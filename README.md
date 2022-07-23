# Machine Learning Based Age Prediction of Coconut
Traditional methods for determining the age of coconuts are time-consuming and cumber-
some in nature. This project aims to classify coconuts according to their age into tender
or mature using machine learning techniques and image data. Transfer learning based so-
lutions are[6] explored in the project. Further, a suitably trained machine learning model
can be incorporated into an Android app for ease of use, decreasing the dependency on
highly skilled palm climbers and farmers to find the age of coconuts.A sample Android
application was built as part of this project.
The initial approach was to consider the problem as a classification task based on only the
image data that was made available. Application of pre-trained models based on VGG16,
ResNet50, and EfficientNet-Lite architectures were analyzed to classify coconut as tender
or mature.
A simple classifier may not be sufficient to perform the prediction correctly in more natural
settings. The presence of leaflets, leaf stalks, and the background can contribute to the scene [4]. Hence an object detection based approach is considered next. Detecting coconut
from its background is needed before classifying it. The similarity between coconut and its
background makes the detection of coconuts in their natural environment very challenging.
Object detection based on EfficientDet and Faster-RCNN were studied in this regard.
