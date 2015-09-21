Hello !
welcome to the readme file for DeepVision website code.

In this code there are several animations which involving images and scripts.
I'll start explaining at the code after <header> tag. (line 112 in Dw)

We use <div> attribute to make our website more organize.
the first section is the section with brain picture. for this brain image, we use two different function.
1. showBrain (when cursor is hovering above the picture and when the brain tumor is clicked (used in mobile website))
2. offBrain (when cursor is not on the picture)

the second section is the section with a picture of a woman wearing black jacket. for this one, there are several animations in it. It involves three area for mouse hover. (I don't think that the mousedown attribute for this is necessary, but I'll just leave it anyway.)
I. First area is the left jacket. it has 3 functions in it
	1. showJacketLeft (when the cursor is hovering on the area, and when area is clicke.)
	2. offJacketLeft (when cursor is not on the picture)
	3. glasses (to change the z-Index of the images)
these function is also applicable to other area of hover.

I'll skip to  the bottom of the file.
 there are bunch of script.
the first eight script is the function for resizing the image dimension and position
the last two script is just to change the position of the images