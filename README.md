 # ImageManager

 ##Introduction
First of all, this is what en empty ImageManager looks like.
!(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/ImageManagerEmpty.PNG)
The Imagemanager can contain an maximum of **15** images.
**Note**<br>
<ul>
<li>You can not change then maximum amount of images an ImageManager can hold.</li>
<li>If you add more nothing will happen and if you then delete some they will not be inserted then.</li>
<li>The valid image types are: png, jpg and jfif.</li>
</ul>
 
You can change the Title and the Icon.
!(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/ImageManagerTitlebar.PNG)

 ##Usage 

They are 3 ways to get images in the ImageManager while it is running. <br>
You can also use setImages so the ImageManager allready opens with Images.

<ol>
<li>Drag and Drop</li>
<li>The **plus** button</li>
<li>The popup menu</li>
</ol>
 
 ###Drag and Drop
(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/ImageManagerDragAndDrop.jpg

**Note**
<ul>
<li>You can Drag multiple images.</li>
<li>If you drag something that is not an image the programm will do nothing.</li>
<li>If the maximum of images is reached it will also do nothing.</li>
<li>You can drag images between 2 to insert it there.</li>
</ul>

 ###The **plus** Button  
If you right click the button with the **plus** icon a file dialog will open up and you can navigate to the location where your images are. 
(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/ImageManagerEmpty.PNG)
**Note** <br>
<ul>
<il>You can not drag the **plus**.</il>
<li>You can only select .png, .jpg and .jfif</li>
<li>While the open dialog is active the main window is disabled.</li>
<li>The open dialog will remember your last location and you will start there next time you open it.</li>
<li>You can even select multiple images.</li>
<li>If you choose one or more images the **plus** icon will moove behind the last image.</li>
<li>If the maximum of 15 images is reached the **plus** will dissapear and come back if there are less then 15.</li>
<li>The dialog can also be closed with the **esc** key.</li>
</ul>

 ###The Popup menu
If you left click on a button a popup menu will apear.
The popup menu has 2 options
<ol>
<li>open</li>
	<li>Will open an open dialog, rules are the same as for the one on **plus** button.</li>
<li>save</li>
	<li>Will open an save dialog.</li>	
</ol>
 
(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/

**Note** <br>
<ul>
<il>Popup menu won`t be shown on the **plus** button and on the big button on the left</il>
<il>The **save** option is disabled if the button does not contain an image.</il>
<il>The **open** option is disabled if the button does contain an image.</il>
<il>The save dialog will also remember your last location</il>
<il>The save dialog can only save in png and jpg.</il>
<il>The dialog can also be closed with the **esc** key.</li>
</ul>

 ###The preview Button
The preview button is the bigger button one on the left side.
(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/
If you right click on an image it will set in this button.
(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/
If you then click on that big button an new Window will open up with the image, so you can see images with greater heights and widths better.
(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/
You can close the window by pressing **esc** or pressing the **X**

**Note** <br>
<ul>
<il>If the image`s height and width is greater then the window it will be scaled down. </il>
<il>If the image`s height and width is smaller then the window it will not be scaled up. </il>
<il>The window is always gonna be fullscreen suitable for your screenbounds</il> 
</ul>
 
 ###Mooving the images
You can drag one image on to another one and they will switch places.
Also they are little seperators between each button. You can drag images on to them. 
This will cause the image to go between the two images the seperator was located.
Here an example
(https://github.com/BBj-Plugins/ImageManager/blob/master/docs/screenshots/

 ###The cancel button
This button will bring up an popup wich will ask you if you really want to close the programm or else unsaved changes will be discarded.
If you hit **ok** it will close, if you hit **cancel** you will be able to continue to use the ImageManager.

 ###The save button 
Saves the current state of the ImageManager, wich means if you have 10 images in it, it will close and return an blob array of the images. 
