# 追踪预训练过程中多语言事实知识的获取路径

发布时间：2025年05月20日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）在预训练过程中如何回忆多语言的事实知识，并分析了这一过程的机制，包括频率驱动的学习和跨语言迁移。研究深入探讨了模型内部的学习过程和跨语言能力的发展，属于对模型理论的分析，因此归类为LLM理论。` `多语言处理`

> Tracing Multilingual Factual Knowledge Acquisition in Pretraining

# 摘要

> 大型语言模型（LLMs）能够回忆其预训练数据中包含的多语言事实知识。然而，大多数研究仅关注最终模型的表现，而忽视了预训练过程中事实回忆能力和跨语言一致性的发展。本研究以OLMo-7B为例，深入追踪了预训练过程中事实回忆和跨语言一致性的演变。我们发现，大多数语言的事实回忆准确性和跨语言一致性随着时间的推移而逐步提升。这种提升主要由预训练语料库中事实的频率驱动：更频繁出现的事实更有可能被正确回忆，无论语言如何。然而，某些非英语的低频事实仍能被正确回忆。我们的分析揭示，这些实例主要得益于其英语对应项的跨语言迁移——这一效应主要在预训练的早期阶段显现。我们指出，多语言事实知识的获取通过两条不同的路径实现：（1）频率驱动的学习，这是主要的、语言无关的路径；（2）跨语言迁移，这种迁移在规模上有限，通常局限于涉及命名实体的关系类型。我们发布了我们的代码和数据，以促进进一步研究：https://github.com/cisnlp/multilingual-fact-tracing。


> Large Language Models (LLMs) are capable of recalling multilingual factual knowledge present in their pretraining data. However, most studies evaluate only the final model, leaving the development of factual recall and crosslingual consistency throughout pretraining largely unexplored. In this work, we trace how factual recall and crosslingual consistency evolve during pretraining, focusing on OLMo-7B as a case study. We find that both accuracy and consistency improve over time for most languages. We show that this improvement is primarily driven by the fact frequency in the pretraining corpus: more frequent facts are more likely to be recalled correctly, regardless of language. Yet, some low-frequency facts in non-English languages can still be correctly recalled. Our analysis reveals that these instances largely benefit from crosslingual transfer of their English counterparts -- an effect that emerges predominantly in the early stages of pretraining. We pinpoint two distinct pathways through which multilingual factual knowledge acquisition occurs: (1) frequency-driven learning, which is dominant and language-agnostic, and (2) crosslingual transfer, which is limited in scale and typically constrained to relation types involving named entities. We release our code and data to facilitate further research at https://github.com/cisnlp/multilingual-fact-tracing.

[Arxiv](https://arxiv.org/abs/2505.14824)