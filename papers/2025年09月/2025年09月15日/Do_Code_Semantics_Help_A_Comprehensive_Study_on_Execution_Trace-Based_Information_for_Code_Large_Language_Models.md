# 代码语义是否有用？基于执行轨迹信息的代码大型语言模型综合研究

发布时间：2025年09月15日

`LLM应用` `基础理论`

> Do Code Semantics Help? A Comprehensive Study on Execution Trace-Based Information for Code Large Language Models

# 摘要

> 代码大型语言模型（Code LLMs）凭借卓越性能开启了编程新纪元。然而，近期研究发现其在推理程序运行时行为及理解实际功能方面存在关键局限，这给模型的后训练与实际部署带来了巨大挑战。具体而言，代码LLM面临两大核心问题：（1）难以准确推理程序执行行为——它们无法清晰解释程序在运行时的实际操作；（2）现有方法对执行轨迹等语义信息的表示不一致且碎片化，严重制约了模型的泛化与推理能力。这些挑战表明，亟需更系统的方法来提升代码LLM的推理能力。为应对这些问题，我们提出了一个通用框架，支持将语义信息（如执行轨迹）整合到代码任务相关提示中，并通过全面研究探索了语义信息在提升代码LLM推理能力中的作用。具体而言，我们重点研究了基于轨迹的语义信息在提升代码LLM监督微调（SFT）和后阶段推理中的作用。实验结果意外地与先前研究相悖，表明语义信息对代码LLM的SFT和测试时扩展作用有限。

> Code Large Language Models (Code LLMs) have opened a new era in programming with their impressive capabilities. However, recent research has revealed critical limitations in their ability to reason about runtime behavior and understand the actual functionality of programs, which poses significant challenges for their post-training and practical deployment. Specifically, Code LLMs encounter two principal issues: (1) a lack of proficiency in reasoning about program execution behavior, as they struggle to interpret what programs actually do during runtime, and (2) the inconsistent and fragmented representation of semantic information, such as execution traces, across existing methods, which hinders their ability to generalize and reason effectively. These challenges underscore the necessity for more systematic approaches to enhance the reasoning capabilities of Code LLMs. To address these issues, we introduce a generic framework to support integrating semantic information~(e.g., execution trace) to code task-relevant prompts, and conduct a comprehensive study to explore the role of semantic information in enhancing the reasoning ability of Code LLMs accordingly. Specifically, we focus on investigating the usefulness of trace-based semantic information in boosting supervised fine-tuning~(SFT) and post-phase inference of Code LLMs. The experimental results surprisingly disagree with previous works and demonstrate that semantic information has limited usefulness for SFT and test time scaling of Code LLM.

[Arxiv](https://arxiv.org/abs/2509.11686)