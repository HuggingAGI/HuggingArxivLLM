# 迈向统一的多模态感知度量基准与模型

发布时间：2024年12月13日

`LLM应用

理由：这篇论文主要讨论了通用视觉-语言模型（如CLIP和大型多模态模型LMMs）在多模态感知相似性任务中的应用，并提出了一个新的基准UniSim-Bench来评估这些模型的表现。虽然论文涉及多模态模型，但其核心是探讨这些模型在特定任务中的应用和性能，因此归类为LLM应用更为合适。` `计算机视觉`

> Towards Unified Benchmark and Models for Multi-Modal Perceptual Metrics

# 摘要

> 人类对单模态和多模态输入的相似性感知极为复杂，开发能精准模拟这种感知的自动化指标颇具挑战。通用视觉-语言模型（如CLIP和大型多模态模型LMMs）可作为零-shot感知指标，近期研究也开发了专攻特定感知任务的模型。然而，现有感知指标与人类感知的一致性仍不明确。为此，我们推出了UniSim-Bench基准，涵盖7个多模态感知相似性任务，共25个数据集。评估显示，通用模型平均表现尚可，但在个别任务上常不及专门模型；而针对特定任务微调的指标在相关但未见任务上泛化能力欠佳。作为迈向统一多任务感知相似性指标的第一步，我们在UniSim-Bench任务子集上微调了基于编码器和生成的视觉-语言模型，取得了最高平均性能，某些情况下甚至超越任务特定模型。然而，这些模型在泛化到未见任务时仍显吃力，凸显了学习一个能捕捉人类相似性概念的鲁棒统一感知相似性指标的持续挑战。代码和模型已开源，详见https://github.com/SaraGhazanfari/UniSim。

> Human perception of similarity across uni- and multimodal inputs is highly complex, making it challenging to develop automated metrics that accurately mimic it. General purpose vision-language models, such as CLIP and large multi-modal models (LMMs), can be applied as zero-shot perceptual metrics, and several recent works have developed models specialized in narrow perceptual tasks. However, the extent to which existing perceptual metrics align with human perception remains unclear. To investigate this question, we introduce UniSim-Bench, a benchmark encompassing 7 multi-modal perceptual similarity tasks, with a total of 25 datasets. Our evaluation reveals that while general-purpose models perform reasonably well on average, they often lag behind specialized models on individual tasks. Conversely, metrics fine-tuned for specific tasks fail to generalize well to unseen, though related, tasks. As a first step towards a unified multi-task perceptual similarity metric, we fine-tune both encoder-based and generative vision-language models on a subset of the UniSim-Bench tasks. This approach yields the highest average performance, and in some cases, even surpasses taskspecific models. Nevertheless, these models still struggle with generalization to unseen tasks, highlighting the ongoing challenge of learning a robust, unified perceptual similarity metric capable of capturing the human notion of similarity. The code and models are available at https://github.com/SaraGhazanfari/UniSim.

[Arxiv](https://arxiv.org/abs/2412.10594)