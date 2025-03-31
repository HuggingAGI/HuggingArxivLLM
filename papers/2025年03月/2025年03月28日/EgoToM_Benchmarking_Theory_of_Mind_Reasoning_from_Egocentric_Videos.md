# EgoToM：基于自我中心视角的视频进行心智理论推理的基准测试

发布时间：2025年03月28日

`LLM应用

摘要中提到的论文主要探讨了多模态大语言模型在视频问答任务中的应用，特别是评估其在自我中心视角下的推理能力。这属于将大型语言模型应用于特定任务的范畴，因此归类为LLM应用。` `视频问答` `数字助手`

> EgoToM: Benchmarking Theory of Mind Reasoning from Egocentric Videos

# 摘要

> 我们推出EgoToM——一个全新的视频问答基准，将心智理论（ToM）评估拓展至自我中心领域。借助因果ToM模型，我们为Ego4D数据集创建了多选视频问答实例，用于评估预测摄像头佩戴者目标、信念及下一步动作的能力。我们对比了人类与当前最先进的多模态大语言模型（MLLMs）在这三大相互关联推理任务中的表现。评估结果显示，MLLMs在从自我中心视角视频中推断目标方面已接近人类水平。然而，在预测摄像头佩戴者即时信念状态及未来动作（这些动作最符合未见视频未来）时，MLLMs（包括我们测试的1000亿参数规模的大型模型）仍无法匹敌人类表现。我们坚信，这些研究发现将为未来设计一类关键的自我中心数字助手提供重要参考，这些助手将内置一个合理的人类内部心理状态模型。

> We introduce EgoToM, a new video question-answering benchmark that extends Theory-of-Mind (ToM) evaluation to egocentric domains. Using a causal ToM model, we generate multi-choice video QA instances for the Ego4D dataset to benchmark the ability to predict a camera wearer's goals, beliefs, and next actions. We study the performance of both humans and state of the art multimodal large language models (MLLMs) on these three interconnected inference problems. Our evaluation shows that MLLMs achieve close to human-level accuracy on inferring goals from egocentric videos. However, MLLMs (including the largest ones we tested with over 100B parameters) fall short of human performance when inferring the camera wearers' in-the-moment belief states and future actions that are most consistent with the unseen video future. We believe that our results will shape the future design of an important class of egocentric digital assistants which are equipped with a reasonable model of the user's internal mental states.

[Arxiv](https://arxiv.org/abs/2503.22152)