# DigitalImageProcessingHW-1
 MSRA10 dataset usage for combineForegroundBackground, gaussianSmoothing and unsharpingMasking methods. You can directly run codes on Google Colab.
 
 <h2> 🚀  Images that I used from MSRA10 dataset </h2>
<p align="left">
 
 <img width="913" alt="Screenshot 2023-05-11 at 02 50 51" src="https://github.com/iremsilamadenli/DigitalImageProcessingHW-1/assets/93054796/988b760b-a0d1-48ef-8c06-366d402bc4c0" height="600">

 
 <h2> 🚀 Task 1 results </h2>
<p align="left">
 
 Since placing the foreground images into the images, I have to change top left corners places. The background picture is 900x1044 pixels, and my foreground image is 400x 266. This task was about combining different images without overflowing any pixel.
 
 <img width="913" alt="Screenshot 2023-05-11 at 02 51 07" src="https://github.com/iremsilamadenli/DigitalImageProcessingHW-1/assets/93054796/1aae2600-4d37-4242-8e43-6e00c5e40dab" height="600">

  <h2> 🚀 Task 2 results </h2>
<p align="left">
 
 In this part I only used background for smoothing. I know I didnot used clear and sharp background image to see smoothing easily but when I first applied the 3 and 8 values as sigma values for Gaussian Smoothing. When we increase the value of sigma in smoothing, it gets blurry.

 <img width="243" alt="Screenshot 2023-05-11 at 02 59 35" src="https://github.com/iremsilamadenli/DigitalImageProcessingHW-1/assets/93054796/28c95c25-c4e6-4ebb-a45a-85c3a9829392" height="500">
 
 In this part I only used foreground for sharpening. I used same sigma values here. Even the sigma value is 3, it looks still sharpened as 8. As you can see The color of the dog's ear turned red from the holder. Light colors got darker to increase sharpness
 
<img width="328" alt="Screenshot 2023-05-11 at 02 51 53" src="https://github.com/iremsilamadenli/DigitalImageProcessingHW-1/assets/93054796/558f08c1-98ec-4e4d-9084-4d1723daee90" height="600" >

 It is smaller than previous parts values but you can still see the difference when you comparing the original combined image
 
<img width="330" alt="Screenshot 2023-05-11 at 02 51 37" src="https://github.com/iremsilamadenli/DigitalImageProcessingHW-1/assets/93054796/0e5153f6-1175-4099-a310-d6408c9f49cf" height="600" >
 
