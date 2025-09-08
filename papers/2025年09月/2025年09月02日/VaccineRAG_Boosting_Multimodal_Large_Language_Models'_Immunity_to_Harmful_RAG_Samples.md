# VaccineRAG：提升多模态大语言模型对有害RAG样本的免疫力

发布时间：2025年09月02日

`RAG` `基础理论`

> VaccineRAG: Boosting Multimodal Large Language Models' Immunity to Harmful RAG Samples

# 摘要

> 检索增强生成（Retrieval Augmented Generation）通过融合检索、生成模块与外部知识，有效提升了大型语言模型（LLMs）的响应精度，尤其在实时查询和视觉问答任务中优势显著。然而，RAG的效能常受限于检索器的精度——大量输入生成阶段的检索样本要么无关要么带有误导性，成为制约LLMs性能的关键瓶颈。为此，我们提出VaccineRAG——一个基于思维链（Chain-of-Thought）的新型检索增强生成数据集。一方面，VaccineRAG构建了基准测试，通过不同正负样本比例的数据评估模型，系统性地暴露当前LLMs的固有缺陷；另一方面，它通过引导LLMs在生成最终答案前为每个样本生成明确的思维链（CoT）分析，提升模型对样本的辨别能力。此外，为提升模型对长序列复杂CoT内容的学习能力，我们还提出了Partial-GRPO方法。该方法将LLMs的输出拆解为多个组件而非单一整体，使模型能对复杂序列做出更合理的偏好选择，进而提升学习复杂CoT的能力。在VaccineRAG上的综合评估与消融实验证实了所提方案的有效性，相关代码和数据集即将公开发布。

> Retrieval Augmented Generation enhances the response accuracy of Large Language Models (LLMs) by integrating retrieval and generation modules with external knowledge, demonstrating particular strength in real-time queries and Visual Question Answering tasks. However, the effectiveness of RAG is frequently hindered by the precision of the retriever: many retrieved samples fed into the generation phase are irrelevant or misleading, posing a critical bottleneck to LLMs' performance. To address this challenge, we introduce VaccineRAG, a novel Chain-of-Thought-based retrieval-augmented generation dataset. On one hand, VaccineRAG employs a benchmark to evaluate models using data with varying positive/negative sample ratios, systematically exposing inherent weaknesses in current LLMs. On the other hand, it enhances models' sample-discrimination capabilities by prompting LLMs to generate explicit Chain-of-Thought (CoT) analysis for each sample before producing final answers. Furthermore, to enhance the model's ability to learn long-sequence complex CoT content, we propose Partial-GRPO. By modeling the outputs of LLMs as multiple components rather than a single whole, our model can make more informed preference selections for complex sequences, thereby enhancing its capacity to learn complex CoT. Comprehensive evaluations and ablation studies on VaccineRAG validate the effectiveness of the proposed scheme. The code and dataset will be publicly released soon.

[Arxiv](https://arxiv.org/abs/2509.04502)