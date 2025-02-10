# 信心提取：针对大型语言模型的新型攻击手段

发布时间：2025年02月06日

`LLM理论` `信息安全` `人工智能`

> Confidence Elicitation: A New Attack Vector for Large Language Models

# 摘要

> 深度学习中的对抗鲁棒性是一个基本问题。随着模型规模的扩大，这一问题依然存在。当前，拥有数十亿参数的大型语言模型（LLMs）与早期较小规模的模型一样，都面临着对抗攻击的威胁。然而，威胁模型已经发生了变化。过去，用户可能可以访问输入嵌入或输出 logits/概率（灰盒访问权限）。然而，随着闭源模型的出现，用户无法获取任何关于模型的信息，除了生成的输出。这意味着当前的黑盒攻击只能利用最终预测结果来判断攻击是否成功。在本研究中，我们探讨并演示了在分类场景下，仅凭黑盒访问权限，类似于利用输出概率进行攻击的潜在可能性。我们通过模型能够表达置信度的能力实现了这一点。我们实证表明，当前 LLMs 的表达置信度是经过校准的，而非凭空捏造。因此，通过最小化表达的置信度，我们可以增加分类错误的可能性。我们的新提出的范式在三个数据集上，针对两个模型（LLaMA-3-8B-Instruct 和 Mistral-7B-Instruct-V0.3），与现有的基于硬标签的黑盒攻击方法（引入词级别替换）相比，展示了有前途的最新技术水平。

> A fundamental issue in deep learning has been adversarial robustness. As these systems have scaled, such issues have persisted. Currently, large language models (LLMs) with billions of parameters suffer from adversarial attacks just like their earlier, smaller counterparts. However, the threat models have changed. Previously, having gray-box access, where input embeddings or output logits/probabilities were visible to the user, might have been reasonable. However, with the introduction of closed-source models, no information about the model is available apart from the generated output. This means that current black-box attacks can only utilize the final prediction to detect if an attack is successful. In this work, we investigate and demonstrate the potential of attack guidance, akin to using output probabilities, while having only black-box access in a classification setting. This is achieved through the ability to elicit confidence from the model. We empirically show that the elicited confidence is calibrated and not hallucinated for current LLMs. By minimizing the elicited confidence, we can therefore increase the likelihood of misclassification. Our new proposed paradigm demonstrates promising state-of-the-art results on three datasets across two models (LLaMA-3-8B-Instruct and Mistral-7B-Instruct-V0.3) when comparing our technique to existing hard-label black-box attack methods that introduce word-level substitutions.

[Arxiv](https://arxiv.org/abs/2502.04643)