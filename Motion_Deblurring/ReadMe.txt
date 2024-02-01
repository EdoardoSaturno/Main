1. Project Title:
   - Fully Convolutional Networks for Image Deblurring 

2. Project Description:
   - The project focuses on deblurring images that are intentionally blurred through a superposition of slightly translated versions of the same image. This method simulates the effects of a shot taken with a shaky hand or a long exposure time. Images for the experiment are derived from MNIST using a specific generator provided in the attached notebook.

3. Usage:
   - Run the provided Python notebook in the repository. The notebook contains a suitable generator to obtain blurred images from MNIST. Mean Squared Error (MSE) is used to evaluate the error between the deblurred image and the ground truth. The computation is repeated over 10 rounds, with the mean MSE and standard deviation reported.

4. Data:
   - MNIST dataset is used.

5. Links to External Resources:
   - [MNIST dataset](http://yann.lecun.com/exdb/mnist/)
   
