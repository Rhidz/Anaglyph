# Anaglyph

#### A 3D effect is produced by superimposing two images in different color channels on top of each other.

### Anaglyh with translation

Adding a slight translation to the original image on the left.

<img src="https://github.com/Rhidz/Anaglyph/blob/main/Anaglyph/output.png" align="center"
     width="600" height="400">

Finding key points in the two matches to check for correspondence. 

<img src="https://github.com/Rhidz/Anaglyph/blob/main/Anaglyph/Matched%20Features.png" align="center"
     width="600" height="400">

Registering the two images by finding homography inbetween them.

<img src="https://github.com/Rhidz/Anaglyph/blob/main/Anaglyph/Registering%20Image%20using%20Homography.png" align="center"
     width="600" height="400">

Putting the images in two different color channels.

<img src="https://github.com/Rhidz/Anaglyph/blob/main/Anaglyph/Color%20Channels.png" align="center"
     width="600" height="400">

Superimposing the images on top of each other.

<img src="https://github.com/Rhidz/Anaglyph/blob/main/Anaglyph/first_anaglyph.png" align="center"
     width="280" height="400">

### Anaglyh with rotation
The previous steps were followed but this time instead of adding a translation a slight rotation was to the image. 

<img src="https://github.com/Rhidz/Anaglyph/blob/main/Anaglyph/rotated_images.png" align="center"
     width="600" height="400">

<img src="https://github.com/Rhidz/Anaglyph/blob/main/Anaglyph/rotated_images_in_diff_color_channels.png" align="center"
     width="600" height="400">

Final image after superimposing. 

<img src="https://github.com/Rhidz/Anaglyph/blob/main/Anaglyph/rotated_anaglyph.png" align="center"
     width="280" height="400">




     
