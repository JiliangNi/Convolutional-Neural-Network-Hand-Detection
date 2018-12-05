CS175RCNN_Model: It is the directory including the RCNN Model that we finally produced by training the data.
src\models-master: It is a directory including the tool called Tensorflow Object Detection API which we used to train the model. We downloaded it from github. The link is https://github.com/tensorflow/models/tree/master/research/object_detection.
New_data: It is the directory including some new photos which we made as test data. In the directory of "\models-master\research\Dataset", we resized the data in "Color" to "Resized" directory, then we transferred the data in "Resized" to TFRecords which is in "\models-master\research\object_detection\TrainingData".
utils: It is a directory in the "models-master", which should be imported in the project.ipnb file. It contains the methods which we have to use.
src\faster_rcnn_nas_lowproposals_coco.config: This is the configuration file of RCNN model. We used it at the beginning, but the performance was not good, so we switch another one.
src\faster_rcnn_resnet50_coco.config: This is the configuration file of the RCNN model. We finally used this model to train the data.
src\Help.txt: It is a file including commands which are used in terminal to produce the "CS175RCNN_Model" directory.
Map.pbxt: It is file including the information about Hand class and its ID, which will be used in project.ipnb file.
