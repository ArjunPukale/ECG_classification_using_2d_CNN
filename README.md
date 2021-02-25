# ECG_classification_using_2d_CNN
Using 2d cnn models for classification of 1d ecg signals by first converting the 1d signal in an image and then passing it to the cnn.
<br>
<b>Dataset Used:</b>  MIT-BIH Arrhythmia Dataset from: https://www.kaggle.com/shayanfazeli/heartbeat
<br>
The implementation is done in <b>PyTorch</b><br>
<b>Model Used:</b> Resnet34<br>
<b>Train Acc:</b> 97.38<br>
<b>Val Acc:</b> 93.55<br>
<b>Test Acc:</b> 93.57<br>
<b>Confusion Matrix:</b>
https://github.com/ArjunPukale/ECG_classification_using_2d_CNN/blob/main/Images/Confusion_Matrix.JPG
<br>
Also implemented CAM to visualize important portions of the ecg graph image which leads to the corresponding predicted class
<br>

