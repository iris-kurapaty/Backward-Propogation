# Neural Networks: Backward Propogation

Backpropagation is a supervised learning algorithm, for training Multi-layer Perceptrons (Artificial Neural Networks). This project includes an excel file that explains the back propogation step in detail. The images below give us a glimpse of the file uploaded.

PFB the screen shot of the excel file.

![image](https://user-images.githubusercontent.com/52544352/135705751-18dcf62c-08bb-4233-b6e3-7f776c4f8881.png)

![image](https://user-images.githubusercontent.com/52544352/135705765-ac0c34ac-a54b-40b6-881f-2ac818c098a8.png)

The Backpropagation algorithm looks for the minimum value of the error function in weight space using a technique called the delta rule or gradient descent. The weights that minimize the error function is then considered to be a solution to the learning problem. 

The major steps in Backpropogation are:

1. Calculate the error – In the image we see a E_total that is the sum of errors, E1 & E2 which are the difference between the outputs of the first model & the expected outputs.
2. Minimum Error/Calculate the gradients – To minimize errors, we calculate the partial derivates of the Error with respect to all the weights.
3. Update the parameters – If the error is huge then, update the parameters (only weights are considered in this example) using a defined learning rate. After that again check the error. Repeat the process until the error becomes minimum.

We can see the changes in the error graph with changes in the learning rate. 
  a. Learning rate = 0. 1 <br/>
  ![image](https://user-images.githubusercontent.com/52544352/135705621-8451f141-153c-48a7-bec0-64999c754260.png)

  b. Learning rate = 0. 2 <br/>break <br/>
  ![image](https://user-images.githubusercontent.com/52544352/135705589-337ca778-43e7-4a30-9cb5-717eee57230a.png)

  c. Learning rate = 0. 5 <br/>break <br/>
  ![image](https://user-images.githubusercontent.com/52544352/135705627-8a7002cc-bc30-40b8-8a6d-9f0766dd3e46.png)

  d. Learning rate = 0. 8 <br/>
  ![image](https://user-images.githubusercontent.com/52544352/135705630-9b142e51-6b5a-4671-abe0-4d3d25b81958.png)

  e. Learning rate = 1 <br/>
  ![image](https://user-images.githubusercontent.com/52544352/135705633-e4960a5c-7264-4e59-acda-e3474f335b28.png)

  f. Learning rate = 2 <br/>
  ![image](https://user-images.githubusercontent.com/52544352/135705642-112019e0-7640-46d4-a534-3d3784968194.png)
