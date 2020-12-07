# Filter
- 0 ------------------------255
- 00000000------------------11111111
- 1 byte(8 BITES) PPER COLOR
-- 3 bytes(24 bits) per pixel
# Sepia
- Most image editing programs support a "sepia filter, which gives images an old-timely feel by making the whole image look a bit reddish-brown.
- sepiaRed = .393 * originalRed + .769 * originalGreen + .189 * originalBlue
- sepiaGreen = .349 * originalRed + .686 * originalGreen + .168 * originalBlue
- sepiaBlue = .272 * originalRed + .534 * originalGreen + .131 * originalBlue
# Reflection
Some fliters might also move pixels around. Reflecting an image, for example, is a filter where the resulting image is what you would get by placing the original image in front of a mirror. So any pixels on the left side of the image should end up n the right, adn vice versa.
#Blur
- There are a number of ways to create the effect of blurring or softing an image. For this problem, we will use "box blur", which workss by taking each pixel and, for each color value, giving it a new value by averaging the color values of neighboring pixels.
# Image transformations
- OpenCV can perform rotating image
- A rotation matrix used to perform rotation in Euclidan space
- It rotates points in the xy-plane counter clockwise through an angle theta aoobuth the origin
# Translation
- Shifting an object in x or y direction
- OpenCV uses Translational matrix T, Tx, Ty
# Resizing
- cv.INTER_AREA for shrinking, cv.INTER_CUBIC for zooming
