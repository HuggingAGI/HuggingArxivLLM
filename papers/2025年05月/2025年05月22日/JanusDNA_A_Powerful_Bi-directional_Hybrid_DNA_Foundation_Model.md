# # JanusDNA：一款强大的双向往返混合DNA基模型

发布时间：2025年05月22日

`LLM应用` `基因组学` `生物信息学`

> JanusDNA: A Powerful Bi-directional Hybrid DNA Foundation Model

# 摘要

> 大型语言模型（LLMs）彻底改变了自然语言处理领域，并逐渐被应用于其他类型的序列数据，包括基因序列。然而，将LLMs应用于基因组学面临重大挑战。捕捉复杂的基因组相互作用需要对DNA序列中的长程依赖关系进行建模，其中相互作用常常跨越超过10,000个碱基对，即使是在单个基因内部，这在传统模型架构和训练范式下带来了巨大的计算负担。

此外，标准的LLM训练方法对于DNA来说效果不佳：虽然自回归训练高效，但仅支持单向理解。然而，DNA本质上是双向的，例如，双向启动子在两个方向上调节转录，占人类基因表达的近11%。遮蔽语言模型（MLMs）允许双向理解，但效率低下，因为每一步只有被遮蔽的标记才对损失做出贡献。

为了解决这些限制，我们引入了JanusDNA，这是首个基于新型预训练范式的双向DNA基础模型，结合了自回归建模的优化效率和遮蔽建模的双向理解能力。JanusDNA采用了混合的Mamba、注意力和专家混合模型（MoE）架构，结合了注意力的长程建模能力和Mamba的高效序列学习能力。MoE层通过稀疏激活进一步扩展模型容量，同时保持计算成本低廉。

值得注意的是，JanusDNA可以在单个80GB GPU上以单核苷酸分辨率处理多达100万个碱基对。大量实验和消融研究显示，JanusDNA在三个基因组表示基准测试中达到了新的SOTA结果，超越了激活参数多250倍的模型。

代码：https://github.com/Qihao-Duan/JanusDNA

> Large language models (LLMs) have revolutionized natural language processing and are increasingly applied to other sequential data types, including genetic sequences. However, adapting LLMs to genomics presents significant challenges. Capturing complex genomic interactions requires modeling long-range dependencies within DNA sequences, where interactions often span over 10,000 base pairs, even within a single gene, posing substantial computational burdens under conventional model architectures and training paradigms. Moreover, standard LLM training approaches are suboptimal for DNA: autoregressive training, while efficient, supports only unidirectional understanding. However, DNA is inherently bidirectional, e.g., bidirectional promoters regulate transcription in both directions and account for nearly 11% of human gene expression. Masked language models (MLMs) allow bidirectional understanding but are inefficient, as only masked tokens contribute to the loss per step. To address these limitations, we introduce JanusDNA, the first bidirectional DNA foundation model built upon a novel pretraining paradigm that combines the optimization efficiency of autoregressive modeling with the bidirectional comprehension of masked modeling. JanusDNA adopts a hybrid Mamba, Attention and Mixture of Experts (MoE) architecture, combining long-range modeling of Attention with efficient sequential learning of Mamba. MoE layers further scale model capacity via sparse activation while keeping computational cost low. Notably, JanusDNA processes up to 1 million base pairs at single nucleotide resolution on a single 80GB GPU. Extensive experiments and ablations show JanusDNA achieves new SOTA results on three genomic representation benchmarks, outperforming models with 250x more activated parameters. Code: https://github.com/Qihao-Duan/JanusDNA

[Arxiv](https://arxiv.org/abs/2505.17257)