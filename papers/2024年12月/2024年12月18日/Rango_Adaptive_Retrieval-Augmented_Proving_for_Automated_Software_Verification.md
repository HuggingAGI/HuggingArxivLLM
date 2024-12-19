# Rango：用于自动化软件验证的自适应检索增强式证明

发布时间：2024年12月18日

`LLM应用` `形式验证`

> Rango: Adaptive Retrieval-Augmented Proving for Automated Software Verification

# 摘要

> 使用像 Coq 这样的证明助手进行形式验证，可以打造出高质量的软件。不过，验证过程需要深厚的专业知识以及大量手动编写证明的功夫。近期的工作探索借助机器学习和大型语言模型（LLMs）来实现证明合成的自动化。此工作显示，识别相关前提，比如引理和定义，有助于合成。我们推出了 Rango，这是一个针对 Coq 的全自动证明合成工具，它能够自动识别相关前提，还能从当前项目中找出类似证明，并在合成时加以运用。Rango 在证明的每一步都运用检索增强，自动确定在其微调的 LLM 上下文中纳入哪些证明和前提。如此一来，Rango 能够适应项目以及证明不断变化的状态。我们创建了一个新的数据集 CoqStoq，涵盖了来自 GitHub 的 2226 个开源 Coq 项目和 196929 个定理，其中既有训练数据，也有精心筛选的评估基准，包含维护良好的项目。在这个基准上，Rango 为 32.0%的定理合成了证明，比之前最先进的工具 Tactician 多 29%的定理。我们的评估还表明，Rango 在其上下文中添加相关证明，使得已证明定理的数量增加了 47%。

> Formal verification using proof assistants, such as Coq, enables the creation of high-quality software. However, the verification process requires significant expertise and manual effort to write proofs. Recent work has explored automating proof synthesis using machine learning and large language models (LLMs). This work has shown that identifying relevant premises, such as lemmas and definitions, can aid synthesis. We present Rango, a fully automated proof synthesis tool for Coq that automatically identifies relevant premises and also similar proofs from the current project and uses them during synthesis. Rango uses retrieval augmentation at every step of the proof to automatically determine which proofs and premises to include in the context of its fine-tuned LLM. In this way, Rango adapts to the project and to the evolving state of the proof. We create a new dataset, CoqStoq, of 2,226 open-source Coq projects and 196,929 theorems from GitHub, which includes both training data and a curated evaluation benchmark of well-maintained projects. On this benchmark, Rango synthesizes proofs for 32.0% of the theorems, which is 29% more theorems than the prior state-of-the-art tool Tactician. Our evaluation also shows that Rango adding relevant proofs to its context leads to a 47% increase in the number of theorems proven.

[Arxiv](https://arxiv.org/abs/2412.14063)