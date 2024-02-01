/*
 * Copyright 2024 Edoardo Saturno
 *
 * Licensed under the Apache License, Version 2.0 (the "License");
 * you may not use this file except in compliance with the License.
 * You may obtain a copy of the License at
 *
 *     http://www.apache.org/licenses/LICENSE-2.0
 *
 * Unless required by applicable law or agreed to in writing, software
 * distributed under the License is distributed on an "AS IS" BASIS,
 * WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 * See the License for the specific language governing permissions and
 * limitations under the License.
 */

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
   
