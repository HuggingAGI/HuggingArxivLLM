# 多智能体互动式问题生成框架，助力长文档理解

发布时间：2025年07月27日

`LLM应用` `文档理解` `视觉-语言模型`

> Multi-Agent Interactive Question Generation Framework for Long Document Understanding

# 摘要

> # 摘要  
在长上下文且布局复杂的场景中，文档理解（DU）仍然是视觉-语言研究领域的重要挑战。尽管大型视觉-语言模型（LVLMs）在短上下文的文档理解任务中表现出色，但它们在处理长上下文场景时性能显著下降。一个关键的限制因素是精细标注的训练数据稀缺，尤其是对于像阿拉伯语这样的低资源语言。现有的最先进的技术严重依赖人工标注，这不仅成本高昂，而且效率低下。我们提出了一种完全自动化的多智能体交互框架，用于高效生成长上下文问题。我们的方法能够高效生成高质量的单页和多页问题，涵盖数百页跨越多个领域的英文和阿拉伯文文档。这有助于提升LVLMs的长上下文理解能力。本研究的实验结果表明，我们生成的英文和阿拉伯语问题（	extbf{AraEngLongBench}）对主要的开源和闭源LVLMs具有相当大的挑战性。本文提出的方法代码和数据可在https://github.com/wangk0b/Multi_Agentic_QA_Long_Doc.git获取。样本问答对（QA）和结构化系统提示可在附录中找到。

> Document Understanding (DU) in long-contextual scenarios with complex layouts remains a significant challenge in vision-language research. Although Large Vision-Language Models (LVLMs) excel at short-context DU tasks, their performance declines in long-context settings. A key limitation is the scarcity of fine-grained training data, particularly for low-resource languages such as Arabic. Existing state-of-the-art techniques rely heavily on human annotation, which is costly and inefficient. We propose a fully automated, multi-agent interactive framework to generate long-context questions efficiently. Our approach efficiently generates high-quality single- and multi-page questions for extensive English and Arabic documents, covering hundreds of pages across diverse domains. This facilitates the development of LVLMs with enhanced long-context understanding ability. Experimental results in this work have shown that our generated English and Arabic questions (\textbf{AraEngLongBench}) are quite challenging to major open- and close-source LVLMs. The code and data proposed in this work can be found in https://github.com/wangk0b/Multi_Agentic_QA_Long_Doc.git. Sample Question and Answer (QA) pairs and structured system prompts can be found in the Appendix.

[Arxiv](https://arxiv.org/abs/2507.20145)