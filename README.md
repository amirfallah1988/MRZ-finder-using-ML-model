# MRZ-finder-using-ML-model
In this repository, I introduced a simple method to find machine readable zone (MRZ) region. This region is a common reason in identification documents such as passports. To solve the problem, I used a CNN model plus some techniques (and also some tricks) based on image processing. I had to create a synthetic dataset to train my model.<br>
# Notes:
<ol>
1. Time complexity is a crucial thing in problems like this. So I tried to design a simple and efficient model at the same time.<br>
2. I assumed that the input image contains mrz. So there is no policies for times that there is no mrz in image. Obviously, it is easy to add some policies to handle this situation (maybe I will add it later!)<br>
3. The program is based on python and tensorflow v.2. To run the code and see the results on your local system, be sure to install the required packages. </ol>
