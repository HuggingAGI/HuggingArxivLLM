# DisTime：为视频大型语言模型提供基于分布的时间表示方法

发布时间：2025年05月30日

`LLM应用` `视频分析` `视频问答`

> DisTime: Distribution-based Time Representation for Video Large Language Models

# 摘要

> 尽管在通用视频理解领域取得了进展，视频大语言模型（Video-LLMs）在时间定位方面仍面临挑战，主要源于离散的时间表示和有限的时间感知数据集。现有的时间表达方法存在以下问题：要么将时间与基于文本的数值混为一谈，要么添加一系列专用时间标记，或者使用专门的时间定位头部来回归时间。为了解决这些问题，我们提出了DisTime——一个轻量级框架，旨在增强Video-LLMs的时间理解能力。

DisTime通过可学习标记创建连续的时间嵌入空间，并引入基于分布的时间解码器，生成时间概率分布，有效缓解边界模糊问题，同时保持时间连续性。此外，基于分布的时间编码器重新编码时间戳，为Video-LLMs提供时间标记。为克服现有数据集在时间粒度上的限制，我们提出了一种创新的自动化标注范式，结合Video-LLMs的字幕生成能力和专用时间模型的定位专业知识。

这一范式催生了InternVid-TG——一个包含17.9万个视频中125万个基于时间的事件的大型数据集，其规模是ActivityNet-Caption的55倍。大量实验表明，DisTime在三个时间敏感任务的基准测试中达到了最先进的性能水平，同时在Video QA任务中也保持了极具竞争力的表现。代码和数据已开源，地址为https://github.com/josephzpng/DisTime。

> Despite advances in general video understanding, Video Large Language Models (Video-LLMs) face challenges in precise temporal localization due to discrete time representations and limited temporally aware datasets. Existing methods for temporal expression either conflate time with text-based numerical values, add a series of dedicated temporal tokens, or regress time using specialized temporal grounding heads. To address these issues, we introduce DisTime, a lightweight framework designed to enhance temporal comprehension in Video-LLMs. DisTime employs a learnable token to create a continuous temporal embedding space and incorporates a Distribution-based Time Decoder that generates temporal probability distributions, effectively mitigating boundary ambiguities and maintaining temporal continuity. Additionally, the Distribution-based Time Encoder re-encodes timestamps to provide time markers for Video-LLMs. To overcome temporal granularity limitations in existing datasets, we propose an automated annotation paradigm that combines the captioning capabilities of Video-LLMs with the localization expertise of dedicated temporal models. This leads to the creation of InternVid-TG, a substantial dataset with 1.25M temporally grounded events across 179k videos, surpassing ActivityNet-Caption by 55 times. Extensive experiments demonstrate that DisTime achieves state-of-the-art performance across benchmarks in three time-sensitive tasks while maintaining competitive performance in Video QA tasks. Code and data are released at https://github.com/josephzpng/DisTime.

[Arxiv](https://arxiv.org/abs/2505.24329)