# HandGestureRecognition-with-CNN
The objective of this project is to create a 2D Convolutional Network to recognize ten different hand gestures

## Technologies
- TensorFlow v2.10.0 <https://www.tensorflow.org/api_docs/python/tf>

## Dataset
The dataset used for this project was from Kaggle at this link <https://www.kaggle.com/datasets/gti-upm/leapgestrecog>. It contains 20,000 images total of 10 different subjects posing ten different hand gestures. 
Example of how the pictures look:
| Label | Hand Gesture | Image |
| --- | --- | --- |
| 0 | palm |<img src = "https://user-images.githubusercontent.com/52841122/192181144-2990a3b5-1c5e-4c40-ab38-75d4082b522e.png" width = "320">|
| 1 | L | <img src = "https://user-images.githubusercontent.com/52841122/192181212-d1af7069-ba1e-4f04-b5ea-d703c5523f8c.png" width = "320">|
| 2 | fist | <img src = "https://user-images.githubusercontent.com/52841122/192182010-9c9f504c-d4e1-462a-a868-7caa07c86109.png" width = "320">|
| 3 | fist moved | <img src = "https://user-images.githubusercontent.com/52841122/192182102-e3529331-ea4a-4ce1-8c5b-1e7f6d5bc662.png" width = "320">|
| 4 | thumb | <img src = "https://user-images.githubusercontent.com/52841122/192182755-9cbc1e10-a741-4c20-9e30-46b7325662e9.png" width = "320">|
| 5 |index | <img src = "https://user-images.githubusercontent.com/52841122/192182878-c474df1a-04a8-40ef-b444-78726014e15f.png" width = "320">|
| 6 | ok |<img src = "https://user-images.githubusercontent.com/52841122/192182963-f5c98634-eb94-4375-af63-a43b274cd8a4.png" width = "320">|
| 7 |palm moved|<img src = "https://user-images.githubusercontent.com/52841122/192183018-fc31d978-fb42-451c-ad71-5ccca49411a1.png" width = "320">|
| 8 | C |<img src = "https://user-images.githubusercontent.com/52841122/192183059-5511c35a-114a-45ae-bc57-0915bdd6e882.png" width = "320">|
| 9 | down |<img src = "https://user-images.githubusercontent.com/52841122/192183135-1f3145a9-f706-4e0d-bd75-45de3cf5cafa.png" width = "320">|

## Model
<img src = "https://user-images.githubusercontent.com/52841122/192361128-08a0be61-d423-4be8-bc0b-46d70e071782.JPG" width = "450">

## Training
<img src = "https://user-images.githubusercontent.com/52841122/192362697-70f33095-29a7-497d-8f7a-55efcb33252e.JPG" width = "700">

![cnn accuracy](https://user-images.githubusercontent.com/52841122/192432767-b7bfbf42-c314-491f-8460-d4db9eb392bf.JPG)
![cnnloss](https://user-images.githubusercontent.com/52841122/192432795-3b795d3c-549e-456d-9e06-9644cf5911f8.JPG)


## Testing
When evaluating the model against the test set, the Test accuracy = 0.9994999766349792 and the Test Loss = 0.005492622498422861
