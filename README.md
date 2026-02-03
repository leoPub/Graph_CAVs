# Supplementary Code for Multi-Vehicle Collaborative Decision Making

此仓库包含论文 **《[此处填写您的论文标题]》** (Chapter 2) 中关于“奖励函数梯度稀疏性验证”的仿真实验代码。

This repository contains the simulation code for validating the "reward gradient sparsity" in Chapter 2 of the paper **"[Insert Your Paper Title Here]"**.

## ⚠️ Acknowledgement & Origin (致谢与来源说明)

> **Note:** This project is a fork / based on the excellent open-source project **Graph_CAVs**.
> **说明：** 本项目基于优秀的开源项目 **Graph_CAVs** 进行二次开发与实验验证。

我们衷心感谢原作者的贡献。除了本文特有的实验代码外，核心仿真环境与基础算法架构均源自：
We sincerely appreciate the contribution of the original authors. The core simulation environment and algorithm architecture are derived from:

* **Original Repository**: [https://github.com/Jacklinkk/Graph_CAVs](https://github.com/Jacklinkk/Graph_CAVs)
* **Original Paper**: Liu, Y., et al. (2022). [Title of the original paper].
* **Modifications**:
    * Added data logging for reward first-order difference analysis.
    * Conducted experiments on reward sparsity under 10 Hz decision frequency.
