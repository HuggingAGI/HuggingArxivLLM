# 跳过一层还是循环处理？预训练 LLM 在推理阶段的深度适配研究

发布时间：2025年07月10日

`LLM理论

这篇论文探讨了大型语言模型（LLM）的各层结构及其在不同任务中的适应性，提出了通过拆解和重组模型层来优化推理过程的方法。研究涉及模型结构的理论分析和优化策略，属于LLM理论的范畴。` `人工智能`

> Skip a Layer or Loop it? Test-Time Depth Adaptation of Pretrained LLMs

# 摘要

> 预训练神经网络是否需要微调才能适应不同输入？简单任务是否需要全部层？这些层是否足够应对复杂任务？我们发现，预训练大型语言模型（LLM）的各层可以灵活拆解重组，为每个测试样本定制一个更优甚至更浅的模型。具体来说，可以跳过或剪裁单层，或将某层重复多次形成循环神经网络（RNN），与其他层任意堆叠，从而为每个样本构建独特的层链（CoLa）。这种组合方式大大拓展了现有循环/预训练模块、层剪裁和早退网络的研究边界。我们开发的蒙特卡洛树搜索（MCTS）协议能为数学和常识推理基准测试中的每个样本找到最优CoLa。相比固定深度的静态模型，CoLa支持快速捷径（快思考）、层循环（慢思考），以及两者的结合，为不同输入提供更灵活多变的架构。通过全面分析MCTS优化的CoLa，我们获得两个重要发现：（1）对于原始模型正确预测的>75%样本，我们能找到更短的CoLa，表明推理效率提升的巨大空间；（2）对于原始模型预测错误的>60%样本，我们能识别出实现正确预测的CoLa，表明性能提升的广阔潜力。我们的研究揭示了固定架构预训练模型在不同样本推理中的局限性，为解锁测试时深度自适应的泛化能力指明了方向。

> Can a pretrained neural network adapt its architecture to different inputs without any finetuning? Do we need all layers for simple tasks, and are they adequate for challenging tasks? We found that the layers of a pretrained large language model (LLM) can be manipulated as separate modules to build a better and even shallower model customized for each test sample. In particular, each layer from the pretrained model can be skipped/pruned or repeated multiple times as recurrent neural networks (RNN), and stacked with others in arbitrary orders, yielding a chain-of-layers (CoLa) per sample. This compositional space greatly expands the scope of existing works on looped/recurrent pretrained modules, layer pruning, or early-exit networks. We develop a Monte Carlo Tree Search (MCTS) protocol to explore and identify the optimal CoLa for each sample from math and commonsense reasoning benchmarks. Compared to a static model of a fixed depth, CoLa allows shortcut paths (fast thinking), recurrence of the same layer(s) (slow thinking), and combining both, offering more flexible, dynamic architectures for different inputs. We conduct an extensive analysis of the MCTS-optimized CoLa, which leads to two key findings: (1) For >75% of samples with correct predictions by the original LLM, we can find shorter CoLa, suggesting a large space for improving inference efficiency; (2) For >60% of samples with originally incorrect predictions, we can identify CoLa achieving correct predictions, suggesting a large space of performance enhancement. Our results highlight the shortcomings of using a fixed architecture of pre-trained LLMs for inference on different samples and pave the way to unlock the generalization power of test-time depth adaptation.

[Arxiv](https://arxiv.org/abs/2507.07996)