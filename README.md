 # ImageManager

First of all, this is what en empty ImageManager looks like.
![ImageManagerEmpty](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerEmpty.PNG)
The ImageManager can contain an maximum of **15** images.


**Note**
- You can not change then maximum amount of images an ImageManager can hold.
- If you add more nothing will happen and if you then delete some they will not be inserted then.
- The valid image types are: png, jpg and jfif.
 
You can change the Title and the Icon.
![ImageManagerTitlebar](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerTitlebar.PNG)

 ## Usage 
They are 3 ways to get images in the ImageManager while it is running. <br>
You can also use setImages so the ImageManager allready opens with Images.

- Drag and Drop
- The **add** button
- The popup menu
 
 ### Drag and Drop
![ImageManagerDragAndDrop](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerDragAndDrop.jpg)

**Note**

- You can Drag multiple images.
- If you drag something that is not an image the programm will do nothing.
- If the maximum of images is reached it will also do nothing.
- You can drag images between 2 to insert it there.


 ### The **add** Button  
If you right click the button with the **add** button a file dialog will open up and you can navigate to the location where your images are. 


![ImageManagerOpenDialog](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerOpenDialog.PNG)


**Note** 


- You can not drag the **add** button.
- You can only select .png, .jpg and .jfif
- While the open dialog is active the main window is disabled.
- The open dialog will remember your last location and you will start there next time you open it.
- You can even select multiple images.
- If you choose one or more images the **add** button will moove behind the last image.
- If the maximum of 15 images is reached the **add** button will dissapear and come back if there are less then 15.
- The dialog can also be closed with the **esc** key.


 ### The Popup menu
If you left click on a button a popup menu will apear.
The popup menu has 2 options:


1. open


	Will open an open dialog, rules are the same as for the one on the **add** button.
2. save


	Will open an save dialog.

 
![ImageManagerPopUp](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerPopUp.jpg)

**Note**



- Popup menu won`t be shown on the **add** button and on the big button on the left
- The **save** option is disabled if the button does not contain an image.
- The **open** option is disabled if the button does contain an image.
- The save dialog will also remember your last location
- The save dialog can only save in png and jpg.
- The dialog can also be closed with the **esc** key.


 ### The preview Button
The preview button is the bigger button one on the left side.
![ImageManagerPreviewButton](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerPreviewButton.jpg)


If you right click on an image it will set in this button.
![ImageManagerPreviewButtonFilled](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerPreviewButtonFilled.jpg)


If you then click on that big button an new Window will open up with the image, so you can see images with greater heights and widths better.
You can close the window by pressing **esc** or pressing the **X**
![ImageManagerPreviewWindow](https://raw.githubusercontent.com/BBj-Plugins/ImageManager/master/docs/screenshots/ImageManagerPreviewWindow.jpg)


**Note** 


- If the image`s height and width is greater then the window it will be scaled down. 
- If the image`s height and width is smaller then the window it will not be scaled up. 
- The window is always gonna be fullscreen suitable for your screenbounds

 
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
