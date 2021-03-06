## sklearn 包

- 三个方法
  - 高斯朴素贝叶斯
   - 适应于 特征变量是连续变量 负荷高斯分布 例如身高
  - 多项式朴素贝叶斯
   - 适应于 特征变量是离散变量 例如单词出现的概率
  - 伯努利朴素贝叶斯
   - 适应于 特征变量是布尔变量 例如单词是否出现

## TF-IDF
- 词频
  - 单词在文档中的次数
- 逆向文档频率
  - 单词在文档中的区分度

### 计算方法

- TF

![TF](https://raw.githubusercontent.com/Syncma/Figurebed/master/img/41.jpeg)
- IDF

![IDF](https://raw.githubusercontent.com/Syncma/Figurebed/master/img/42.jpeg)


```公式
TF-IDF = TF * IDF
```

## 示例代码

[示例代码](./demo.py)

## 文档分类

![文档分类](https://raw.githubusercontent.com/Syncma/Figurebed/master/img/49.jpeg)

- 英文分类
  - `nltk`
- 中文分类
  - `jieba`
