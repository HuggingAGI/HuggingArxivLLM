# AutoRev：面向学术研究论文的自动同行评审系统

发布时间：2025年05月20日

`LLM应用` `学术研究` `学术论文`

> AutoRev: Automatic Peer Review System for Academic Research Papers

# 摘要

> 撰写学术论文评审意见是一项复杂任务，需要深入理解论文内容及其各部分的相互关联。这不仅要求掌握技术细节，还需对论文整体结构和连贯性有透彻把握。近期研究主要通过微调大型语言模型（LLMs）来应对这一挑战，但往往忽视了长输入令牌带来的计算和性能限制。为此，我们推出AutoRev——一个用于学术研究论文的自动同行评审系统。我们的创新框架将学术文档表示为图结构，能够提取对评审至关重要的关键段落。这种基于图的方法在评审生成中表现出色，且可灵活应用于问答、摘要和文档表示等多种下游任务。在评审生成任务中，我们的方法在所有评估指标上平均比最先进（SOTA）基线高出58.72%。我们期待这项工作能激发更多研究，将基于图的提取技术应用于NLP的其他下游任务。我们计划在论文被接受后公开代码。

> Generating a review for an academic research paper is a complex task that requires a deep understanding of the document's content and the interdependencies between its sections. It demands not only insight into technical details but also an appreciation of the paper's overall coherence and structure. Recent methods have predominantly focused on fine-tuning large language models (LLMs) to address this challenge. However, they often overlook the computational and performance limitations imposed by long input token lengths. To address this, we introduce AutoRev, an Automatic Peer Review System for Academic Research Papers. Our novel framework represents an academic document as a graph, enabling the extraction of the most critical passages that contribute significantly to the review. This graph-based approach demonstrates effectiveness for review generation and is potentially adaptable to various downstream tasks, such as question answering, summarization, and document representation. When applied to review generation, our method outperforms SOTA baselines by an average of 58.72% across all evaluation metrics. We hope that our work will stimulate further research in applying graph-based extraction techniques to other downstream tasks in NLP. We plan to make our code public upon acceptance.

[Arxiv](https://arxiv.org/abs/2505.14376)