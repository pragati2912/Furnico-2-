Place your two-seater JPEG at this path so the site will display it:

`assets/images/two-seater-image.jpg`

Recommended steps:

- If you have the image on your machine, copy it into the folder:

  Powershell:

  cd 'c:\Users\GEU\Desktop\file\furniture-site\assets\images'
  cp 'C:\path\to\your\two-seater.jpg' 'two-seater-image.jpg'

- Or rename your existing file to `two-seater-image.jpg`.

- The `index.html` product card already references this filename. The image will be loaded with `loading="lazy"` for faster initial load.

Helpful conversions (optional):

- To convert PNG to JPEG using ImageMagick:

  magick convert two-seater.png -quality 85 two-seater-image.jpg

- To resize to 1200px wide (keep aspect ratio):

  magick convert input.jpg -resize 1200 two-seater-image.jpg
