# 大型语言模型擅长于在上下文中学习分子知识（注：由于原文标题简洁且具有一定的专业性，从准确性和生动性角度考虑，在翻译时保留了“上下文”这一术语，并将“learner”译为更符合中文表达习惯的“学习者”，同时也强调了其在分子领域的学习能力。）

发布时间：2024年03月06日

`LLM应用`

> Large Language Models are In-Context Molecule Learners

# 摘要

> LLMs 在生化任务，特别是分子描述翻译这一连接分子世界与自然语言文本的任务中表现非凡。然而，以往的方法在让 LLMs 适应此类任务时面临诸多问题，比如需要额外的领域预训练，分子与文本空间对齐较弱，或是对模型规模有苛刻要求。因此，我们创新性地提出了“基于上下文的分子适应”（ICMA）这一新思路，运用“基于上下文的分子微调”技术，让 LLMs 从实例化的上下文中习得分子与文本间的对应关系。ICMA 过程分为三步走：跨模态检索、检索后重排序以及基于上下文的分子微调。起始阶段，跨模态检索采用 BM25 描述检索和分子图检索技术捕获富含信息的上下文示例；进一步，我们引入结合序列反转与随机游走的检索后重排序策略，提升检索结果的质量；最终，基于上下文的分子微调环节激活了 LLMs 对上下文分子知识的学习潜力，并针对性地微调 LLMs 参数以优化分子描述翻译任务。实验证明，ICMT 能够赋予 LLMs 在无额外训练数据集和复杂架构的情况下达到当前最优或相当的性能水平，有力地证实了 LLMs 内在具备上下文分子学习的潜能。

> Large Language Models (LLMs) have demonstrated exceptional performance in biochemical tasks, especially the molecule caption translation task, which aims to bridge the gap between molecules and natural language texts. However, previous methods in adapting LLMs to the molecule-caption translation task required extra domain-specific pre-training stages, suffered weak alignment between molecular and textual spaces, or imposed stringent demands on the scale of LLMs. To resolve the challenges, we propose In-Context Molecule Adaptation (ICMA), as a new paradigm allowing LLMs to learn the molecule-text alignment from context examples via In-Context Molecule Tuning. Specifically, ICMA incorporates the following three stages: Cross-modal Retrieval, Post-retrieval Re-ranking, and In-context Molecule Tuning. Initially, Cross-modal Retrieval utilizes BM25 Caption Retrieval and Molecule Graph Retrieval to retrieve informative context examples. Additionally, we also propose Post-retrieval Re-ranking with Sequence Reversal and Random Walk to further improve the quality of retrieval results. Finally, In-Context Molecule Tuning unlocks the in-context molecule learning capability of LLMs with retrieved examples and adapts the parameters of LLMs for the molecule-caption translation task. Experimental results demonstrate that ICMT can empower LLMs to achieve state-of-the-art or comparable performance without extra training corpora and intricate structures, showing that LLMs are inherently in-context molecule learners.

[Arxiv](https://arxiv.org/abs/2403.04197)