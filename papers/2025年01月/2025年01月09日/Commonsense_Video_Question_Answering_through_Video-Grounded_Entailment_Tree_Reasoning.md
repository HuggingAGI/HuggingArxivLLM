# 基于视频的蕴含树推理实现常识视频问答

发布时间：2025年01月09日

`LLM应用

理由：这篇论文主要讨论了如何利用大型视觉语言模型（VLMs）和大型语言模型（LLMs）来改进视频问答（VQA）任务。虽然论文中提到了视觉语言模型，但其核心方法依赖于大型语言模型进行去偏和推理，因此可以归类为LLM应用。` `视频问答` `常识推理`

> Commonsense Video Question Answering through Video-Grounded Entailment Tree Reasoning

# 摘要

> 本文首次提出了一种基于视频的蕴含树推理方法，用于常识性视频问答（VQA）。尽管大型视觉语言模型（VLMs）取得了显著进展，但其黑箱性质和基准测试偏见可能导致模型学习到视频与答案之间的虚假关联。我们的方法通过四个步骤将VQA任务明确地基于视频片段：构建蕴含树、验证视频语言蕴含、进行树推理和动态扩展树。该方法的一个关键优势是其对当前基于视频和图像的VLMs在不同推理类型上的通用性。为了确保公平评估，我们设计了一种基于大型语言模型的去偏程序，通过重写VQA基准答案集来强制模型进行推理。在现有和去偏基准上的系统实验表明，我们的方法组件在基准、VLMs和推理类型上均产生了显著影响。

> This paper proposes the first video-grounded entailment tree reasoning method for commonsense video question answering (VQA). Despite the remarkable progress of large visual-language models (VLMs), there are growing concerns that they learn spurious correlations between videos and likely answers, reinforced by their black-box nature and remaining benchmarking biases. Our method explicitly grounds VQA tasks to video fragments in four steps: entailment tree construction, video-language entailment verification, tree reasoning, and dynamic tree expansion. A vital benefit of the method is its generalizability to current video and image-based VLMs across reasoning types. To support fair evaluation, we devise a de-biasing procedure based on large-language models that rewrites VQA benchmark answer sets to enforce model reasoning. Systematic experiments on existing and de-biased benchmarks highlight the impact of our method components across benchmarks, VLMs, and reasoning types.

[Arxiv](https://arxiv.org/abs/2501.05069)