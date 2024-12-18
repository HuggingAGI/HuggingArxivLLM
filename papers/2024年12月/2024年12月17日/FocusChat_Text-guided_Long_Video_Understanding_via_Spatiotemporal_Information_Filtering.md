# FocusChat：借助时空信息过滤达成文本引导的长视频理解

发布时间：2024年12月17日

`LLM应用` `多模态` `语言模型`

> FocusChat: Text-guided Long Video Understanding via Spatiotemporal Information Filtering

# 摘要

> 最近，多模态大型语言模型进展显著。然而，缺少用户意图引导的视觉信息，可能会在长且未修剪的视频中引发冗余计算和不必要的视觉噪声。为应对此问题，我们推出了 FocusChat，这是一款由文本引导的多模态大型语言模型（LLM），注重与用户提示相关的视觉信息。具体而言，我们的模型首先历经语义提取模块，其包含视觉语义分支和文本语义分支，分别用于提取图像和文本语义。这两个分支通过时空滤波模块（STFM）加以组合。STFM 可实现显性的空间级信息过滤和隐性的时间级特征过滤，保证视觉标记与用户的查询紧密契合。这降低了输入 LLM 的视觉标记的必要数量。FocusChat 在零样本实验中远超 Video-LLaMA，所用训练数据少一个量级，仅占用 16 个视觉标记。在少样本实验中，它仅用 0.72M 的预训练数据，就取得了可与最先进水平媲美的成果。

> Recently, multi-modal large language models have made significant progress. However, visual information lacking of guidance from the user's intention may lead to redundant computation and involve unnecessary visual noise, especially in long, untrimmed videos. To address this issue, we propose FocusChat, a text-guided multi-modal large language model (LLM) that emphasizes visual information correlated to the user's prompt. In detail, Our model first undergoes the semantic extraction module, which comprises a visual semantic branch and a text semantic branch to extract image and text semantics, respectively. The two branches are combined using the Spatial-Temporal Filtering Module (STFM). STFM enables explicit spatial-level information filtering and implicit temporal-level feature filtering, ensuring that the visual tokens are closely aligned with the user's query. It lowers the essential number of visual tokens inputted into the LLM. FocusChat significantly outperforms Video-LLaMA in zero-shot experiments, using an order of magnitude less training data with only 16 visual tokens occupied. It achieves results comparable to the state-of-the-art in few-shot experiments, with only 0.72M pre-training data.

[Arxiv](https://arxiv.org/abs/2412.12833)