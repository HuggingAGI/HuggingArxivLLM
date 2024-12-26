# 通过显性工作记忆提高事实性

发布时间：2024年12月23日

`RAG` `长文本生成`

> Improving Factuality with Explicit Working Memory

# 摘要

> 大型语言模型可能会生成事实不准确的内容，此问题称作幻觉。近来的工作基于检索增强生成，借由迭代提示来提升事实准确性，然而这些方法受传统 RAG 设计所限。为应对这些挑战，我们推出 EWE（显式工作记忆）这一新颖手段，通过整合能接收外部资源实时反馈的工作记忆，来增强长文本生成中的事实准确性。该记忆依据在线事实核查和检索反馈进行刷新，让 EWE 能在生成过程中纠正错误说法，保证更准确可靠的输出。我们的实验显示，Ewe 在四个寻求事实的长文本生成数据集中表现优于强劲的基线，使事实性指标 VeriScore 绝对提升 2 至 10 分，且不降低响应的有用性。进一步分析表明，记忆更新规则的设计、记忆单元的配置以及检索数据存储的质量是影响模型性能的关键要素。

> Large language models can generate factually inaccurate content, a problem known as hallucination. Recent works have built upon retrieved-augmented generation to improve factuality through iterative prompting but these methods are limited by the traditional RAG design. To address these challenges, we introduce EWE (Explicit Working Memory), a novel approach that enhances factuality in long-form text generation by integrating a working memory that receives real-time feedback from external resources. The memory is refreshed based on online fact-checking and retrieval feedback, allowing EWE to rectify false claims during the generation process and ensure more accurate and reliable outputs. Our experiments demonstrate that Ewe outperforms strong baselines on four fact-seeking long-form generation datasets, increasing the factuality metric, VeriScore, by 2 to 10 points absolute without sacrificing the helpfulness of the responses. Further analysis reveals that the design of rules for memory updates, configurations of memory units, and the quality of the retrieval datastore are crucial factors for influencing model performance.

[Arxiv](https://arxiv.org/abs/2412.18069)