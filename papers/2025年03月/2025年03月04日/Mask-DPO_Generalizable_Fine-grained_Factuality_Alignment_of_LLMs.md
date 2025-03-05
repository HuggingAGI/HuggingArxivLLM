# # 标题  
Mask-DPO: 可泛化的细粒度事实对齐方法

发布时间：2025年03月04日

`LLM应用

摘要中提到的论文提出了一种新的方法Mask-DPO，用于改进大型语言模型的事实对齐，属于应用层面的优化。因此，该论文被归类为LLM应用。` `人工智能` `机器学习`

> Mask-DPO: Generalizable Fine-grained Factuality Alignment of LLMs

# 摘要

> 大型语言模型（LLMs）在作为AI助手时，常常会出现不忠实或无意义的幻觉信息。由于这些幻觉总是与真实内容交织在一起，传统的基于响应级别的事实对齐方法在训练中难以避免噪声干扰。针对这一问题，我们提出了一种名为Mask-DPO的细粒度事实对齐方法，基于直接偏好优化（DPO）。通过将句子级别的事实性作为掩码信号，Mask-DPO能够精准地从优选样本中的事实正确句子中学习，同时避免对非优选样本中的事实内容进行惩罚，从而有效解决了传统方法中的模糊性问题。

实验结果表明，Mask-DPO显著提升了LLMs对各类问题的事实性表现，即使这些问题及其主题在训练过程中从未出现过。仅使用ANAH训练集进行训练，Llama3.1-8B-Instruct在ANAH测试集上的得分从49.19%跃升至77.53%，甚至超越了Llama3.1-70B-Instruct（53.44%）的表现。同时，在 Biography 外部数据集上，其FactScore也从30.29%提升至39.39%。通过不同训练样本扩展策略的研究，我们发现增加数据集中的主题数量比增加问题数量更能提升模型性能。

我们对事实对齐在LLMs中的作用提出了假设，并通过概念验证实验进行了验证。希望这一方法和发现能为未来在事实对齐扩展领域的研究提供重要参考。

> Large language models (LLMs) exhibit hallucinations (i.e., unfaithful or nonsensical information) when serving as AI assistants in various domains. Since hallucinations always come with truthful content in the LLM responses, previous factuality alignment methods that conduct response-level preference learning inevitably introduced noises during training. Therefore, this paper proposes a fine-grained factuality alignment method based on Direct Preference Optimization (DPO), called Mask-DPO. Incorporating sentence-level factuality as mask signals, Mask-DPO only learns from factually correct sentences in the preferred samples and prevents the penalty on factual contents in the not preferred samples, which resolves the ambiguity in the preference learning. Extensive experimental results demonstrate that Mask-DPO can significantly improve the factuality of LLMs responses to questions from both in-domain and out-of-domain datasets, although these questions and their corresponding topics are unseen during training. Only trained on the ANAH train set, the score of Llama3.1-8B-Instruct on the ANAH test set is improved from 49.19% to 77.53%, even surpassing the score of Llama3.1-70B-Instruct (53.44%), while its FactScore on the out-of-domain Biography dataset is also improved from 30.29% to 39.39%. We further study the generalization property of Mask-DPO using different training sample scaling strategies and find that scaling the number of topics in the dataset is more effective than the number of questions. We provide a hypothesis of what factual alignment is doing with LLMs, on the implication of this phenomenon, and conduct proof-of-concept experiments to verify it. We hope the method and the findings pave the way for future research on scaling factuality alignment.

[Arxiv](https://arxiv.org/abs/2503.02846)