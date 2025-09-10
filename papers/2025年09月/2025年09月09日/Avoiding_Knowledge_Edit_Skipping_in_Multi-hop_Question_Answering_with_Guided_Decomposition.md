# 基于引导式分解避免多跳问答中的知识编辑跳过

发布时间：2025年09月09日

`RAG` `基础理论`

> Avoiding Knowledge Edit Skipping in Multi-hop Question Answering with Guided Decomposition

# 摘要

> 在信息飞速更新的快节奏世界中，大型语言模型（LLMs）的知识很快就会过时。重新训练LLMs成本高昂，并非理想选择，因此无需修改参数的知识编辑（KE）技术变得尤为关键。我们发现，现有基于检索增强生成（RAG）的KE方法虽擅长编辑简单知识，但在多跳问答的KE任务中却因“编辑跳过”问题举步维艰——所谓“编辑跳过”，即推理时忽略了相关的已编辑事实。除了知识的自然语言表达存在多样性外，编辑跳过的根源还在于LLMs解决问题时的粒度与已编辑记忆中事实的粒度不匹配。为解决这一难题，我们提出了一种新的引导分解迭代检索增强知识编辑方法（IRAKE），该方法通过单个已编辑事实和完整已编辑案例的双重引导实现。实验结果表明，IRAKE有效缓解了编辑跳过导致的编辑失效问题，并在多跳问答的KE任务上超越了当前最先进的方法。

> In a rapidly evolving world where information updates swiftly, knowledge in large language models (LLMs) becomes outdated quickly. Retraining LLMs is not a cost-effective option, making knowledge editing (KE) without modifying parameters particularly necessary. We find that although existing retrieval-augmented generation (RAG)-based KE methods excel at editing simple knowledge, they struggle with KE in multi-hop question answering due to the issue of "edit skipping", which refers to skipping the relevant edited fact in inference. In addition to the diversity of natural language expressions of knowledge, edit skipping also arises from the mismatch between the granularity of LLMs in problem-solving and the facts in the edited memory. To address this issue, we propose a novel Iterative Retrieval-Augmented Knowledge Editing method with guided decomposition (IRAKE) through the guidance from single edited facts and entire edited cases. Experimental results demonstrate that IRAKE mitigates the failure of editing caused by edit skipping and outperforms state-of-the-art methods for KE in multi-hop question answering.

[Arxiv](https://arxiv.org/abs/2509.07555)