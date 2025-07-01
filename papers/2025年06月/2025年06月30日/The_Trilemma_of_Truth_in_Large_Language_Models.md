# 大型语言模型面临的真相三重挑战

发布时间：2025年06月30日

`LLM理论` `人工智能`

> The Trilemma of Truth in Large Language Models

# 摘要

> 我们常常将人类特性归因于大型语言模型 (LLMs)，并声称它们“知道”某些事物。LLMs 内部有一种概率性的知识，代表了训练过程中保留的信息。我们如何评估这种知识的真实性？我们研究了两种常用的探查 LLMs 真实性的方法，并发现了几个存在缺陷的假设。为了克服这些缺陷，我们引入了 sAwMIL（Sparse Aware Multiple-Instance Learning 的缩写），这是一种利用 LLMs 内部激活来将陈述分为真实、虚假和非真非假三类的探查方法。sAwMIL 基于多实例学习和符合性预测。我们在 16 个开源 LLMs 上对 sAwMIL 进行了评估，涵盖了默认版本和基于对话的变体，并在 3 个新数据集上进行了测试，评估标准包括 5 个有效性指标。我们发现的几个关键点包括：(1) 真实性信号通常集中在 LLM 深度的第三部分；(2) 真实与虚假信号并非总是对称的；(3) 线性探查器在对话模型上的表现优于默认模型；(4) 对于某些基于人类反馈的强化学习或知识蒸馏的 LLMs，可能需要非线性探查器来捕捉真实性信号；(5) LLMs 捕捉到了第三种信号，这种信号不同于真与假，既非真亦非假。这些发现为验证 LLMs“知道”的内容及其对内部概率知识的确定性提供了一种可靠的方法。
    

> We often attribute human characteristics to large language models (LLMs) and claim that they "know" certain things. LLMs have an internal probabilistic knowledge that represents information retained during training. How can we assess the veracity of this knowledge? We examine two common methods for probing the veracity of LLMs and discover several assumptions that are flawed. To address these flawed assumptions, we introduce sAwMIL (short for Sparse Aware Multiple-Instance Learning), a probing method that utilizes the internal activations of LLMs to separate statements into true, false, and neither. sAwMIL is based on multiple-instance learning and conformal prediction. We evaluate sAwMIL on 5 validity criteria across 16 open-source LLMs, including both default and chat-based variants, as well as on 3 new datasets. Among the insights we provide are: (1) the veracity signal is often concentrated in the third quarter of an LLM's depth; (2) truth and falsehood signals are not always symmetric; (3) linear probes perform better on chat models than on default models; (4) nonlinear probes may be required to capture veracity signals for some LLMs with reinforcement learning from human feedback or knowledge distillation; and (5) LLMs capture a third type of signal that is distinct from true and false and is neither true nor false. These findings provide a reliable method for verifying what LLMs "know" and how certain they are of their probabilistic internal knowledge.

[Arxiv](https://arxiv.org/abs/2506.23921)