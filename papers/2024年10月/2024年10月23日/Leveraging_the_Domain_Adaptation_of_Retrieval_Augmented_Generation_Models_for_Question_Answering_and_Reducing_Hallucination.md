# 借助检索增强生成模型的领域适应能力，提升问答效果并减少幻觉

发布时间：2024年10月23日

`RAG

理由：这篇论文主要讨论了检索增强生成模型（RAG）在问答任务中的应用，特别是通过领域适应来优化模型性能并减少幻觉。论文还构建了一个新的数据集HotelConvQA，并评估了多种RAG架构在领域适应后的表现。因此，这篇论文的核心内容与RAG相关，应归类为RAG。` `客户服务` `问答系统`

> Leveraging the Domain Adaptation of Retrieval Augmented Generation Models for Question Answering and Reducing Hallucination

# 摘要

> 尽管大型语言模型（LLMs）在各类NLP任务中取得了显著进展，但检索增强生成模型（RAG）在问答等下游应用中表现尤为突出。近期，RAG-end2end模型进一步优化了架构，在领域适应方面取得了显著性能提升。然而，这些基于RAG的架构在专门领域（如客户服务）微调以构建可靠对话AI系统时的有效性仍未被充分探索。此外，如何在保持高领域特定准确性的同时减少幻觉的发生，仍是一个关键挑战。本文通过领域适应研究了多种RAG及类似架构的性能，并评估了它们在基于上下文知识库生成准确和相关响应的能力。为便于模型评估，我们构建了一个新的数据集HotelConvQA，该数据集来源于广泛的酒店相关对话，并在我们的领域特定数据集上对所有模型进行了微调。我们还填补了一个关键研究空白，即确定领域适应对不同RAG架构减少幻觉的影响，这一方面在之前的研究中未得到充分衡量。评估结果显示，采用领域适应后，所有指标均取得积极成果，展示了在问答任务中的强大性能，并提供了关于其在减少幻觉方面有效性的见解。我们的研究结果明确表明，领域适应不仅提升了模型在问答任务中的表现，还显著减少了所有评估RAG架构中的幻觉。

> While ongoing advancements in Large Language Models have demonstrated remarkable success across various NLP tasks, Retrieval Augmented Generation Model stands out to be highly effective on downstream applications like Question Answering. Recently, RAG-end2end model further optimized the architecture and achieved notable performance improvements on domain adaptation. However, the effectiveness of these RAG-based architectures remains relatively unexplored when fine-tuned on specialized domains such as customer service for building a reliable conversational AI system. Furthermore, a critical challenge persists in reducing the occurrence of hallucinations while maintaining high domain-specific accuracy. In this paper, we investigated the performance of diverse RAG and RAG-like architectures through domain adaptation and evaluated their ability to generate accurate and relevant response grounded in the contextual knowledge base. To facilitate the evaluation of the models, we constructed a novel dataset HotelConvQA, sourced from wide range of hotel-related conversations and fine-tuned all the models on our domain specific dataset. We also addressed a critical research gap on determining the impact of domain adaptation on reducing hallucinations across different RAG architectures, an aspect that was not properly measured in prior work. Our evaluation shows positive results in all metrics by employing domain adaptation, demonstrating strong performance on QA tasks and providing insights into their efficacy in reducing hallucinations. Our findings clearly indicate that domain adaptation not only enhances the models' performance on QA tasks but also significantly reduces hallucination across all evaluated RAG architectures.

[Arxiv](https://arxiv.org/abs/2410.17783)