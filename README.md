# Aaron Walber's Data Science Portfolio

## <u>Kaggle Datasets</u>:
### <b>[Fake News](https://www.kaggle.com/c/fake-news)</b>
This competition involved creating a classifier to determine if the selected news article might be fake news. For this competition, I designed a simple LSTM neural network using Pytorch. My Kaggle kernel can be found [here](https://www.kaggle.com/awalber94/fake-news-prediction-using-lstm-neural-network), and the code used to submit to the competition can be found on [Github](https://github.com/awalber/fake-news-detector). The trained model scored 95.8% accuracy on the testing data.

### <b>[Dog and Cat Classifier](https://www.kaggle.com/tongpython/cat-and-dog)</b>
This project involved training a classifier for images of cats and dogs. To solve this problem, I used transfer learning to fine-tune the classification layer of a pre-trained CNN. The Kaggle kernel for this project can be found [here](https://www.kaggle.com/awalber94/cnn-classifier-with-transfer-learning-resnet-18). A [Github](https://github.com/awalber/cat-dog-classification) repository was also created for this work, which has more discussion on the fundamentals used in this technique.

## <u>Personal Projects:</u>
### <b>Building an R-CNN from scratch with Pytorch and OpenCV</b>
The main motive of this project was to learn and explain how an R-CNN operates. Understanding the fundamentals of an R-CNN is important because it has become the backbone for modern computer vision techniques, such as Faster R-CNN. For this project, a pre-trained ResNet model was used in conjunction with OpenCV to create and predict bounding boxes for a single image. The code for this project can be found on [here](https://github.com/awalber/rcnn).