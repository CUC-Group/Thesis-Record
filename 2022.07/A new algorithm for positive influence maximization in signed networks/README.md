# A new algorithm for positive influence maximization in signed networks

## 文献信息

### 题目：

***符号网络中正影响最大化的新算法***

### 	发布时间： 

2019

### 作者姓名：

Weijia Ju, Ling Chen2, Bin Li, Wei Liu, Jun Sheng, Yuwei Wang

### **作者信息：**

扬州大学信息工程学院；南京大学新型软件技术国家重点实验室

## 期刊信息

期刊名：*《**Information Sciences**》*

中科院SCI:  

![sci分区](sci.png)



## 摘要

&emsp; &emsp; 随着在线社交网络的快速发展，影响力最大化问题受到了研究者的广泛关注，并被应用到营销、金融等多个领域。由于社会网络中个体之间可能存在正负关系，因此符号网络中的影响力最大化问题有着广泛的应用。文章提出了在独立级联模型下符号网络中积极影响力最大化的一种有效算法。首先，我们提出了一个独立的基于路径的算法来计算节点对之间的激活概率。在激活概率的基础上，我们定义了一个扩展函数，以避免模拟种子节点选择的影响扩散。我们提出了一种选择种子节点的算法，以使得选定的中子节点在有符号网络中能将积极影响扩散最大化。在社交网络中的实证结果表明，我们的算法比其他方法具有更广泛的正向传播影响。

## 内容总结

1. 正式定义了**IC模型下签名网络中的正影响最大化问题**。还提出了一套传播规则来模拟竞争影响力的传播。
2. 提出一种算法，使用**独立路径**计算每个节点对之间的正激活概率。
3. 为了避免模拟影响传播的耗时过程，定义了一个**传播函数**来估计种子集的影响范围。
4. 提出了一种称为**PIM-SN**的算法，用于使用传播函数检测最佳种子集。