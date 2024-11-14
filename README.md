# NLP_-0-1-miniGPT

深度学习与实践课程文件

# 踩坑记录

### 1、安装版本torchtext后一直出现OSError，应该是torch和torchtext版本不匹配出现的问题，尝试了很多方法才正确安装。

正确安装方法：

首先在torch官网上找到适合自己环境的torch安装命令，建议使用conda而不是pip。

![1731564044962](images/README/1731564044962.png)

直接使用Run this Command安装torch

```
conda install pytorch torchvision torchaudio cpuonly -c pytorch
```

然后使用一下命令安装torchtext

```
conda install -c pytorch torchtext
```

就成功了。

最终安装的版本是：

pytorch                   2.5.1

torchtext                 0.6.0

### 2
