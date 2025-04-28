# 乐观、期望还是讽刺？多类希望言论检测在西班牙语和英语中的应用

发布时间：2025年04月24日

`LLM应用` `心理健康`

> Optimism, Expectation, or Sarcasm? Multi-Class Hope Speech Detection in Spanish and English

# 摘要

> 希望是一种复杂且未被充分探索的情感状态，在教育、心理健康和社会互动中发挥着重要作用。与基本情绪不同，希望以多种形式呈现，从现实乐观到过度幻想或讽刺不等，这使得自然语言处理系统难以准确检测。本研究推出PolyHope V2，一个多语言、细粒度的希望言论数据集，包含超过30,000条英语和西班牙语的标注推文。该数据集区分了四种希望子类型：普通希望、现实希望、非现实希望和讽刺希望，并通过明确标注讽刺实例对现有数据集进行了改进。我们对多个预训练的Transformer模型进行了基准测试，并将其与GPT 4和Llama 3等大语言模型（LLM）在零样本和少样本测试中进行了比较。我们的研究发现，微调的Transformer模型在零样本和少样本测试中优于基于提示的LLM，尤其在区分细微的希望类别和讽刺方面表现突出。通过定性分析和混淆矩阵，我们揭示了在区分密切相关希望子类型时系统性的挑战。该数据集和研究结果为未来需要更高语义和上下文敏感性的跨语言情绪识别任务提供了坚实的基础。

> Hope is a complex and underexplored emotional state that plays a significant role in education, mental health, and social interaction. Unlike basic emotions, hope manifests in nuanced forms ranging from grounded optimism to exaggerated wishfulness or sarcasm, making it difficult for Natural Language Processing systems to detect accurately. This study introduces PolyHope V2, a multilingual, fine-grained hope speech dataset comprising over 30,000 annotated tweets in English and Spanish. This resource distinguishes between four hope subtypes Generalized, Realistic, Unrealistic, and Sarcastic and enhances existing datasets by explicitly labeling sarcastic instances. We benchmark multiple pretrained transformer models and compare them with large language models (LLMs) such as GPT 4 and Llama 3 under zero-shot and few-shot regimes. Our findings show that fine-tuned transformers outperform prompt-based LLMs, especially in distinguishing nuanced hope categories and sarcasm. Through qualitative analysis and confusion matrices, we highlight systematic challenges in separating closely related hope subtypes. The dataset and results provide a robust foundation for future emotion recognition tasks that demand greater semantic and contextual sensitivity across languages.

[Arxiv](https://arxiv.org/abs/2504.17974)