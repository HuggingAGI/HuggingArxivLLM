# 高效数据微调：优化大型语言模型用于代码生成

发布时间：2025年04月17日

`LLM理论` `代码生成`

> Data-efficient LLM Fine-tuning for Code Generation

# 摘要

> 大型语言模型（LLMs）在代码生成任务中展现了巨大潜力，但开源与闭源模型间仍存在性能差距。现有方法通常通过生成大量合成数据进行微调，但这往往导致训练效率低下。我们提出了一种数据选择策略，以提升代码基LLMs的训练效果和效率。通过优先考虑数据复杂度，并确保采样子集与原始数据集分布一致，我们的采样策略能够有效选择高质量数据。此外，我们还通过“动态打包”技术优化了分词过程，从而减少了填充标记的使用，降低了计算资源的消耗。实验结果表明，在使用OSS-Instruct数据集的40%进行训练时，DeepSeek-Coder-Base-6.7B模型的平均性能达到了66.9%，超过了使用完整数据集时的66.1%性能表现。同时，训练时间从47分钟缩短至34分钟，单个epoch期间的GPU峰值内存从61.47 GB降至42.72 GB。在Evol-Instruct数据集上，CodeLlama-Python-7B模型也观察到了类似的改进。通过优化数据选择和分词过程，我们的方法不仅提升了模型性能，还显著提高了训练效率。

> Large language models (LLMs) have demonstrated significant potential in code generation tasks. However, there remains a performance gap between open-source and closed-source models. To address this gap, existing approaches typically generate large amounts of synthetic data for fine-tuning, which often leads to inefficient training. In this work, we propose a data selection strategy in order to improve the effectiveness and efficiency of training for code-based LLMs. By prioritizing data complexity and ensuring that the sampled subset aligns with the distribution of the original dataset, our sampling strategy effectively selects high-quality data. Additionally, we optimize the tokenization process through a "dynamic pack" technique, which minimizes padding tokens and reduces computational resource consumption. Experimental results show that when training on 40% of the OSS-Instruct dataset, the DeepSeek-Coder-Base-6.7B model achieves an average performance of 66.9%, surpassing the 66.1% performance with the full dataset. Moreover, training time is reduced from 47 minutes to 34 minutes, and the peak GPU memory decreases from 61.47 GB to 42.72 GB during a single epoch. Similar improvements are observed with the CodeLlama-Python-7B model on the Evol-Instruct dataset. By optimizing both data selection and tokenization, our approach not only improves model performance but also improves training efficiency.

[Arxiv](https://arxiv.org/abs/2504.12687)