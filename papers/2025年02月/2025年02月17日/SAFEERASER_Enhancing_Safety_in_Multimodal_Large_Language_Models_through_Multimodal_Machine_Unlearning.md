# SAFEERASER：通过多模态机器卸学习提升多模态大语言模型的安全性

发布时间：2025年02月17日

`LLM应用

摘要主要探讨了多模态大语言模型（MLLMs）的安全性和隐私保护问题，特别是在机器遗忘（MU）策略的应用和评估方面。研究提出了一种新的基准SAFEERASER，并引入了提示解耦损失和新的度量指标，以解决模型在遗忘过程中出现的问题。这些内容属于LLM在安全和隐私方面的具体应用和改进，因此归类为LLM应用。` `隐私保护` `人工智能`

> SAFEERASER: Enhancing Safety in Multimodal Large Language Models through Multimodal Machine Unlearning

# 摘要

> 多模态大语言模型（MLLMs）的发展带来了日益凸显的安全隐患。机器遗忘（MU）作为一种有效的训练数据特定知识遗忘策略，在隐私保护领域得到了广泛应用。然而，针对MLLM安全性的机器遗忘研究尚未得到充分探索。为解决这一问题，我们提出了SAFEERASER——一个多模态大语言模型的安全遗忘基准，包含3,000张图像和28.8万个视觉问答（VQA）对。我们从遗忘质量和模型效用两个角度全面评估遗忘方法。研究发现，现有MU方法在实现遗忘操作时往往难以保持模型性能，且常出现过度遗忘问题。因此，我们引入了提示解耦（PD）损失，通过在遗忘过程中解耦提示来缓解过度遗忘。为了定量衡量PD损失对过度遗忘的缓解效果，我们提出了一种新的度量指标——安全答案拒绝率（SARR）。实验结果表明，将PD损失与现有遗忘方法相结合，能够有效防止过度遗忘，使LLaVA-7B和LLaVA-13B模型的SARR指标分别降低79.5%，同时保持遗忘质量和模型效用。我们的代码和数据集将在论文被接收后发布。警告：本论文包含有害语言和图像示例，建议读者自行斟酌。

> As Multimodal Large Language Models (MLLMs) develop, their potential security issues have become increasingly prominent. Machine Unlearning (MU), as an effective strategy for forgetting specific knowledge in training data, has been widely used in privacy protection. However, MU for safety in MLLM has yet to be fully explored. To address this issue, we propose SAFEERASER, a safety unlearning benchmark for MLLMs, consisting of 3,000 images and 28.8K VQA pairs. We comprehensively evaluate unlearning methods from two perspectives: forget quality and model utility. Our findings show that existing MU methods struggle to maintain model performance while implementing the forget operation and often suffer from over-forgetting. Hence, we introduce Prompt Decouple (PD) Loss to alleviate over-forgetting through decouple prompt during unlearning process. To quantitatively measure over-forgetting mitigated by PD Loss, we propose a new metric called Safe Answer Refusal Rate (SARR). Experimental results demonstrate that combining PD Loss with existing unlearning methods can effectively prevent over-forgetting and achieve a decrease of 79.5% in the SARR metric of LLaVA-7B and LLaVA-13B, while maintaining forget quality and model utility. Our code and dataset will be released upon acceptance. Warning: This paper contains examples of harmful language and images, and reader discretion is recommended.

[Arxiv](https://arxiv.org/abs/2502.12520)