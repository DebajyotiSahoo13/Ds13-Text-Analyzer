# Text Analyzer

<p align="center">
  <img class="center" src ="https://postimg.cc/Wdct7cNZ" alt="Drawing" style="width: 1400px; height: 600px">
</p>

<b>Description : </b> Here I used **Artificial Intelligence** in diagnosing plant diseases. Various diseases like early blight and late blight immensely influence the quality and quantity of the potatoes and manual interpretation of these leaf diseases is quite time-taking and cumbersome. Therefore I created a **Web App** using <b>Streamlit</b> which simply classify <b>Potato Leaf Diseases</b> and, finally deployed the Web-app on **Heroku**. Internally, our model is built using a simple <b>Convolutional Neural Network Architecture</b> to classify <b>Potato Leaf Diseases</b>. Initially I collected ready-made data from internet. Then due to small size of dataset, I used one of the simple and effective method, called <b>Data Augmentation</b> to increase the size of dataset as well as to reduce overfitting of our model. At the end built a **Deep Learning Model** to detect or classify Potato Leaf Diseases and got a **test accuracy of 97%.**

<b>Aim : </b>
<ul>
  <li>The project focuses on <b>diagnosing plant diseases</b> using Machine Learning.</li>
  <li>Various diseases like early blight and late blight immensely influence the quality and quantity of the potatoes, and manual interpretation of these leaf diseases is quite time-taking and cumbersome. </li>
  <li>This is a WebApp made using Streamlit, and the app is deployed on Heroku. The app classifies <b>Potato Leaf Diseases</b>.</li>
  <li>Internally, we use a simple <b>Convolutional Neural Network Architecture to build our model</b>. We use this model to classify <b>Potato Leaf Diseases</b>. The data source and data structure are mentioned.</li>
  <li>Due to the small dataset size, we used <b>Data Augmentation</b> to increase the dataset's height and reduce the overfitting of our model.</li>
  <li>The <b>Deep Learning Model</b> used to detect or classify Potato Leaf Diseases has a <b>test accuracy of 97%</b>.</li>
</ul>


<b>Heroku App : https://potato-leaf-disease-detection.herokuapp.com/</b><br>


<b>Sample Output : </b> The output is showing 3 thing's.

- <b>Predicted Class : </b>The model's output.
- <b>Actual Class : </b>The actual output.
- <b>Confidence : </b>How confident our model is.

https://user-images.githubusercontent.com/72561319/186013450-13591326-cdd7-4f71-b7d4-6e919bd33255.mp4

<p align="center">
  <img class="center" src ="/main/sample/potato.png" alt="Drawing" style="width: 1400px; height: 800px">
</p>

<b>Folder Structure : </b>

```
                    Potato Leaf Dataset       --> main folder
                      ----| train
                          ----| Potato_Healthy
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Early_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Late_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg

                      ----| test
                          ----| Potato_Healthy
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Early_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Late_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg

                      ----| valid
                          ----| Potato_Healthy
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Early_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
                          ----| Potato_Late_Blight
                              ----| img1.jpg
                              ----| img2.jpg
                              ----| img3.jpg
```
