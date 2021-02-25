# ECG_classification_using_2d_CNN
Using 2d cnn models for classification of 1d ecg signals by first converting the 1d signal to an image and then passing it to the cnn.
<br>
<b>Sample ECG image graphs created from 1d signals</b><br>
![Alt text](/Images/ecg_graphs.png?raw=true "Sample Ecg Graphs")
<b>Dataset Used:</b>  <b>MIT-BIH Arrhythmia</b> Dataset from: https://www.kaggle.com/shayanfazeli/heartbeat
<br>
The implementation is done in <b>PyTorch</b><br>
<b>Model Used:</b> Resnet34<br>
<b>Train Acc:</b> 97.38<br>
<b>Val Acc:</b> 93.55<br>
<b>Test Acc:</b> 93.57<br>
<b>Confusion Matrix:</b><br>
![Alt text](/Images/Confusion_Matrix.JPG?raw=true "Confusion Matrix")
<br>
*Also implemented <b>CAM</b> to visualize important portions of the ecg graph image which leads to the corresponding predicted class*
<br>
