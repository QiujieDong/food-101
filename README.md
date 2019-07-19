# food-101

本代码是对food-101的训练与预测，使用的是ResNet50的迁移学习搭建模型。

环境：python3.6, tensorflow==1.8.0

- [[food-101]](http://data.vision.ee.ethz.ch/cvl/food-101.tar.gz)数据集下载网址在food-101/data_dir里
- 下载下的food-101数据集先使用dataset_split.py将数据集分成train和test
- train:python food101_ResNet50.py -m train; 训练好的模型保存在saved_models_food101文件夹下
- test: python food101_ResNet50.py -m test -p loss最低的模型地址 -i 预测图片地址
- [[food101.ipynb]](https://github.com/QiujieDong/food-101/blob/master/food101.ipynb)中我完善了整个项目过程，并进行了模型可视化。
