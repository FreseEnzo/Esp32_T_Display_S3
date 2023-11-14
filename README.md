# Esp32_T_Display_S3
- Some tricks to use this Lilygo Esp-32 and how to add images and gifs very easy.

# Step-by-step Guide
Setting up your workspace
  1. Configure your Visual Studio Code for Python compiling
  2. Add PlatformIo extention in your VSCode (This should take a few minutes)
  3. Go to https://github.com/Xinyuan-LilyGO/T-Display-S3 and clone the repository
     
Making a cool GIF
  1. Download or make a GIF in some website
  2. Resize your gif to (135 x 245)px (It can changes depending your choice for orientation)
     
Creating a .h from your GIF code 
  1. Go to https://github.com/bitbank2/image_to_c and clone the repository
  2. Go to your dist folder in the repository abovve, paste your gif and execute in the prompt command
```
./image_to_c64.exe your_gif.gif > out.h
```
  3. Make sure that a out.h has been created in this folder
Building your project



