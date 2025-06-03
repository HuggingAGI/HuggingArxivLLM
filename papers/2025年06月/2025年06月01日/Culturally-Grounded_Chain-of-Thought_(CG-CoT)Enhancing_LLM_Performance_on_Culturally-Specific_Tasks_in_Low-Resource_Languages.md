# 文化根基的思维链方法（CG-CoT）：优化大语言模型在低资源语言文化特定任务中的性能

发布时间：2025年06月01日

`LLM应用` `人工智能`

> Culturally-Grounded Chain-of-Thought (CG-CoT):Enhancing LLM Performance on Culturally-Specific Tasks in Low-Resource Languages

# 摘要

> 大型语言模型 (LLMs) 在文化特定推理任务，尤其是低资源语言方面表现不佳，这限制了它们的全球适用性。解决这一差距对于实现公平的人工智能部署至关重要。我们提出了一种新型提示策略——文化根基链式思维 (CG-CoT)，该策略结合了文化背景的密集向量检索与明确的推理序列。我们在约鲁巴谚语解析上的广泛实验表明，与传统提示方法相比，CG-CoT 提供了显著更高程度的文化对齐准确性和深度，这一结论通过自动度量和基于 LLM 的评估得到了验证。值得注意的是，我们发现像 BLEU 这样的词级别翻译指标与人工评判的文化相关性之间存在显著差异，这表明需要重新考虑低资源 NLP 的评估方法。

> Large Language Models (LLMs) struggle with culturally-specific reasoning tasks, particularly in low-resource languages, hindering their global applicability. Addressing this gap is crucial for equitable AI deployment. We introduce Culturally-Grounded Chain-of-Thought (CG-CoT), a novel prompting strategy that combines dense vector retrieval of cultural context with explicit reasoning sequences. Our extensive experiments on Yoruba proverb interpretation demonstrate that CG-CoT provides significantly higher culturally-aligned accuracy and depth than traditional prompting methods, validated through both automated metrics and LLM-based evaluations. Notably, we uncover stark disparities between token-level translation metrics like BLEU and human-judged cultural relevance, suggesting a rethinking of evaluation approaches for low-resource NLP.

[Arxiv](https://arxiv.org/abs/2506.01190)