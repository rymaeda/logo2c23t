# Customize the initial screen of your Fnirsi 2C23T!!

If you are searching for a way to customize the splash screen of a Fnirsi multimeter-oscilloscope 2C23T, I think I can help you.

Here, I am sharing some images ready to be installed on that device, and I am also sharing the GIMP file used to generate these images, so you can create your own custom images.

![Custom splash screens](https://github.com/rymaeda/logo2c23t/blob/main/logo2c23.gif)


## Files in this repo

**image-srcs.zip**: source image files use to produce my images. Some of the images was created by Copilot and some come from Freepiks.com. The Fnirsi logo was grabed of image on official site with the use of inkscape to catch them vectorized.

**logo2c23-collection001.zip**: some images generated.

**logo2c23.gif**: the animated image above, just to illustrate some results.

**logo2c23-GIMP.zip**: this can be you initial file to produce your custom screen images.


## My GIMP-way to produce custom screens

1. Install GIMP.
2. Open the logo2c23.xcf packed in logo2c23-GIMP.zip just above.
3. Open **your** custom image on GIMP, by right click on it and choosing "open with Gimp".
4. You need Resize your custom image with [Image] -> [Scale Image...], in such way that the width will be equal or more than 320 and the height will be equal or more than 240 pixels.
5. Now you need to adjust the [Image] -> [Canvas Size...] to 320 x 240 pixels.
6. Copy the image with control+'A' followed by control+'C'.
7. Go to logo2c23.xcf project.
8. Paste the previous copied image in a new layer with [Edit] -> [Paste As...] -> [New Layer]
9. Invert the image vertically with [Image] -> [Transform] -> [Flip Vertically]
10. Connect the Fnirsi 2C23T to the computer with the USB cable.
11. Now you can generate your custom image with [File] -> [Export As...], on the "Export Image" dialog, rename the file to "logo2c23-aa.bmp".
12. On the "Export Image as BMP", mark the "Do not write color space information" and the "R5 G6 B5" options. Click On "Export". Done!
