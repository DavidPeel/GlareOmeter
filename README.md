# GlareOmeter
Windows software to automatically assess glare in aerial survey photos

This is experimental code for testing and evaluation.
No guarantees of the quality or accuracy of the results.

The code relies heavily on the openCV C++ library
http://opencv.org/

The application has no GUI and is a console application. To setup and control edit the file Config.txt

```
#Sampling (eg 2 means analyse every second image)
1
#image extension
JPG
#Output ALL result images (0-No 1-yes)
1
#Normalise images(0-No 1-yes) 
1
# Red threshold Level for glare estimation (these RGB levels were appropriate for finding glare in images where there was no white sand or ice in the images)
177
#Green threshold Level for glare estimation
0
#Blue threshold Level for glare estimation
0
# Image Analysis HORIZONTAL size (this is reduced from the orginal size)
1000
# Image Analysis VERTICAL size (this is reduced from the orginal size)
665
#Path to put result images (not used if 'output ALL result images' is 0)
[insert file folder location here]
#Paths to images (sub folders are searched to so just list the parent folder)
[insert file folder location here]
```

