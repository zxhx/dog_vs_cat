# Dogs VS Cats

## README
* public score: 0.03644

* 云平台配置：AWS，实例配置：

  - 12 core CPUs

  - 60G RAM

  - 75G SSD Hard Disk

  - GPU：Tesla V100

    

* 操作系统：

  - ID: ubuntu

  - version: 16.04.4 LTS

    

* 软件开发环境：

  - Python 3.6.4 

  - h5py 2.7.1 

  - ipykernel 4.8.2 

  - ipython 6.4.0 

  - ipython-genutils 0.2.0 

  - ipywidgets 7.2.1 

  - jupyter 1.0.0 

  - jupyter-client 5.2.3 

  - jupyter-console 5.2.0 

  - jupyter-core 4.4.0 

  - kaggle 1.3.6 

  - Keras 2.1.6 

  - Markdown 2.6.11 

  - matplotlib 2.2.2 

  - notebook 5.4.1 

  - numpy 1.14.3 

  - opencv-python 3.4.0.12 

  - pandas 0.22.0 

  - pip 10.0.1 

  - scikit-image 0.13.1 

  - scikit-learn 0.19.1 

  - scipy 1.1.0 

  - sklearn 0.0 

  - tensorboard 1.8.0 

  - tensorflow-gpu 1.8.0
* 模型准备和搭建、运行时间分两部分：
  - 异常图片清洗：使用了三个预训练模型：Xception：5min, DenseNet201:14min, InceptionResNetV2:15min，小计：34min
  - 模型训练和生成预测结果：Xception:147s, InceptionResNetV2:215s, DenseNet201:177s, train:4min, 小计：12min
  - 以上总计时间：46min
  - 训练时间：train很快，总的时间大约4min
    
