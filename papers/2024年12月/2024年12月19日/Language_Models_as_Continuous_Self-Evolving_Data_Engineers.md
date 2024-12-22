# 语言模型犹如不断自我进化的数据工程师

发布时间：2024年12月19日

`LLM应用` `人工智能`

> Language Models as Continuous Self-Evolving Data Engineers

# 摘要

> 大型语言模型（LLMs）在各类任务中展现出了卓越的能力，但其进一步发展受限于优质训练数据的匮乏。而且，传统训练方式过度依赖专家标注的数据，给 LLMs 的性能设置了上限。为应对此问题，我们提出了一种全新范式——LANCE，能让 LLMs 通过自主生成、清理、审查及标注带有偏好信息的数据来自我训练。我们的方法证明，LLMs 能够成为持续自我进化的数据工程师，大幅缩减了训练后数据构建过程的时间与成本。通过对 Qwen2 的不同变体进行迭代微调，我们验证了 LANCE 在各种任务中的有效性，表明其能够持续提升模型性能并保持高质量的数据生成。在八个基准维度上，LANCE 让 Qwen2-7B 的平均得分提高了 3.36，Qwen2-7B-Instruct 的平均得分提高了 2.70。这种具备自主数据构建的训练范式，不但降低了对人类专家或外部模型的依赖，还确保数据契合人类的价值观和偏好，为未来超越人类能力的超级智能系统的发展铺平了道路。

> Large Language Models (LLMs) have demonstrated remarkable capabilities on various tasks, while the further evolvement is limited to the lack of high-quality training data. In addition, traditional training approaches rely too much on expert-labeled data, setting an upper limit on the performance of LLMs. To address this issue, we propose a novel paradigm that enables LLMs to train itself by autonomously generating, cleaning, reviewing, and annotating data with preference information, named LANCE. Our approach demonstrates that LLMs can serve as continuous self-evolving data engineers, significantly reducing the time and cost of the post-training data construction process. Through iterative fine-tuning on different variants of the Qwen2, we validate the effectiveness of LANCE across various tasks, showing that it can continuously improve model performance and maintain high-quality data generation. Across eight benchmark dimensions, LANCE resulted in an average score enhancement of 3.36 for Qwen2-7B and 2.70 for Qwen2-7B-Instruct. This training paradigm with autonomous data construction not only reduces the reliance on human experts or external models but also ensures that the data aligns with human values and preferences, paving the way for the development of future superintelligent systems that can exceed human capabilities.

[Arxiv](https://arxiv.org/abs/2412.15151)