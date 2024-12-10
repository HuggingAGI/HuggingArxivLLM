# 先暴露再防御：借助暴露模型统一并强化后门防御

发布时间：2024年10月25日

`其他` `网络安全` `人工智能`

> Expose Before You Defend: Unifying and Enhancing Backdoor Defenses via Exposed Models

# 摘要

> 后门攻击会通过对少量训练数据投毒，用预先设计好的后门触发器悄悄将其植入深度神经网络（DNNs）。在大模型时代，这种漏洞愈发严重，因为基于网络抓取数据集的大量（预）训练容易受到威胁。本文中，我们推出了一个新颖的两步防御框架，名为“先暴露再防御（EBYD）”。EBYD 将现有的后门防御方法整合进一个性能提升的综合防御系统。具体而言，EBYD 先是通过名为后门暴露的模型预处理步骤，在植入后门的模型中揭示后门功能，然后对暴露的模型运用检测和移除方法，来识别并清除后门特征。在后门暴露的第一步，我们提出了一种叫“清洁遗忘（CUL）”的新技术，它能主动从植入后门的模型中遗忘干净特征，从而揭示隐藏的后门特征。我们还探索了多种用于后门暴露的模型编辑/修改技术，包括微调、模型稀疏化和权重扰动。借助 EBYD，我们在 2 个视觉数据集（CIFAR-10 和 ImageNet 子集）和 4 个语言数据集（SST-2、IMDB、Twitter 和 AG 的新闻）上针对 10 种图像攻击和 6 种文本攻击开展了大量实验。结果显示出后门暴露对后门防御的重要性，表明暴露的模型能极大地助力一系列下游防御任务，包括后门标签检测、后门触发器恢复、后门模型检测和后门移除。我们期望我们的工作能激发更多关于开发带有暴露模型的先进防御框架的研究。我们的代码可在：https://github.com/bboylyg/Expose-Before-You-Defend 获取。

> Backdoor attacks covertly implant triggers into deep neural networks (DNNs) by poisoning a small portion of the training data with pre-designed backdoor triggers. This vulnerability is exacerbated in the era of large models, where extensive (pre-)training on web-crawled datasets is susceptible to compromise. In this paper, we introduce a novel two-step defense framework named Expose Before You Defend (EBYD). EBYD unifies existing backdoor defense methods into a comprehensive defense system with enhanced performance. Specifically, EBYD first exposes the backdoor functionality in the backdoored model through a model preprocessing step called backdoor exposure, and then applies detection and removal methods to the exposed model to identify and eliminate the backdoor features. In the first step of backdoor exposure, we propose a novel technique called Clean Unlearning (CUL), which proactively unlearns clean features from the backdoored model to reveal the hidden backdoor features. We also explore various model editing/modification techniques for backdoor exposure, including fine-tuning, model sparsification, and weight perturbation. Using EBYD, we conduct extensive experiments on 10 image attacks and 6 text attacks across 2 vision datasets (CIFAR-10 and an ImageNet subset) and 4 language datasets (SST-2, IMDB, Twitter, and AG's News). The results demonstrate the importance of backdoor exposure for backdoor defense, showing that the exposed models can significantly benefit a range of downstream defense tasks, including backdoor label detection, backdoor trigger recovery, backdoor model detection, and backdoor removal. We hope our work could inspire more research in developing advanced defense frameworks with exposed models. Our code is available at: https://github.com/bboylyg/Expose-Before-You-Defend.

[Arxiv](https://arxiv.org/abs/2410.19427)