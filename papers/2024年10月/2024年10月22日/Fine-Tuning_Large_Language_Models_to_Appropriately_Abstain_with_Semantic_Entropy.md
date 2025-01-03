# 通过语义熵微调大型语言模型，使其能够恰当地弃权

发布时间：2024年10月22日

`LLM理论

理由：这篇论文主要讨论了大型语言模型（LLMs）在生成文本时产生的“幻觉”问题，并提出了一种基于语义熵的微调方法来缓解这一问题。论文的核心在于对LLMs的理论改进和优化，特别是通过模型自省来减少幻觉现象。因此，这篇论文更适合归类为“LLM理论”。`

> Fine-Tuning Large Language Models to Appropriately Abstain with Semantic Entropy

# 摘要

> 大型语言模型（LLMs）常会产生看似合理但不准确的文本，这种现象被称为“幻觉”。在医学或法律等关键领域，幻觉带来了重大风险，因此需要有效的缓解策略。尽管已有研究提出通过微调让LLMs避免回答超出其知识范围的问题，但这些方法要么依赖真实标签，要么仅限于短文本生成。为此，我们提出了一种基于语义熵的微调方法，这种不确定性度量源自模型自省，无需外部标签。实验表明，我们的方法在多个数据集上表现优异，无论是短文本还是长文本生成，均优于现有方法。

> Large Language Models (LLMs) are known to hallucinate, whereby they generate plausible but inaccurate text. This phenomenon poses significant risks in critical applications, such as medicine or law, necessitating robust hallucination mitigation strategies. While recent works have proposed fine-tuning methods to teach LLMs to abstain from answering questions beyond their knowledge or capabilities, these methods rely on the existence of ground-truth labels or are limited to short-form responses. To address these limitations, we propose fine-tuning using semantic entropy, an uncertainty measure derived from introspection into the model which does not require external labels. We demonstrate that our approach matches or outperforms models fine-tuned using prior work and achieves strong performance for both short and long-form generations on a range of datasets.

[Arxiv](https://arxiv.org/abs/2410.17234)