# EE369-project

本项目为EE369机器学习课程大作业，即3D肺部结节图像分类问题

dataset：包含了测试样本文件夹test（共117个npz文件）以及sampleSubmission.csv

densenet.ipynb：为整套训练测试代码，需要在google colab上运行

model.pth：为获得最终结果0.71612的模型权重文件

test.ipynb:为测试代码，需要与dataset、model.pth放至同一目录下后运行，运行后将生成test_submit.csv文件

test_submit.csv：为运行test.ipynb后的结果
