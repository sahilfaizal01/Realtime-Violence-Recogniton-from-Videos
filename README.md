# Realtime-Violence-Recogniton-from-Videos
This is a computer vision project to recognise violence in real-time from videos.
# Approaches:
1) Using ConvLSTM <br>
2) Using CNN + LSTM <br>
3) Using MobileNetV2 <br>
4) Using MobileNetV2 Bi-LSTM <br>
5) Using SeparableConv2D <br>
6) Using 3D CNN <br>
## Frameworks and Libraries:
* Tensorflow
* Keras
* Matplotlib
* OpenCV
* Numpy
* Pandas
## Notes:
1) Why use TimeDistributed layer instead of Dense layer? <br>
Because we want to keep each timestep value seperate, as in the TimeDistributed layer we apply a dense layer on each timestep.


