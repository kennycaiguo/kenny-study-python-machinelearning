# kenny-study-python-machinelearning
# 我的sklearn代码仓库: https://github.com/kennycaiguo/kenny-sklearn-lessons
# 关于Python3.10 安装Matplotlib的问题
## 1.python3.10需要安装3.5.3版本的matplotlib,安装低于这个版本的会报错
C:\Users\Administrator>pip install matplotlib==3.5.3
Collecting matplotlib==3.5.3
  Downloading matplotlib-3.5.3-cp310-cp310-win_amd64.whl.metadata (6.7 kB)
Requirement already satisfied: cycler>=0.10 in d:\programs\python310\lib\site-packages (from matplotlib==3.5.3) (0.12.1)
Requirement already satisfied: fonttools>=4.22.0 in d:\programs\python310\lib\site-packages (from matplotlib==3.5.3) (4.53.1)
Requirement already satisfied: kiwisolver>=1.0.1 in d:\programs\python310\lib\site-packages (from matplotlib==3.5.3) (1.4.5)
Requirement already satisfied: numpy>=1.17 in d:\programs\python310\lib\site-packages (from matplotlib==3.5.3) (2.0.1)
Requirement already satisfied: packaging>=20.0 in d:\programs\python310\lib\site-packages (from matplotlib==3.5.3) (24.1)
Requirement already satisfied: pillow>=6.2.0 in d:\programs\python310\lib\site-packages (from matplotlib==3.5.3) (10.4.0)
Requirement already satisfied: pyparsing>=2.2.1 in d:\programs\python310\lib\site-packages (from matplotlib==3.5.3) (3.1.2)
Requirement already satisfied: python-dateutil>=2.7 in d:\programs\python310\lib\site-packages (from matplotlib==3.5.3) (2.9.0.post0)
Requirement already satisfied: six>=1.5 in d:\programs\python310\lib\site-packages (from python-dateutil>=2.7->matplotlib==3.5.3) (1.16.0)
Downloading matplotlib-3.5.3-cp310-cp310-win_amd64.whl (7.2 MB)
   ---------------------------------------- 7.2/7.2 MB 9.2 MB/s eta 0:00:00
Installing collected packages: matplotlib
Successfully installed matplotlib-3.5.3

## 2.MatPlotlib不支持numpy2.x,如果安装了,需要删除然后安装numpy1.x,这里需要安装numpy1.26.4版本,低于这个版本会报错
C:\Users\Administrator>pip install numpy==1.26.4
Collecting numpy==1.26.4
  Downloading numpy-1.26.4-cp310-cp310-win_amd64.whl.metadata (61 kB)
Downloading numpy-1.26.4-cp310-cp310-win_amd64.whl (15.8 MB)
   ---------------------------------------- 15.8/15.8 MB 5.3 MB/s eta 0:00:00
Installing collected packages: numpy
Successfully installed numpy-1.26.4
这两点需要注意,否则可能会出现安装了matplotlib但是导入会出错的问题

# 机器学习数据集网址
## 1.Kaggle数据集网站: https://www.kaggle.com/datasets 
## 2.UCI数据集网站: http://archive.ics.uci.edu/ 
## 3.scikit learn网站提供的数据集: https://scikit-learn.org/1.5/datasets/toy_dataset.html 
## 4.16个scikit learn有用数据集模型: https://hackernoon.com/16-best-sklearn-datasets-for-building-machine-learning-models 
## 5.scikit learn 数据集GitHub仓库: https://github.com/scikit-learn/scikit-learn/tree/main/sklearn/datasets/data

# 学习python机器学习，以下是以下有用的仓库

# <a href="https://github.com/kennycaiguo/handson-ml">handson-ml</a>
# <a href="https://github.com/kennycaiguo/machine-learning">machine-learning</a>
# <a href="https://github.com/kennycaiguo/Python-Machine-Learning-Cookbook">Python-Machine-Learning-Cookbook</a>
# <a href="https://github.com/kennycaiguo/machine-learning-yearning-cn">machine-learning-yearning-cn</a>
# <a href="https://github.com/facebookresearch/fastText">基于FastText的一款名为Muse的多语种无监督或有监督的词嵌入项目.</a>
# <a href="https://github.com/luanfujun/deep-photo-styletransfer">深度照片风格转换</a>
# <a href="https://github.com/ageitgey/face_recognition">全世界最简单的面部识别API，基于Python与命令行</a>
# <a href="https://github.com/tensorflow/tfjs-core">用于网络的硬件加速机器智能库</a>
# <a href="https://github.com/deepmind/pysc2">星际争霸II学习环境</a>
# <a href="https://github.com/wushiwang/ML">机器学习练手项目</a>
# <a href="https://github.com/fengdu78/Coursera-ML-AndrewNg-Notes">吴恩达老师的机器学习课程个人笔记</a>
# <a href="https://github.com/fengdu78/deeplearning_ai_books">deeplearning.ai（吴恩达老师的深度学习课程笔记及资源）</a>
# <a href="https://github.com/htylab/machine-learning-python">機器學習: Python</a>
# <a href="https://github.com/basicv8vc/Python-Machine-Learning-zh">Python机器学习，机器学习入门首选-jupyter notebook版本</a>
# <a href="https://github.com/rasbt/python-machine-learning-book-3rd-edition">The "Python Machine Learning (3rd edition)" book code repository</a>
# <a href="https://github.com/ZiruZha/Machine-Learning">黑马程序员3天快速入门python机器学习</a>
# <a href="https://github.com/datawhalechina/machine-learning-toy-code">《机器学习》（西瓜书）代码实战</a>
# <a href="https://github.com/LeBron-Jian/MachineLearningNote">Python机器学习笔记：sklearn库的学习</a>
# <a href=""></a>
# <a href=""></a>
# <a href=""></a>
# <a href=""></a>
# <a href=""></a>
# <a href=""></a>
# <a href=""></a>
