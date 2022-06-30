# Separate

A bash script that uses ImageMagick to separate colors from an image.

```
convert original.jpg -fuzz 5% -channel rgba -fill white +opaque #f7d25d white.jpg
convert original.jpg -fuzz 5% -channel rgba -fill white +opaque #6bccad cyan.jpg
convert original.jpg -fuzz 5% -channel rgba -fill white +opaque #db4f69 magenta.jpg
convert original.jpg -fuzz 5% -channel rgba -fill white +opaque #4e1469 black.jpg
```