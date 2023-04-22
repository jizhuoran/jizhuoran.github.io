---
layout: archive
title: "本手册旨在帮助读者学习GPU编程"
permalink: /intro2GPU/
author_profile: true
---


在开始之前，你需要一个有Nvidia GPU的电脑，不动手实践而学会编程是不可能的。最好是ubuntu系统，当然Windows系统应该也可以。Nvidia编程环境的搭建需要艰苦卓绝的努力，希望你能迈过第一块绊脚石（Nvidia编程环境比AMD的好搭多了，LOL）。

---

首先，你可以参照入门书《CUDA by example》（或其中文版本《GPU高性能编程CUDA实战》），这本书是由两位Nvidia的资深软件工程师Jason Sanders和Edward Kandrot编写。十分建议在电脑上完成里面的操作题目


几个不错的基础练习题：
* 向量加法
* 向量点乘
* 分块矩阵乘法 (Kernel 1-3) (https://cnugteren.github.io/tutorial/pages/page1.html)
  
**至此，你已经能进行基本的GPU编程了。如果你是因为看到我们的招募广告而来，那么你已经具备足够的能力了！**

---

之后，你可以学习Nvidia官方编程指南[《CUDA C++ Programming Guide》](https://docs.nvidia.com/cuda/cuda-c-programming-guide/)（或其中文版本[《NVIDIA CUDA 编程指南》](https://www.nvidia.cn/docs/IO/51635/NVIDIA_CUDA_Programming_Guide_1.1_chs.pdf)）的**第五章**。注意到，中文版本不仅翻译腔严重，而且内容较为落后。但在此阶段，中文版本内容仍可以满足你的学习需求。

几个不错的进阶练习题：
* 矩阵转置
* 统计直方图
* 分块矩阵乘法 (Kernel 4-10) (https://cnugteren.github.io/tutorial/pages/page1.html)

**恭喜你，你已经初步入门GPU并行程序设计了。相信你能够相对独立的进行相关的开发和研究了。**

---

随后，让我们暂时远离GPU。《深入理解计算机系统》（大名鼎鼎的CSAPP）中的第五章和第六章，可以帮助你理解程序优化的基本思想。

此书附带练习题，我就不班门弄斧了

**好书！**

---

最后，你可以通读Nvidia官方编程指南[《CUDA C++ Programming Guide》](https://docs.nvidia.com/cuda/cuda-c-programming-guide/)的所有章节，并思考其设计的来龙去脉。

几个不错的资深练习题：
* Tensor Core加速的分块矩阵乘法
* KNN树索引

**你已俨然一位GPU内核程序性能调优的大师。**

---

如果你仍不满足于此，你可以利用LLVM编译器为AMD GPU编译OpenCL代码，通过钻研生成的机器码，了解一个GPU内核程序将会如何在GPU上一步步被执行。

大师级练习题：
* 向量加法 （咦？我们回到了最初的起点。但是向量加法真的没有优化空间吗？）

**如果用一句话总结GPU程序设计的本质，您的答案是什么呢？**




