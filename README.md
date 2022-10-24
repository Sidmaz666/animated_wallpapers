## Background Wallpaper Animation

A Simple script to set live background wallpaper using feh.


#### Dependencies

1. feh

## Convert GIFs or Video to png's [immagemagick]

Use the following command to extract all the frames from a gif and put all the images in a directory.
**Ensure that all the images are renamed in a serial order for this to work**

        convert -verbose -coalesce input.gif output.png  

## Use the Script To Automatically create frames for Mulitple GIFS!

	cframe [PATH TO DIRECTORY CONTAINING GIFS] [OUTPUT DIRECTORY]
	
	Example:

		cframe ./gifs ./

<img src="https://github.com/Sidmaz666/animated_wallpapers/blob/main/preview.gif" width="100%">

### Installation

Copy  bg-ani file to /usr/bin 
             
         sudo cp bg-ani /usr/bin

### Usage

Run the command bg-ani in terminal with a path to a directory.
         
         bg-ani lone
 
 
