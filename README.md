# Week-7-Readme

1. XSS via Image file
Tried in version 4.2.2
Downloaded an image from internet saved in desktop. 
Added as new media image (as a .jpg)
Added the script a<img src=a onerror=alert(document.cookie)>.jpg in the title field
I clicked on the image and then clicked on view attachment page.
Received error message
GIF walkthrough
<a href="https://imgflip.com/gif/21kh02"><img src="https://i.imgflip.com/21kh02.gif" title="made at imgflip.com"/></a>
