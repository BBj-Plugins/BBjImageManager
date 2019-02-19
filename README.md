 # ImageManager

 ## Introduction
 The ImageManager lets you display a list of images(maximum 15) whose order you can adapt by either removing and adding the images in the desired order, or by dragging and dropping them into the desired location.
 By clicking on an image loaded into the ImageManager, the preview button on the left will automatically show the selected image.
 By clicking on the preview button the image will be displayed in a separate preview window(full screen).s
![ImageManagerEmpty](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerExampleInsert1.jpg)


**Note**
- You can not change then maximum amount of images.
- The valid image types are: png, jpg and jfif.
 
You can change the Title and the Icon.


![ImageManagerTitlebar](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerTitlebar.PNG)

 ## Usage 
 You can load images into the ImageManager by:
 - Dragging and Dropping the image(s) 
 - by clicking the add button and then selecting the images you want to add.
 - by right clicking on the empty image buttons and selecting the open option.

**Note**
- Only valid image formats can be used: .png, .jpg, .jfif
- You can add multiple images at once.
- You can only save the images in .png and .jpg. 
 
 ### Mooving the images
You can drag one image on to another one and they will switch places.


Also they are little seperators between each button. 


You can drag images on to them. 


This will cause the image to go between the two images the seperator was located.


Here is an example:
![ImageManagerExampleInsert1](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerExampleInsert1.jpg)
![ImageManagerExampleInsert2](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerExampleInsert2.jpg)

 ### The cancel button
This button will bring up an popup wich will ask you if you really want to close the programm or else unsaved changes will be discarded.
If you hit **ok** it will close, if you hit **cancel** you will be able to continue to use the ImageManager.

 ### The save button 
Saves the current state of the ImageManager, wich means if you have 10 images in it, it will close and return an blob array of the images. 
