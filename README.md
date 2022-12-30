# AFFPNG 2.1
**Description:**
This program helps us in displaying png/jpg/bmp images on the screen without a dialog box and at any given coordinates. You can even display multiple Images one after another at the same time which will seem like an animation. you can also adjust the tempo and delay between the images which will make the animation effect faster or slower.

AUTHOR:	**SachaDee**

# USAGE

<code>AffPNG ["Fichier[PNG,GIF,JPG,BMP]Script[TXT]"] [opt. [/XPos "Pixel"]] [opt. [/YPos "Pixel"]] [opt. [/tempo "Milliseconde"]] Script [opt. [/Vitesse "Milliseconde"]]</code>

Where: 

    PNG/GIF/JPG/BMP/Script.txt 	:	Path of the Image file or Path to the Text file (containing all the image names, seperated by comma)  
    /XPos				:	To Modify the X position of the Imgae on Screen (in center by default)  
    /YPos				:	To Modify the Y position of the Imgae on Screen (in center by default)  
    /tempo				:	To adjust the Tempo of Output in milliseconds 
    /Vitesse			:	To Modify the default speed of OUTPUT in milliseconds 
    
# Demonstration

To demonstrate this plugin here I have displayed an Image named zoro.jpg at coordinates (300,300) without any dialog box.
<!-- wp:code -->
<pre class="wp-block-code"><code>affpngv21 zoro.jpg /xpos 300 /ypos 300</code></pre>
<!-- /wp:code -->
![image](https://user-images.githubusercontent.com/82807654/210067864-6217f23f-1c7f-4f0f-acfe-ad012237d976.png)

For displaying multiple Images one after another we have to make a text file that contains the name of all the images separated by a comma. Then run the AFFPNG plugin with the path of the text file instead of the image. As in the example below, I have displayed 7 images with a time delay of 500 milliseconds.
<!-- wp:code -->
<pre class="wp-block-code"><code>affpngv21 script.txt /xpos 350 /ypos 400 /Vitesse 500</code></pre>
<!-- /wp:code -->
![image](https://user-images.githubusercontent.com/82807654/210067923-f58b47be-d708-45ef-a447-55b3a4fc62c9.png)

Article-https://batch-man.com/affpng/

Video-https://www.youtube.com/watch?v=8UKte1n9yyc&t=1s


// *** AFFPNG.EXE 2.1 By SachaDee (c) 2014 *** \\
