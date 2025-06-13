# VideoDeepResearch：利用智能体工具进行长视频理解

发布时间：2025年06月12日

`Agent` `多媒体` `视频处理`

> VideoDeepResearch: Long Video Understanding With Agentic Tool Using

# 摘要

> 长视频理解（LVU）因其固有复杂性和上下文窗口限制，对当前多模态大语言模型（MLLMs）构成重大挑战。人们普遍认为，解决此类任务需要MLLM具备扩展上下文窗口、强大的视觉感知能力和专业知识。然而，我们提出了VideoDeepResearch，一个全新的智能体框架，彻底改变了这一认知。该框架仅依赖于纯文本推理模型（LRM），并结合现成的多模态工具包，包括检索器和视觉感知器。系统通过推理制定策略，并通过工具选择性利用关键视频内容。我们在MLVU、Video-MME和LVBench等基准测试中验证了这一方法，结果显示VideoDeepResearch分别在MLVU（测试集）、LVBench和LongVideoBench上超越现有最优方法9.6%、6.6%和3.9%。这证明了智能体系统在解决LVU问题中的巨大潜力。
    

> Long video understanding (LVU) presents a significant challenge for current multi-modal large language models (MLLMs) due to the task's inherent complexity and context window constraint. It is widely assumed that addressing LVU tasks requires foundation MLLMs with extended context windows, strong visual perception capabilities, and proficient domain expertise. In this work, we challenge this common belief by introducing VideoDeepResearch, a novel agentic framework for long video understanding. Our approach relies solely on a text-only large reasoning model (LRM) combined with a modular multi-modal toolkit, including multimodal retrievers and visual perceivers, all of which are readily available in practice. For each LVU task, the system formulates a problem-solving strategy through reasoning, while selectively accessing and utilizing essential video content via tool using. We conduct extensive experiments on popular LVU benchmarks, including MLVU, Video-MME, and LVBench. Our results demonstrate that VideoDeepResearch achieves substantial improvements over existing MLLM baselines, surpassing the previous state-of-the-art by 9.6%, 6.6%, and 3.9% on MLVU (test), LVBench, and LongVideoBench, respectively. These findings highlight the promise of agentic systems in overcoming key challenges in LVU problems.

[Arxiv](https://arxiv.org/abs/2506.10821)