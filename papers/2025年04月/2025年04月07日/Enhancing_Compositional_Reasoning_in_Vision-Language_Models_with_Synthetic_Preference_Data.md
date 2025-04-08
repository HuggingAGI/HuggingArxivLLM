# 利用合成偏好数据提升视觉-语言模型的组合推理能力

发布时间：2025年04月07日

`LLM应用` `视觉语言处理`

> Enhancing Compositional Reasoning in Vision-Language Models with Synthetic Preference Data

# 摘要

> 组合性，也就是正确识别场景为原子视觉概念的组合，仍是多模态大型语言模型 (MLLMs) 的一大挑战。即使是像 GPT-4o 这样的先进模型，在区分“狗追猫”与“猫追狗”等组合关系时仍会出错。尽管在 Winoground 这一衡量推理能力的基准测试中，MLLMs 已取得显著进展，但与人类表现仍有很大差距。

我们发现，通过数据阐明这些概念可以提升模型的组合推理能力。具体来说，训练模型偏好为图像选择正确的描述而非相似但错误的描述。为此，我们提出了 SCRAMBLe：一种通过二元偏好学习增强 MLLMs 组合推理能力的方法。该方法利用从现有图像-描述数据中完全自动化生成的合成偏好数据，对开源权重的 MLLMs 进行偏好微调。

SCRAMBLe 全面提升了 MLLMs 的组合推理能力。这一点在多个视觉语言组合性基准测试中得到了显著改善，并在更广泛的视觉问答任务中也实现了较小但显著的提升。作为抢先预览，SCRAMBLe 微调后的 Molmo-7B 模型在 Winoground 上的表现从 49.5% 提升至 54.8%（目前报告的最佳成绩），同时在更通用的视觉问答任务上提升了约 1%。

SCRAMBLe 的代码、微调后的模型以及我们的合成训练数据集均可在 https://github.com/samarth4149/SCRAMBLe 获取。

> Compositionality, or correctly recognizing scenes as compositions of atomic visual concepts, remains difficult for multimodal large language models (MLLMs). Even state of the art MLLMs such as GPT-4o can make mistakes in distinguishing compositions like "dog chasing cat" vs "cat chasing dog". While on Winoground, a benchmark for measuring such reasoning, MLLMs have made significant progress, they are still far from a human's performance. We show that compositional reasoning in these models can be improved by elucidating such concepts via data, where a model is trained to prefer the correct caption for an image over a close but incorrect one. We introduce SCRAMBLe: Synthetic Compositional Reasoning Augmentation of MLLMs with Binary preference Learning, an approach for preference tuning open-weight MLLMs on synthetic preference data generated in a fully automated manner from existing image-caption data. SCRAMBLe holistically improves these MLLMs' compositional reasoning capabilities which we can see through significant improvements across multiple vision language compositionality benchmarks, as well as smaller but significant improvements on general question answering tasks. As a sneak peek, SCRAMBLe tuned Molmo-7B model improves on Winoground from 49.5% to 54.8% (best reported to date), while improving by ~1% on more general visual question answering tasks. Code for SCRAMBLe along with tuned models and our synthetic training dataset is available at https://github.com/samarth4149/SCRAMBLe.

[Arxiv](https://arxiv.org/abs/2504.04740)