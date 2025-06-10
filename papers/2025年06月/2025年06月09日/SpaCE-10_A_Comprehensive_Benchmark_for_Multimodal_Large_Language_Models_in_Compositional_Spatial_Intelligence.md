# SpaCE-10: 多模态大型语言模型在组合空间智能方面的全方位评测

发布时间：2025年06月09日

`LLM应用

理由：这篇论文主要探讨了多模态大型语言模型（MLLMs）在空间智能方面的应用，提出了一个新的评估基准SpaCE-10，用于测试和提升模型在空间任务中的性能。它属于LLM的应用领域，因为它专注于模型在特定任务中的应用和评估，而不是理论、Agent行为或RAG方法。` `空间智能` `计算机视觉`

> SpaCE-10: A Comprehensive Benchmark for Multimodal Large Language Models in Compositional Spatial Intelligence

# 摘要

> 多模态大型语言模型（MLLMs）在多模态任务中表现突出，但要在空间领域实现更高智能，仍需整合多种原子级空间能力以应对复杂动态任务。现有基准测试难以全面评估MLLMs的空间智能，尤其在从原子到组合的层级上。为此，我们推出SpaCE-10，一个全新的组合式空间评估基准。SpaCE-10定义了10种原子级空间能力，并组合成8种复合能力。通过创新的层次化标注流水线，我们生成了高质量、多样化的问答对。经过150多小时的专家工作，SpaCE-10涵盖了811个真实室内场景的5000多个问答对，支持点云输入和多选问答等多种评估模式。实验表明，即使是最先进的MLLMs在空间智能上仍远逊于人类。研究发现，计数能力的不足严重限制了MLLMs的组合式空间能力。更多细节请访问https://github.com/Cuzyoung/SpaCE-10。

> Multimodal Large Language Models (MLLMs) have achieved remarkable progress in various multimodal tasks. To pursue higher intelligence in space, MLLMs require integrating multiple atomic spatial capabilities to handle complex and dynamic tasks. However, existing benchmarks struggle to comprehensively evaluate the spatial intelligence of common MLLMs from the atomic level to the compositional level. To fill this gap, we present SpaCE-10, a comprehensive benchmark for compositional spatial evaluations. In SpaCE-10, we define 10 atomic spatial capabilities, which are combined to form 8 compositional capabilities. Based on these definitions, we propose a novel hierarchical annotation pipeline to generate high-quality and diverse question-answer (QA) pairs. With over 150+ hours of human expert effort, we obtain over 5k QA pairs for 811 real indoor scenes in SpaCE-10, which covers various evaluation settings like point cloud input and multi-choice QA. We conduct an extensive evaluation of common MLLMs on SpaCE-10 and find that even the most advanced MLLM still lags behind humans by large margins. Through our careful study, we also draw several significant findings that benefit the MLLM community. For example, we reveal that the shortcoming of counting capability greatly limits the compositional spatial capabilities of existing MLLMs. The evaluation code and benchmark datasets are available at https://github.com/Cuzyoung/SpaCE-10.

[Arxiv](https://arxiv.org/abs/2506.07966)