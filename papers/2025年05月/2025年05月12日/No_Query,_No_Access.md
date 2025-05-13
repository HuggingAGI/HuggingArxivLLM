# 无查询则无访问权限

发布时间：2025年05月12日

`LLM应用`

> No Query, No Access

# 摘要

> 文本对抗攻击通过微妙修改文本误导自然语言处理模型，包括大型语言模型（LLMs）。然而，现有攻击方法受限于需要了解受害者模型、大量查询或访问训练数据，难以在实际中应用。为此，我们提出	extbf{基于受害者数据的对抗攻击（VDBA）}，仅利用受害者文本即可实施攻击。

为避免直接接触受害者模型，我们基于公开预训练模型和聚类方法构建影子数据集，用于开发替代模型。针对信息反馈不足导致的低攻击成功率（ASR），我们设计了分层替代模型方案，通过多模型协作克服单一模型在决策边界上的局限。

同时，我们采用多样化的对抗样本生成策略，综合运用多种攻击方法，筛选出相似性高且攻击效果佳的样本。实验显示，VDBA在情感分析和SST5数据集上比现有方法提升了52.08\%的攻击成功率，同时将攻击查询次数大幅降低至0。更重要的是，VDBA对Qwen2和GPT系列等大型语言模型构成重大威胁，即使不依赖API访问，仍实现了45.99\%的最高攻击成功率，表明先进NLP模型仍面临严峻的安全挑战。我们的代码可在https://anonymous.4open.science/r/VDBA-Victim-Data-based-Adversarial-Attack-36EC/获取。


> Textual adversarial attacks mislead NLP models, including Large Language Models (LLMs), by subtly modifying text. While effective, existing attacks often require knowledge of the victim model, extensive queries, or access to training data, limiting real-world feasibility. To overcome these constraints, we introduce the \textbf{Victim Data-based Adversarial Attack (VDBA)}, which operates using only victim texts. To prevent access to the victim model, we create a shadow dataset with publicly available pre-trained models and clustering methods as a foundation for developing substitute models. To address the low attack success rate (ASR) due to insufficient information feedback, we propose the hierarchical substitution model design, generating substitute models to mitigate the failure of a single substitute model at the decision boundary.
  Concurrently, we use diverse adversarial example generation, employing various attack methods to generate and select the adversarial example with better similarity and attack effectiveness. Experiments on the Emotion and SST5 datasets show that VDBA outperforms state-of-the-art methods, achieving an ASR improvement of 52.08\% while significantly reducing attack queries to 0. More importantly, we discover that VDBA poses a significant threat to LLMs such as Qwen2 and the GPT family, and achieves the highest ASR of 45.99% even without access to the API, confirming that advanced NLP models still face serious security risks. Our codes can be found at https://anonymous.4open.science/r/VDBA-Victim-Data-based-Adversarial-Attack-36EC/

[Arxiv](https://arxiv.org/abs/2505.07258)