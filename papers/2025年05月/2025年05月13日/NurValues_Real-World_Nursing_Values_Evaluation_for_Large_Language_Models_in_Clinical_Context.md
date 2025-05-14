# NurValues：在临床场景中评估大型语言模型的护理真实价值

发布时间：2025年05月13日

`LLM应用` `人工智能伦理`

> NurValues: Real-World Nursing Values Evaluation for Large Language Models in Clinical Context

# 摘要

> 本研究推出了首个护理价值对齐基准，该基准基于国际护理准则，提炼出五大核心价值维度：利他主义、人的尊严、正直、公正与职业精神。我们通过为期五个月的跨三家不同等级医院的实地研究，收集了1,100个真实世界护理行为实例。这些实例由五名临床护士标注，并通过LLM生成的具有相反伦理倾向的反事实案例进行增强。每个原始案例都配有一个符合价值导向和一个违背价值导向的版本，最终生成了2,200个标注实例，构成Easy-Level数据集。为了提升对抗复杂性，我们还将每个实例转化为嵌入情境线索和微妙误导信号的对话格式，从而形成了Hard-Level数据集。我们评估了23个最先进的（SoTA）LLMs在护理价值对齐方面的表现。研究发现显示三个关键结论：（1）DeepSeek-V3在Easy-Level数据集上表现最佳（94.55分），而Claude 3.5 Sonnet在Hard-Level数据集上超越了其他模型（89.43分），远超医疗LLMs；（2）公正始终是最难评估的护理价值维度；（3）上下文学习显著提升了对齐效果。本研究旨在为临床环境中开发价值敏感型LLMs奠定基础。数据集和代码可在https://huggingface.co/datasets/Ben012345/NurValues获取。

> This work introduces the first benchmark for nursing value alignment, consisting of five core value dimensions distilled from international nursing codes: Altruism, Human Dignity, Integrity, Justice, and Professionalism. The benchmark comprises 1,100 real-world nursing behavior instances collected through a five-month longitudinal field study across three hospitals of varying tiers. These instances are annotated by five clinical nurses and then augmented with LLM-generated counterfactuals with reversed ethic polarity. Each original case is paired with a value-aligned and a value-violating version, resulting in 2,200 labeled instances that constitute the Easy-Level dataset. To increase adversarial complexity, each instance is further transformed into a dialogue-based format that embeds contextual cues and subtle misleading signals, yielding a Hard-Level dataset. We evaluate 23 state-of-the-art (SoTA) LLMs on their alignment with nursing values. Our findings reveal three key insights: (1) DeepSeek-V3 achieves the highest performance on the Easy-Level dataset (94.55), where Claude 3.5 Sonnet outperforms other models on the Hard-Level dataset (89.43), significantly surpassing the medical LLMs; (2) Justice is consistently the most difficult nursing value dimension to evaluate; and (3) in-context learning significantly improves alignment. This work aims to provide a foundation for value-sensitive LLMs development in clinical settings. The dataset and the code are available at https://huggingface.co/datasets/Ben012345/NurValues.

[Arxiv](https://arxiv.org/abs/2505.08734)