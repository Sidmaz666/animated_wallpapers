## Background Wallpaper Animation

A Simple script to set live background wallpaper using feh.


#### Dependencies

1. feh

## Convert GIFs or Video to png's [imagemagick]

Use the following command to extract all the frames from a gif and put all the images in a directory.
**Ensure that all the images are renamed in a serial order for this to work**

        convert -verbose -coalesce input.gif output.png  

![preview](https://github.com/Sidmaz666/animated_wallpapers/blob/main/preview.gif)

### Installation

Copy  bg-ani file to /usr/bin 
             
         sudo cp bg-ani /usr/bin

### Usage

Run the command bg-ani in terminal with a path to a directory.
         
         bg-ani lone
 
 
