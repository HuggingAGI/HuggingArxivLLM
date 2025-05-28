# SATORI-R1：通过空间定位和可验证奖励促进多模态推理

发布时间：2025年05月25日

`Agent

理由：这篇论文主要探讨了强化学习（RL）在多模态任务中的应用，特别是视觉问答（VQA）任务。虽然涉及LLM的应用，但核心是关于强化学习的方法和多模态任务的优化，因此归类为Agent。` `视觉问答` `计算机视觉`

> SATORI-R1: Incentivizing Multimodal Reasoning with Spatial Grounding and Verifiable Rewards

# 摘要

> DeepSeek-R1通过稳定的强化学习（RL）在文本领域展现了强大的推理能力。在多模态领域，已有研究开始尝试直接应用RL来生成类似R1的自由形式推理，用于视觉问答（VQA）任务。然而，多模态任务与文本任务在本质上存在显著差异，前者需要依赖对输入图像的理解来解决问题。因此，这种自由形式的推理在VQA任务中面临两大关键限制：（1）延长的推理链使视觉焦点偏离任务关键区域，从而降低答案准确性。（2）无法验证的中间步骤会加剧策略梯度的方差，并增加计算成本。为了解决这些问题，本文引入了SATORI（基于强化学习的空间锚定任务优化），将VQA分解为三个可验证的阶段：全局图像描述、区域定位和答案预测，每个阶段都提供明确的奖励信号。此外，我们还引入了VQA-Verify数据集，这是一个包含12,000个样本的标注数据集，提供与答案对齐的描述和边界框，以促进训练。实验结果表明，与类似R1的基线模型相比，我们的方法在七个VQA基准测试中实现了性能的一致提升，准确率最高提升了【数学公式】。对注意力图的分析证实了模型对关键区域的注意力增强，这带来了准确率的提升。我们的代码可在https://github.com/justairr/SATORI-R1获取。

> DeepSeek-R1 has demonstrated powerful reasoning capabilities in the text domain through stable reinforcement learning (RL). Recently, in the multimodal domain, works have begun to directly apply RL to generate R1-like free-form reasoning for Visual Question Answering (VQA) tasks. However, multimodal tasks share an intrinsically different nature from textual tasks, which heavily rely on the understanding of the input image to solve the problem. Therefore, such free-form reasoning faces two critical limitations in the VQA task: (1) Extended reasoning chains diffuse visual focus away from task-critical regions, degrading answer accuracy. (2) Unverifiable intermediate steps amplify policy-gradient variance and computational costs overhead. To address these issues, in this paper, we introduce SATORI ($\textbf{S}patially$ $\textbf{A}nchored$ $\textbf{T}ask$ $\textbf{O}ptimization$ with $\textbf{R}e\textbf{I}nforcement$ Learning), which decomposes VQA into three verifiable stages, including global image captioning, region localization, and answer prediction, each supplying explicit reward signals. Furthermore, we also introduce VQA-Verify, a 12k dataset annotated with answer-aligned captions and bounding-boxes to facilitate training. Experiments demonstrate consistent performance improvements across seven VQA benchmarks, achieving up to $15.7\%$ improvement in accuracy in accuracy compared to the R1-like baseline. Our analysis of the attention map confirms enhanced focus on critical regions, which brings improvements in accuracy. Our code is available at https://github.com/justairr/SATORI-R1.

[Arxiv](https://arxiv.org/abs/2505.19094)