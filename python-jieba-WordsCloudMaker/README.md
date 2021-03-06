# 中文词云Maker v0.02

**基于[jieba分词](https://github.com/fxsjy/jieba)**

## 关于

- “词云”就是对网络文本中出现频率较高的“关键词”予以视觉上的突出，形成“关键词云层”或“关键词渲染”，从而过滤掉大量的文本信息，使浏览网页者只要一眼扫过文本就可以领略文本的主旨。

- 在Python编程中，我们可以使用词云的方法来提取文档中的词语，生成词云图片，实现数据可视化。

- 本设计使用Tkinter库实现可视化界面，基于jieba库实现中文的分词处理。

## 功能

1. 主要功能

    - 通过读取用户给定的**中文txt文档**的内容，对文档进行分词。

    - 再读取用户给定的**白底图片蒙版**，生成具有一定形状的词云图片。

2. 其它功能

    - 选择生成词云图片的字体

    - 调整字体的大小和随机变动值

## 展示

- 主界面

    ![main](https://github.com/JasonSun2018/img-folder/blob/master/python-jieba-WordsCloudMaker/main.png)

- 分词对比

    ![result](https://github.com/JasonSun2018/img-folder/blob/master/python-jieba-WordsCloudMaker/%E5%AF%B9%E6%AF%94.png)
