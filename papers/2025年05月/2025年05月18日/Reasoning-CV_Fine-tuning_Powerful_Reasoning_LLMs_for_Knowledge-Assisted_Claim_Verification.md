# Reasoning-CV: 微调强大推理型大语言模型，助力知识辅助声明验证

发布时间：2025年05月18日

`LLM应用

这篇论文探讨了大型语言模型在声明验证中的应用，提出了一种新的方法来改进其验证能力，属于LLM的应用研究。` `信息真实性评估` `声明验证`

> Reasoning-CV: Fine-tuning Powerful Reasoning LLMs for Knowledge-Assisted Claim Verification

# 摘要

> 声明验证在对抗错误信息中至关重要，大型语言模型（LLMs）近期在此领域崭露头角，成为评估声明真实性的强大工具，通过外部知识来判断声明的真伪。现有的基于LLM的声明验证方法通常采用“分解-验证”范式，即将复杂声明分解为多个独立子声明，然后分别验证每个子声明。然而，这种范式在声明分解过程中常常引入错误。为了解决这些问题，我们提出了一种名为Chain-of-Thought (CoT)-Verify的新范式，该范式利用LLM的推理方法为原始复杂声明生成CoT-验证路径，无需分解为子声明和单独的验证阶段。CoT-Verify范式使我们能够提出一种名为Reasoning-CV的自然微调方法，以增强LLMs的验证能力。Reasoning-CV包括监督微调（SFT）阶段和自我改进的直接偏好优化（DPO）阶段。仅使用一个8B的预训练LLM，Reasoning-CV在知识辅助声明验证性能上优于现有的“分解-验证”方法，以及强大的黑箱LLMs，如GPT-4o+CoT和o1-preview。我们的代码已开源。


> Claim verification is essential in combating misinformation, and large language models (LLMs) have recently emerged in this area as powerful tools for assessing the veracity of claims using external knowledge. Existing LLM-based methods for claim verification typically adopt a Decompose-Then-Verify paradigm, which involves decomposing complex claims into several independent sub-claims and verifying each sub-claim separately. However, this paradigm often introduces errors during the claim decomposition process. To mitigate these errors, we propose to develop the Chain-of-Thought (CoT)-Verify paradigm, which leverages LLM reasoning methods to generate CoT-verification paths for the original complex claim without requiring decompositions into sub-claims and separate verification stages. The CoT-Verify paradigm allows us to propose a natural fine-tuning method called Reasoning-CV to enhance the verification capabilities in LLMs. Reasoning-CV includes a supervised fine-tuning (SFT) stage and a self-improvement direct preference optimization (DPO) stage. Utilizing only an 8B pre-trained LLM, Reasoning-CV demonstrates superior knowledge-assisted claim verification performances compared to existing Decompose-Then-Verify methods, as well as powerful black-box LLMs such as GPT-4o+CoT and o1-preview. Our code is available.

[Arxiv](https://arxiv.org/abs/2505.12348)