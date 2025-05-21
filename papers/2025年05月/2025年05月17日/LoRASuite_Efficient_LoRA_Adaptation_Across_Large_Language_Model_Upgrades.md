# # LoRASuite：跨大型语言模型升级的高效LoRA适配方案

发布时间：2025年05月17日

`LLM应用`

> LoRASuite: Efficient LoRA Adaptation Across Large Language Model Upgrades

# 摘要

> 大型语言模型（LLMs）更新频繁，导致基于早期版本训练的LoRA权重迅速过时。传统的从零开始在最新模型上重新训练LoRA权重的做法不仅成本高昂、耗时，而且对环境有害，尤其是在LLMs多样性和下游任务不断扩展的背景下。这促使我们提出一个关键问题：“如何高效利用现有LoRA权重以适应新模型版本？”为解决这一问题，我们提出了LoRASuite，一种专门针对各种类型LLMs更新的模块化方法。

首先，我们利用旧版和新版LLMs的已知参数计算转移矩阵。然后，我们分别基于中心核对齐和余弦相似度指标分配相应的层和注意力头。随后，我们进行小规模的精细微调以确保数值稳定性。实验评估表明，LoRASuite始终超越小规模的标准LoRA方法。值得注意的是，在MiniCPM和Qwen等主干LLMs上，LoRASuite甚至超越了全规模LoRA重新训练的性能，分别在数学任务上平均提升了+1.4和+6.6个百分点。此外，LoRASuite显著降低了内存消耗（减少5.5 GB）和计算时间（减少78.23%）。

> As Large Language Models (LLMs) are frequently updated, LoRA weights trained on earlier versions quickly become obsolete. The conventional practice of retraining LoRA weights from scratch on the latest model is costly, time-consuming, and environmentally detrimental, particularly as the diversity of LLMs and downstream tasks expands. This motivates a critical question: "How can we efficiently leverage existing LoRA weights to adapt to newer model versions?" To address this, we propose LoRASuite, a modular approach tailored specifically to various types of LLM updates. First, we compute a transfer matrix utilizing known parameters from both old and new LLMs. Next, we allocate corresponding layers and attention heads based on centered kernel alignment and cosine similarity metrics, respectively. A subsequent small-scale, skillful fine-tuning step ensures numerical stability. Experimental evaluations demonstrate that LoRASuite consistently surpasses small-scale vanilla LoRA methods. Notably, on backbone LLMs such as MiniCPM and Qwen, LoRASuite even exceeds the performance of full-scale LoRA retraining, with average improvements of +1.4 and +6.6 points on math tasks, respectively. Additionally, LoRASuite significantly reduces memory consumption by 5.5 GB and computational time by 78.23%.

[Arxiv](https://arxiv.org/abs/2505.13515)