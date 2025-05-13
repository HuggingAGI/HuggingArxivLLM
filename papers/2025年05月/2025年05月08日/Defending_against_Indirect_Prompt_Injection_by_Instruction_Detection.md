# 指令检测防御间接提示注入攻击

发布时间：2025年05月08日

`RAG` `网络安全`

> Defending against Indirect Prompt Injection by Instruction Detection

# 摘要

> 将大型语言模型（LLMs）与外部数据源集成已成趋势，检索增强生成（RAG）便是其中典范。然而，这种集成也带来了间接提示注入（IPI）攻击的风险，外部数据中的隐藏指令可能诱导LLMs执行非预期甚至有害操作。IPI攻击的成功关键在于外部内容中嵌入的指令会改变LLMs的行为状态。能否通过检测这些状态变化来防御IPI攻击？本文提出了一种新方法，该方法将外部数据作为输入，并通过分析LLMs在正向和反向传播过程中的行为状态来检测潜在攻击。具体而言，我们发现中间层的隐藏状态和梯度提供了极具区分度的指令检测特征。通过有效整合这些特征，我们的方法在内部数据集上实现了99.60%的检测准确率，在外部数据集上达到96.90%的准确率，同时将BIPIA基准上的攻击成功率降至0.12%。

> The integration of Large Language Models (LLMs) with external sources is becoming increasingly common, with Retrieval-Augmented Generation (RAG) being a prominent example. However, this integration introduces vulnerabilities of Indirect Prompt Injection (IPI) attacks, where hidden instructions embedded in external data can manipulate LLMs into executing unintended or harmful actions. We recognize that the success of IPI attacks fundamentally relies in the presence of instructions embedded within external content, which can alter the behavioral state of LLMs. Can effectively detecting such state changes help us defend against IPI attacks? In this paper, we propose a novel approach that takes external data as input and leverages the behavioral state of LLMs during both forward and backward propagation to detect potential IPI attacks. Specifically, we demonstrate that the hidden states and gradients from intermediate layers provide highly discriminative features for instruction detection. By effectively combining these features, our approach achieves a detection accuracy of 99.60\% in the in-domain setting and 96.90\% in the out-of-domain setting, while reducing the attack success rate to just 0.12\% on the BIPIA benchmark.

[Arxiv](https://arxiv.org/abs/2505.06311)