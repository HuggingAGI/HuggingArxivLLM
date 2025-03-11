# # 多链式思维在对比推理中的隐式情感分析应用

发布时间：2025年03月10日

`LLM应用

理由：这篇论文探讨了大型语言模型在隐式情感分析中的应用，提出了一种创新的推理框架来提升情感分析的效果。研究重点在于如何利用LLM进行情感分析，属于应用层面的创新。` `情感分析`

> Application of Multiple Chain-of-Thought in Contrastive Reasoning for Implicit Sentiment Analysis

# 摘要

> 隐式情感分析致力于挖掘那些隐藏在模糊和隐喻语言中的微妙情感。为了实现这一目标，需要借助大型语言模型和多步推理来识别那些未明确表达的情感。本研究提出了一种创新的双逆向链式推理框架（DRCR），以提升隐式情感分析的效果。该框架受演绎推理启发，包含三个核心步骤：1) 假设一种情感倾向并推导出推理过程，2) 否定初始假设并推导出新的推理过程，3) 对比两种推理路径以确定最终的情感倾向。在此基础上，我们还引入了三重逆向链式推理框架（TRCR），以克服随机假设的局限性。这两种方法巧妙结合了对比机制与多步推理，显著提升了隐式情感分类的准确性。实验结果表明，这两种方法在不同规模的模型上均超越了现有方法，达到了当前最优的性能水平。这充分验证了将对比推理与多步推理相结合在隐式情感分析中的有效性。

> Implicit sentiment analysis aims to uncover emotions that are subtly expressed, often obscured by ambiguity and figurative language. To accomplish this task, large language models and multi-step reasoning are needed to identify those sentiments that are not explicitly stated. In this study, we propose a novel Dual Reverse Chain Reasoning (DRCR) framework to enhance the performance of implicit sentiment analysis. Inspired by deductive reasoning, the framework consists of three key steps: 1) hypothesize an emotional polarity and derive a reasoning process, 2) negate the initial hypothesis and derive a new reasoning process, and 3) contrast the two reasoning paths to deduce the final sentiment polarity. Building on this, we also introduce a Triple Reverse Chain Reasoning (TRCR) framework to address the limitations of random hypotheses. Both methods combine contrastive mechanisms and multi-step reasoning, significantly improving the accuracy of implicit sentiment classification. Experimental results demonstrate that both approaches outperform existing methods across various model scales, achieving state-of-the-art performance. This validates the effectiveness of combining contrastive reasoning and multi-step reasoning for implicit sentiment analysis.

[Arxiv](https://arxiv.org/abs/2503.07140)