# LIMO: 少即是多，推理更高效

发布时间：2025年02月05日

`LLM理论

理由：这篇论文主要探讨了大型语言模型（LLM）在复杂推理任务中的表现，特别是通过少量示例激发复杂推理能力的现象。论文提出了“少即是多推理假设”（LIMO假设），并讨论了预训练阶段和后训练示例对模型推理能力的影响。这些内容涉及LLM的理论基础和工作机制，因此应归类为LLM理论。` `人工智能`

> LIMO: Less is More for Reasoning

# 摘要

> 我们揭示了一个颠覆性的发现，挑战了我们对大型语言模型中复杂推理能力形成的传统认知。尽管普遍认为复杂推理任务需要海量训练数据（>10万样本），但我们发现，仅需少量示例即可有效激发复杂的数学推理能力。通过一系列实验，我们提出的LIMO模型在数学推理任务中展现了前所未有的性能。仅用817个精选训练样本，LIMO在AIME和MATH测试集上分别达到了57.1%和94.8%的准确率，远超此前基于SFT模型的6.5%和59.2%，且仅使用了1%的训练数据。LIMO在分布外泛化方面表现尤为突出，在10个不同基准测试中实现了40.5%的绝对提升，优于使用100倍数据训练的模型，这挑战了SFT导致记忆而非泛化的观点。基于这些发现，我们提出了“少即是多推理假设”（LIMO假设）：在预训练阶段已全面编码领域知识的基础模型中，通过少量但精心设计的认知过程演示，即可激发复杂的推理能力。该假设认为，复杂推理的激发阈值取决于两个关键因素：（1）模型在预训练阶段编码的知识基础的完整性，以及（2）后训练示例作为“认知模板”的有效性，这些示例展示了模型如何利用其知识库解决复杂推理任务。为了推动数据高效推理的可重复性和未来研究，我们在https://github.com/GAIR-NLP/LIMO上开源了LIMO套件。

> We present a fundamental discovery that challenges our understanding of how complex reasoning emerges in large language models. While conventional wisdom suggests that sophisticated reasoning tasks demand extensive training data (>100,000 examples), we demonstrate that complex mathematical reasoning abilities can be effectively elicited with surprisingly few examples. Through comprehensive experiments, our proposed model LIMO demonstrates unprecedented performance in mathematical reasoning. With merely 817 curated training samples, LIMO achieves 57.1% accuracy on AIME and 94.8% on MATH, improving from previous SFT-based models' 6.5% and 59.2% respectively, while only using 1% of the training data required by previous approaches. LIMO demonstrates exceptional out-of-distribution generalization, achieving 40.5% absolute improvement across 10 diverse benchmarks, outperforming models trained on 100x more data, challenging the notion that SFT leads to memorization rather than generalization. Based on these results, we propose the Less-Is-More Reasoning Hypothesis (LIMO Hypothesis): In foundation models where domain knowledge has been comprehensively encoded during pre-training, sophisticated reasoning capabilities can emerge through minimal but precisely orchestrated demonstrations of cognitive processes. This hypothesis posits that the elicitation threshold for complex reasoning is determined by two key factors: (1) the completeness of the model's encoded knowledge foundation during pre-training, and (2) the effectiveness of post-training examples as "cognitive templates" that show the model how to utilize its knowledge base to solve complex reasoning tasks. To facilitate reproducibility and future research in data-efficient reasoning, we release LIMO as a comprehensive open-source suite at https://github.com/GAIR-NLP/LIMO.

[Arxiv](https://arxiv.org/abs/2502.03387)