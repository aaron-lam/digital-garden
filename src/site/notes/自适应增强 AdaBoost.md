---
{"dg-publish":true,"dg-home":false,"dg-permalink":"ada-boost","permalink":"/ada-boost/","dgPassFrontmatter":true}
---

202312312150
  
笔记状态: #随想 
标签: #AdaBoost

AdaBoost（Adaptive Boosting）是一种强大的集成学习算法，旨在通过组合多个弱学习器以构建一个强大的模型。与随机森林不同，AdaBoost的基本思想是逐步提升那些在前一轮中表现不佳的样本的权重，使得模型更加关注难以分类的样本。每个弱学习器都被赋予一个权重，而这些权重是根据前一轮学习器的性能来调整的。最终的模型是通过加权组合所有弱学习器的输出而得到的。AdaBoost在二分类和多分类问题上表现出色，尤其在处理复杂数据集和噪声数据时具有较强的鲁棒性。

---
# 参考文献

https://www.cnblogs.com/jpcflyer/p/11268859.html