# CheckableImageView
An ImageView that can be check/uncheck with materialized animation.

# Download
[![](https://jitpack.io/v/Tornaco/CheckableImageView.svg)](https://jitpack.io/#Tornaco/CheckableImageView)

# Sample code
```java
    final CheckableImageView checkableImageView = (CheckableImageView) findViewById(R.id.image_view);
        checkableImageView.setImageDrawable(ContextCompat.getDrawable(this, R.mipmap.ic_launcher_round));

        checkableImageView.setOnClickListener(new View.OnClickListener() {
            @Override
            public void onClick(View v) {
                checkableImageView.setChecked(!checkableImageView.isChecked());
            }
        });
```

