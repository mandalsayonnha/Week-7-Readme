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



2. XSS unauthenticated stored cross site scripting
Version tried is 4.2
In the example title page, go to leave a reply, enter script <script>while(1){alert(document.cookie);}</script> in the comment box
Once I hit submit, warning messages started to appear.




GIF walkthrough
The GIP captured could not capture the full screen, showed up as blank

<a href="https://imgflip.com/gif/21kh6d"><img src="https://i.imgflip.com/21kh6d.gif" title="made at imgflip.com"/></a>

