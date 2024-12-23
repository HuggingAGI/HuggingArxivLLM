# 解析用于语言模型微调的推理标记和样板标记

发布时间：2024年12月19日

`Agent` `语言模型` `人工智能`

> Disentangling Reasoning Tokens and Boilerplate Tokens For Language Model Fine-tuning

# 摘要

> 在使用代理任务数据集增强大型语言模型（LLMs）的代理能力时，当下的方法往往对样本内的所有标记同等对待。然而，我们指出，发挥不同作用的标记——具体来说，推理标记与样板标记（比如控制输出格式的那些）——在重要性和学习复杂度上差异显著，所以需要将它们分开处理。为解决此问题，我们提出了一种新颖的洗牌感知鉴别器（SHAD）用于自适应标记鉴别。SHAD利用在样本间打乱输入 - 输出组合后观察到的可预测性差异来对标记进行分类：样板标记由于在样本间具有重复性，所以保持了可预测性，而推理标记并非如此。借助SHAD，我们提出了推理突出微调（RFT）方法，该方法在微调过程中自适应地侧重推理标记，相比常见的监督微调（SFT），性能有了显著提升。

> When using agent-task datasets to enhance agent capabilities for Large Language Models (LLMs), current methodologies often treat all tokens within a sample equally. However, we argue that tokens serving different roles - specifically, reasoning tokens versus boilerplate tokens (e.g., those governing output format) - differ significantly in importance and learning complexity, necessitating their disentanglement and distinct treatment. To address this, we propose a novel Shuffle-Aware Discriminator (SHAD) for adaptive token discrimination. SHAD classifies tokens by exploiting predictability differences observed after shuffling input-output combinations across samples: boilerplate tokens, due to their repetitive nature among samples, maintain predictability, whereas reasoning tokens do not. Using SHAD, we propose the Reasoning-highlighted Fine-Tuning (RFT) method, which adaptively emphasizes reasoning tokens during fine-tuning, yielding notable performance gains over common Supervised Fine-Tuning (SFT).

[Arxiv](https://arxiv.org/abs/2412.14780)