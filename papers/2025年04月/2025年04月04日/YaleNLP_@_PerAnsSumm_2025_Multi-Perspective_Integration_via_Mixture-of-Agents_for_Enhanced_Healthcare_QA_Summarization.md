# YaleNLP @ PerAnsSumm 2025：采用多智能体混合方法进行多视角整合，提升医疗问答摘要效果。

发布时间：2025年04月04日

`LLM应用

理由：这篇论文主要探讨了如何利用大语言模型（LLM）在医疗问答论坛中进行自动摘要的任务，特别是面对多角度回答的挑战。研究采用了QLoRA微调方法和智能体驱动的多模态方法，这些都是LLM的具体应用。实验结果展示了LLM在特定任务中的表现和优化方法，属于LLM的应用研究。` `问答系统`

> YaleNLP @ PerAnsSumm 2025: Multi-Perspective Integration via Mixture-of-Agents for Enhanced Healthcare QA Summarization

# 摘要

> 医疗问答论坛的自动摘要：多角度回答带来的挑战
医疗问答论坛的自动摘要任务面临一个核心挑战——每个问题往往伴随着多篇回答，每篇回答都可能从不同的视角进行阐述。为了解决这一难题，我们提出了PerAnsSumm共享任务，旨在从不同答案中提取多元视角，并生成对问题的全面解答。本研究采用了两种互补的方法来应对这一挑战：

1. 基于训练的QLoRA微调方法：我们对LLaMA-3.3-70B-Instruct进行了QLoRA微调，以提升模型在视角识别任务中的表现。
2. 智能体驱动的多模态方法：我们采用了前沿LLMs（LLaMA-3.3-70B-Instruct和GPT-4o）的零样本与少样本提示策略，并开发了一种混合智能体（MoA）框架，通过多层反馈聚合实现了更优的性能。

实验结果表明：
- 在视角跨度识别/分类任务中，GPT-4o零样本提示达到了0.57的总体得分，远超LLaMA基线的0.40。
- 通过两层MoA配置，我们成功将LLaMA的表现提升了28%至0.51。
- 在基于视角的摘要任务中，GPT-4o零样本提示获得了0.42的总体得分，优于LLaMA零样本的0.28。
- 我们的两层MoA方法使LLaMA的表现提升了32%至0.37。

此外，我们在少样本设置下的研究发现，基于句子转换器嵌入的示例选择比手动选择的示例对LLaMA模型更有帮助，尽管对于GPT-4o来说，少样本提示并不总是有效。最终，YaleNLP团队的方法在共享任务中总体排名第二。

> Automated summarization of healthcare community question-answering forums is challenging due to diverse perspectives presented across multiple user responses to each question. The PerAnsSumm Shared Task was therefore proposed to tackle this challenge by identifying perspectives from different answers and then generating a comprehensive answer to the question. In this study, we address the PerAnsSumm Shared Task using two complementary paradigms: (i) a training-based approach through QLoRA fine-tuning of LLaMA-3.3-70B-Instruct, and (ii) agentic approaches including zero- and few-shot prompting with frontier LLMs (LLaMA-3.3-70B-Instruct and GPT-4o) and a Mixture-of-Agents (MoA) framework that leverages a diverse set of LLMs by combining outputs from multi-layer feedback aggregation. For perspective span identification/classification, GPT-4o zero-shot achieves an overall score of 0.57, substantially outperforming the 0.40 score of the LLaMA baseline. With a 2-layer MoA configuration, we were able to improve LLaMA performance up by 28 percent to 0.51. For perspective-based summarization, GPT-4o zero-shot attains an overall score of 0.42 compared to 0.28 for the best LLaMA zero-shot, and our 2-layer MoA approach boosts LLaMA performance by 32 percent to 0.37. Furthermore, in few-shot setting, our results show that the sentence-transformer embedding-based exemplar selection provides more gain than manually selected exemplars on LLaMA models, although the few-shot prompting is not always helpful for GPT-4o. The YaleNLP team's approach ranked the overall second place in the shared task.

[Arxiv](https://arxiv.org/abs/2504.03932)