# Emotion-Classify

* 一个学习大神的CNN表情识别demo
* csv2tfrecord就是把fer2013这个数据集转化成tfrecord
* cnn_cv_tfrecord为训练代码
* load_meta_cnn为预测代码
* temp/cv/fer2013/里放fer2013.scv数据集
  temp/cv/cnn_inuse为训练后的模型
  temp/cv/pic放要进行预测的图片
* 本人测试环境 pyhton==3.6.4 tensorflow-gpu==1.13.1 cuda==10 cudnn==7.4.3