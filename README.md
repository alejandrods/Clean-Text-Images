# Clean_Text_Images
Clean Automatically Text from Images


Function to Clean Text Automatically
Take the images and convert it to gray scale and we measure the number of white pixels (between 245 - 255) in the bottom of the image. Then we convert the image to blur scale and calculate the lines, if the slope of the lines is between -0.06 and 0.06 we return the values. Finally, we delete that part of the images.

* 1.- We convert the image to grayscale
* 2.- Take the 25% bottom part of the image 
* 3.- Count the number of white pixels (white pixels >= 250)
* 4.- If the number of white pixels is more than 90000 we apply this:
* 5.- Convert the image to blurscale
* 6.- Calculate the lines and slope
* 7.- If the slope is between -0.06 and 0.06 return this values
* 8.- If we have slope between -0.06 and 0.06 take the minimum line in y axis.
* 9.- Delete from that point to the end of the picture

## Result

![alt text](https://github.com/alejandrods/Clean_Text_Images/blob/master/Imgs/Result.png)

