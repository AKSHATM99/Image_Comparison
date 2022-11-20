# Image_Comparison by using Structural Similarity Index (SSIM)
### In this program , I am comparing 2 images (provided as input by user) on the basis of Structural Similarity. I am using Structural Similarity Index for comparison. When comparing images, the mean squared error (MSE)–while simple to implement–is not highly indicative of perceived similarity. Structural similarity aims to address this shortcoming by taking texture into account. 
Steps -
* First of all two images are provides by the user as input to the program .
* Then we are resizing both images and making them same in size.
* Images are passed to the SSIM function and function returns the value between '0 to 1 '.
* Here 1 means perfectly similar and 0 means totally diffrent .
###
### In future I want to convert this whole program into a webapp by using ' FLASK ' .  ###

## Case 1 - When images are similar - 
![100%](https://github.com/AKSHATM99/Image_Comparison/blob/main/Assets/100%25.png)

## Case 2 - When similarity is less - 
![10%](https://github.com/AKSHATM99/Image_Comparison/blob/main/Assets/10%25.png)

## Tools Used-
1. OpenCV
2. SSIM
3. Numpy
4. Python 3.8
5. Jupyter Notebook
