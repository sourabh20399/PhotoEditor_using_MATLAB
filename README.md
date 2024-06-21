# Photo Editor using MATLAB

<br/>

**Abstract**

Image processing is a very useful technology whose demand has been increasing steadi- ly. The rapid acceleration of computer vision, thanks to deep learning and the emergence of open source projects and large image databases only increased the need for image processing tools. Efforts are continuously being made to integrate both these technologies together to provide better performance for the user.

There is a need for a portable image editing tool, as this feature is not available in MATLAB. Although codes can be written in MATLAB for basic functions such as altering the brightness and saturations, there is no interface for the user to freely vary the degree of change of such features. The project that was done as a part of the internship aims to design an app that performimage manipulation and pre-processing. This app can be inte- grated into MATLAB and can also be used as a standalone executable application.

<br/>

**Project Details**


The main aim of the project is to create an app using the MATLAB App Creator Tool that can be used to perform pre-processing and filtering of images.

The pre-processing operations that can be carried out by the app include resizing the im- age, changing the orientation of the image and adjustment of the colour profile of the im- age. Figure 2.1 is a block diagram that shows the basic functionalities of the app.

![Aspose Words bd8a7c88-00d5-4569-8edf-5259afb95d52 003](https://github.com/sourabh20399/PhotoEditor_using_MATLAB/assets/84284202/5a7a513f-e12a-4b4c-b191-647c177994d0)


The image can be imported directly from the device into the app. This helps in reducing the time taken for carrying out the entire process. The preview provides two different views of the image. One is the regular view and the other is the histogram view. An image histo- gram is a type of histogram that acts as a graphical representation of the tonal distribution in a digital image. This can be useful in finding objects of a particular colour in an image.

Resizing is mainly done using crop function. Rotate and flip operations are carried out to change the orientation of the image. The brightness, contrast, saturation and temperature of the image can be adjusted as per the requirements. The sharpness of the image can also be changed.

The app also allows users to apply filters that can assist in the next step of the process. The filters that are included in this project are Black and White filter, Sepia filter, Negative filter, etc. The actions taken are easily reversible. Each action history is stored and the us-

er can jump back as many steps as required. The image can be saved on to the device or it can be used in a MATLAB function that carries out further processing to extract useful information from the image. Some examples of the various functions available are shown in the picture below

![Aspose Words bd8a7c88-00d5-4569-8edf-5259afb95d52 004](https://github.com/sourabh20399/PhotoEditor_using_MATLAB/assets/84284202/737714d1-422e-4441-903e-b5e4aa3607e5)

<br/>

**Conclusion**

An app was designed to allow the user to carry out many of the pre-processing functions within MATLAB itself. Usually, all the functionalities provided by this app are carried out in some other app and then the image is loaded into MATLAB for complex processing or fea- ture extraction. The other option is to carry out these steps in the program itself which may be undesirable. This app allows the user to carry out these functions without having to switch between MATLAB and another app which reduces the turnaround time and hence improves the performance.


• Please read the 'PhotoEditor MATLAB Report' for general working of the app.  
• Refer 'PhotoEditor MATLAB Code' for the working code of the app.  
• There are 2 versions of the app - 'app1.mlapp' and 'PhotoEditor_alpha.mlappinstall'

