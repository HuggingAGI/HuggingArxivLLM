# LIFT：基于LLM的Pragma插入，通过GNN监督微调实现HLS

发布时间：2025年04月29日

`LLM应用` `数据中心` `硬件设计`

> LIFT: LLM-Based Pragma Insertion for HLS via GNN Supervised Fine-Tuning

# 摘要

> FPGAs凭借其可重构性和高能效，正迅速成为数据中心环境中的热门选择。高级综合（HLS）工具通过将抽象层次从RTL提升到无时序的C/C++，显著降低了FPGA编程的门槛。然而，实现高性能仍需专家介入，通过手动反复插入优化pragma来调整微架构。为解决这一难题，我们推出了LIFT——一款基于大型语言模型（LLM）的HLS编码助手，它能够根据C/C++设计自动生成性能关键的pragma。我们采用了一种创新的微调方法，将图神经网络（GNN）与LLM训练过程紧密结合，并施加监督学习。这种方法巧妙地融合了LLMs在序列建模方面的优势，以及GNNs在代码及其控制/数据依赖关系上的结构和语义理解能力，从而实现高效推理。实验结果表明，LIFT的表现远超现有技术：与AutoDSE和HARP相比，性能分别提升了3.52倍和2.16倍，更是达到了GPT-4的66倍。

> FPGAs are increasingly adopted in datacenter environments for their reconfigurability and energy efficiency. High-Level Synthesis (HLS) tools have eased FPGA programming by raising the abstraction level from RTL to untimed C/C++, yet attaining high performance still demands expert knowledge and iterative manual insertion of optimization pragmas to modify the microarchitecture. To address this challenge, we propose LIFT, a large language model (LLM)-based coding assistant for HLS that automatically generates performance-critical pragmas given a C/C++ design. We fine-tune the LLM by tightly integrating and supervising the training process with a graph neural network (GNN), combining the sequential modeling capabilities of LLMs with the structural and semantic understanding of GNNs necessary for reasoning over code and its control/data dependencies. On average, LIFT produces designs that improve performance by 3.52x and 2.16x than prior state-of the art AutoDSE and HARP respectively, and 66x than GPT-4o.

[Arxiv](https://arxiv.org/abs/2504.21187)