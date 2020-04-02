# MERSF-Sonar-Image-Segmentation
A Robust and Fast Method for Sidescan Sonar Image Segmentation Using Nonlocal Despeckling and Active Contour Model
This software is a matlab version which implemented the method in the paper "A Robust and Fast Method for Sidescan Sonar Image Segmentation Using Nonlocal Despeckling and Active Contour Model "(IEEE TCYB，2017). To use the software, you simply following the steps below:
1. Unzip the “MERSF Segmentation Sidescan sonar image.zip”into your desired directory;
2. Start the Matlab program(a version of R2017B or later is ok);
3. Open the "\MERSF Segmentation Sidescan sonar image\MERSF" directory;
4. You will find five files in the current directory;
5. Simply type "SonarSegmentation" in the cmd window, and press enter key, then a GUI will be loaded;
6. Press the "OpenImage" button, and choose an image file in the "sonar image set" directory;
7. The image to be segmented will be loaded and shown, then press the "ReadParameters" button, and the default parameters for that image will be loaded;
8. You can modify all the parameters to achieve maybe even better results, or you can just press the "TargetDetection" button to start the segmentation;
9. The Segmentation results with different iterations will be displayed in different images;
10. The segmentation will automatically stop if it reaches the convergence, and you can press the "SaveResult" button to save the final segmentation results.
Note：Parameters should be selected according to the noise level of the image, the denosing method and the regions to be segmented can also be switched.  
If you have any problem in using this software, please donnot hesitate to contact me via emai: huoguanying@163.com.
Best regards.
