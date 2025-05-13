# 文档归属：借助大型语言模型探究引用关联

发布时间：2025年05月09日

`LLM应用` `问答系统` `信息抽取`

> Document Attribution: Examining Citation Relationships using Large Language Models

# 摘要

> 随着大型语言模型（LLMs）在文档摘要、问答和信息抽取等基于文档的任务中得到广泛应用，用户需求更多是提取文档中的信息，而非依赖模型自身的知识储备。因此，确保这些系统的可信度和可解释性已成为关键问题。归因方法通过追踪生成的输出回溯到其来源文档，是解决这一问题的核心。然而，由于LLMs可能会生成不准确或不精确的回答，因此评估这些引用的可靠性至关重要。

为应对这一挑战，我们提出了两种创新技术。第一种是零样本方法，将归因视为一个简单的文本蕴含任务。通过使用flan-ul2，我们在归因基准测试（AttributionBench）中分别在ID和OOD数据集上实现了0.27%和2.4%的性能提升。第二种是通过较小规模的LLM（flan-t5-small）探索注意力机制在增强归因过程中的作用。实验结果显示，我们的F1分数在几乎所有层数中都优于基线模型，仅在第4层和第8至11层除外。

> As Large Language Models (LLMs) are increasingly applied to document-based tasks - such as document summarization, question answering, and information extraction - where user requirements focus on retrieving information from provided documents rather than relying on the model's parametric knowledge, ensuring the trustworthiness and interpretability of these systems has become a critical concern. A central approach to addressing this challenge is attribution, which involves tracing the generated outputs back to their source documents. However, since LLMs can produce inaccurate or imprecise responses, it is crucial to assess the reliability of these citations.
  To tackle this, our work proposes two techniques. (1) A zero-shot approach that frames attribution as a straightforward textual entailment task. Our method using flan-ul2 demonstrates an improvement of 0.27% and 2.4% over the best baseline of ID and OOD sets of AttributionBench, respectively. (2) We also explore the role of the attention mechanism in enhancing the attribution process. Using a smaller LLM, flan-t5-small, the F1 scores outperform the baseline across almost all layers except layer 4 and layers 8 through 11.

[Arxiv](https://arxiv.org/abs/2505.06324)