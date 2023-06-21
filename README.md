# Realtime-Violence-Recogniton-from-Videos
This is a computer vision project to recognise violence in real-time from videos.
# Approaches:
1) Using ConvLSTM (Video) - Accuracy: 78% <br>
2) Using CNN + LSTM (Frames) - Accuracy: 100% <br>
3) Using MobileNetV2 (Frames) - Accuracy: 88% <br>
4) Using MobileNetV2 Bi-LSTM (Video) - Accuracy: 88% <br>
5) Using 3D CNN <br>
6) Using LRCN Approach <br>
## Frameworks and Libraries:
* Tensorflow
* Keras
* Matplotlib
* OpenCV
* Numpy
* Pandas
## Link
* Features extracted to create the dataset (Size: 128 * 128 * 3 and SequenceStep:20)- https://drive.google.com/drive/folders/13U6j0cJK3N0eAtHcu2AmR0sl_djyqe2c?usp=share_link
## Notes:
1) Why use TimeDistributed layer instead of Dense layer? <br>
Because we want to keep each timestep value seperate, as in the TimeDistributed layer we apply a dense layer on each timestep.
## References:
https://www.tensorflow.org/tutorials/video/video_classification

https://github.com/kcct-fujimotolab/3DCNN

