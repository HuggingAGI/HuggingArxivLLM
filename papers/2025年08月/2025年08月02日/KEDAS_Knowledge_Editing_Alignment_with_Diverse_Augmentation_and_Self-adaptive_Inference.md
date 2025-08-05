# 知识编辑对齐方法：多样化增强与自适应推理驱动的KEDAS。

发布时间：2025年08月02日

`LLM理论

理由：这篇论文探讨了大型语言模型（LLMs）的知识编辑机制，提出了一种新的方法KEDAS，用于改进模型的知识对齐和编辑能力。研究集中在模型内部的调整和优化，属于理论层面的探讨，因此归类为LLM理论。` `知识管理`

> KEDAS: Knowledge Editing Alignment with Diverse Augmentation and Self-adaptive Inference

# 摘要

> 知识编辑致力于高效修改大型语言模型（LLMs）中的过时知识，同时保留其强大的能力。现有的大多数方法依赖于基于参数的编辑方法，或是基于检索的方法。为此，我们提出了知识编辑对齐方法KEDAS（Knowledge Editing alignment with Diverse Augmentation and Self-adaptive inference），以更好地实现LLMs与知识编辑的对齐。在对齐阶段，LLMs通过低秩适配学习如何应用上下文编辑的知识。编辑过程中，我们设计了一种多样化的编辑增强技术，以提高编辑的召回率。随后，我们提出了一种自适应的后对齐推理机制，其中采用基于过滤的智能检索器来动态选择推理路由。具体来说，不相关的查询将直接通过原始预对齐模型处理，而相关查询则与相关的编辑内容一起，通过带有激活对齐适配器的模型进行处理。实验结果表明，KEDAS在四个数据集上，使用三种LLMs，在三种设置下，总共36个案例中的35个案例中取得了最高的整体性能得分。与强大的知识编辑对齐竞争对手相比，KEDAS在编辑成功、局部性和可移植性方面获得了约19.8个调和平均分的优势，并且显著优于基于参数编辑和基于检索的基线方法。计算成本分析以及在一般任务上的性能进一步验证了KEDAS的鲁棒性和效率，表明它为知识编辑对齐提供了一种理想的范式。

> Knowledge editing aims to modify outdated knowledge in large language models (LLMs) efficiently while retaining their powerful capabilities. Most existing methods rely on either parameter-level editing or retrieval-based approaches. In this work, we propose Knowledge Editing alignment with Diverse Augmentation and Self-adaptive inference (KEDAS) to better align LLMs with knowledge editing. In the alignment phase, LLMs learn to apply in-context edited knowledge via low-rank adaptation. During editing, we design a diverse edit augmentation technique to improve the recall of edits. After that, a self-adaptive post-alignment inference mechanism is proposed, in which a filter-based smart retriever is employed to perform a dynamic selection of inference routing. Specifically, irrelevant queries will go through the original pre-alignment model directly, while relevant ones, together with their related edits, go through the model with aligned adapters activated. In experiments, KEDAS secures the highest overall performance scores in 35 out of 36 cases across four datasets with three LLMs on three settings, surpassing its strong knowledge editing alignment counterpart by about 19.8 harmonic mean scores of edit success, locality and portability and outperforming both parameter editing and retrieval-based baselines significantly. Analysis of computational cost and performance on general tasks further validates the robustness and efficiency of KEDAS, indicating that it presents an ideal paradigm of knowledge editing alignment.

[Arxiv](https://arxiv.org/abs/2508.01302)