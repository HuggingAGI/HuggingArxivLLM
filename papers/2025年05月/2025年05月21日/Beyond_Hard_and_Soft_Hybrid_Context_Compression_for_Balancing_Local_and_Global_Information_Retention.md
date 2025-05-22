# 突破传统界限：混合上下文压缩，平衡局部与全局信息保留

发布时间：2025年05月21日

`LLM理论` `问答系统`

> Beyond Hard and Soft: Hybrid Context Compression for Balancing Local and Global Information Retention

# 摘要

> 大型语言模型（LLMs）在处理长序列推理时面临计算效率低下和冗余处理的挑战，这激发了人们对上下文压缩技术的兴趣。现有方法通常通过令牌重要性进行局部硬压缩，或通过编码上下文到潜在表示中进行软全局压缩。然而，由于文本内容相关性的不均衡分布以及用户指令需求的多样性，这些方法往往会丢失潜在有价值的信息。为了解决这一问题，我们提出了Hybrid Context Compression（HyCo$_2$）方法，该方法整合了全局和局部视角来指导上下文压缩，同时保留任务完成所需的必要语义和关键细节。

具体来说，我们采用了一种混合适配器，基于全局视角对全局语义进行优化，因为不同的适配器在不同任务中表现出色。然后，我们引入了一个分类层，根据局部视角为每个上下文令牌分配一个保留概率，决定其是否应保留或丢弃。为了促进全局和局部压缩的平衡整合，我们在指令微调之前引入了辅助的改写和完成预训练。这促进了对指令相关重要信息的强调，同时保留了关键的局部细节，最终在上下文压缩中实现了局部和全局信息保留的平衡。

实验表明，我们的HyCo$_2$方法显著提升了长文本推理能力，同时减少了令牌使用量。在七个知识密集型问答基准测试中，HyCo$_2$平均提升了各种LLM系列的性能13.1%。此外，HyCo$_2$在性能上与未压缩方法持平，同时将令牌消耗降低了88.8%。

> Large Language Models (LLMs) encounter significant challenges in long-sequence inference due to computational inefficiency and redundant processing, driving interest in context compression techniques. Existing methods often rely on token importance to perform hard local compression or encode context into latent representations for soft global compression. However, the uneven distribution of textual content relevance and the diversity of demands for user instructions mean these approaches frequently lead to the loss of potentially valuable information. To address this, we propose $\textbf{Hy}$brid $\textbf{Co}$ntext $\textbf{Co}$mpression (HyCo$_2$) for LLMs, which integrates both global and local perspectives to guide context compression while retaining both the essential semantics and critical details for task completion. Specifically, we employ a hybrid adapter to refine global semantics with the global view, based on the observation that different adapters excel at different tasks. Then we incorporate a classification layer that assigns a retention probability to each context token based on the local view, determining whether it should be retained or discarded. To foster a balanced integration of global and local compression, we introduce auxiliary paraphrasing and completion pretraining before instruction tuning. This promotes a synergistic integration that emphasizes instruction-relevant information while preserving essential local details, ultimately balancing local and global information retention in context compression. Experiments show that our HyCo$_2$ method significantly enhances long-text reasoning while reducing token usage. It improves the performance of various LLM series by an average of 13.1\% across seven knowledge-intensive QA benchmarks. Moreover, HyCo$_2$ matches the performance of uncompressed methods while reducing token consumption by 88.8\%.

[Arxiv](https://arxiv.org/abs/2505.15774)