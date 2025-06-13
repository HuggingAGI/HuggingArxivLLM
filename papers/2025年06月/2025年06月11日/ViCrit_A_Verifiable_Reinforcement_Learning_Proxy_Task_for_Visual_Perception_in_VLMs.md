# ViCrit：面向视觉语言模型视觉感知的可验证强化学习代理任务

发布时间：2025年06月11日

`其他` `计算机视觉` `图像处理`

> ViCrit: A Verifiable Reinforcement Learning Proxy Task for Visual Perception in VLMs

# 摘要

> 强化学习（RL）在微调大型语言模型（LLMs）方面表现出显著效果，尤其在数学推理或代码生成等具有挑战性且易于验证的任务中。然而，将其成功扩展到视觉语言模型（VLMs）的视觉感知领域却受到限制，因为缺乏同时具有挑战性和明确可验证性的视觉中心任务。为解决这一问题，我们提出了ViCrit（视觉描述幻觉批评），一个RL代理任务，旨在训练VLMs定位注入到人类编写图像描述段落中的细微、合成视觉幻觉。从200字的描述开始，我们在物体、属性、计数或空间关系上注入一个细微的视觉描述错误（修改几个单词），并要求模型在给定图像和修改后的描述时定位出受损的文本片段。这种设定保留了全部感知难度，同时提供了一个易于计算且明确的二进制精确匹配奖励。通过ViCrit任务训练的模型在各种VL基准测试中表现出显著提升。更重要的是，这些改进不仅限于自然图像训练数据，还扩展到抽象图像推理和视觉数学，展示了学习感知而非仅仅记忆已见对象的潜力。为了便于评估，我们进一步引入了ViCrit-Bench，这是一个类别平衡的诊断基准测试，系统性地探究了不同图像领域和错误类型中的感知错误。综上所述，我们的结果表明，精细的幻觉批评是增强VLM视觉感知的有效且通用目标。

> Reinforcement learning (RL) has shown great effectiveness for fine-tuning large language models (LLMs) using tasks that are challenging yet easily verifiable, such as math reasoning or code generation. However, extending this success to visual perception in vision-language models (VLMs) has been impeded by the scarcity of vision-centric tasks that are simultaneously challenging and unambiguously verifiable. To this end, we introduce ViCrit (Visual Caption Hallucination Critic), an RL proxy task that trains VLMs to localize a subtle, synthetic visual hallucination injected into paragraphs of human-written image captions. Starting from a 200-word captions, we inject a single, subtle visual description error-altering a few words on objects, attributes, counts, or spatial relations-and task the model to pinpoint the corrupted span given the image and the modified caption. This formulation preserves the full perceptual difficulty while providing a binary, exact-match reward that is easy to compute and unambiguous. Models trained with the ViCrit Task exhibit substantial gains across a variety of VL benchmarks. Crucially, the improvements transfer beyond natural-image training data to abstract image reasoning and visual math, showing promises of learning to perceive rather than barely memorizing seen objects. To facilitate evaluation, we further introduce ViCrit-Bench, a category-balanced diagnostic benchmark that systematically probes perception errors across diverse image domains and error types. Together, our results demonstrate that fine-grained hallucination criticism is an effective and generalizable objective for enhancing visual perception in VLMs.

[Arxiv](https://arxiv.org/abs/2506.10128)