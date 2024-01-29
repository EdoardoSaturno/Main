The project involves deblurring images. The blurred version is obtained through a superposition of slightly translated versions of the same image, following a random trajectory. This kind of blur is supposed to simulate the result of a shot taken with a shaky hand, or with a long exposure time.

Images are obtained from MNIST by means of a suitable generator provided in the attached notebook.

Mean Squared Error (mse) is used to evaluate the error between the deblurred image and the ground truth. it is computed over 10000 blurred versions of the test set.
The prevevious computation is repeated 10 times, and gives as a result the mean mse over the ten rounds, along with the standard deviation.