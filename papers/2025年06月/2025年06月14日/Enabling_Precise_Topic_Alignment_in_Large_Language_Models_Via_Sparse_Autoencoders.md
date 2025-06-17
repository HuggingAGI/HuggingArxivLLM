# 借助稀疏自编码器实现大型语言模型的精确主题对齐

发布时间：2025年06月14日

`LLM应用`

> Enabling Precise Topic Alignment in Large Language Models Via Sparse Autoencoders

# 摘要

> 近期研究表明，稀疏自编码器（SAE）在大型语言模型（LLM）各层的应用中，其神经元对应于可解释的概念。现有方法仅能通过调整 SAE 神经元对齐生成输出结果，但受限于预定义主题和参数调优需求。我们提出的方法基于 SAE 的观测与修改特性，实现了对任意主题的对齐能力。该方法通过 1) 计算每个 SAE 神经元与对齐文本的语义相似性评分，2) 强调与主题对齐的神经元来优化 SAE 层级输出。我们在亚马逊评论、医学和阿谀奉承等多样化公开主题数据集上评估了该方法的对齐能力，并在开源 LLM 和 SAE 组合（GPT2 和 Gemma）及多种 SAE 配置下进行了测试。实验结果表明，与微调方法相比，该方法在医学提示对齐任务中具有显著优势，包括更高的平均语言可接受性评分（0.25 vs. 0.5）、更短的训练时间（333.6 秒 vs. 62 秒）以及适用于多种应用的推理时间（+0.00092 秒/词）。我们的开源代码可在 github.com/IBM/sae-steering 获取。

> Recent work shows that Sparse Autoencoders (SAE) applied to large language model (LLM) layers have neurons corresponding to interpretable concepts. These SAE neurons can be modified to align generated outputs, but only towards pre-identified topics and with some parameter tuning. Our approach leverages the observational and modification properties of SAEs to enable alignment for any topic. This method 1) scores each SAE neuron by its semantic similarity to an alignment text and uses them to 2) modify SAE-layer-level outputs by emphasizing topic-aligned neurons. We assess the alignment capabilities of this approach on diverse public topic datasets including Amazon reviews, Medicine, and Sycophancy, across the currently available open-source LLMs and SAE pairs (GPT2 and Gemma) with multiple SAEs configurations. Experiments aligning to medical prompts reveal several benefits over fine-tuning, including increased average language acceptability (0.25 vs. 0.5), reduced training time across multiple alignment topics (333.6s vs. 62s), and acceptable inference time for many applications (+0.00092s/token). Our open-source code is available at github.com/IBM/sae-steering.

[Arxiv](https://arxiv.org/abs/2506.12576)