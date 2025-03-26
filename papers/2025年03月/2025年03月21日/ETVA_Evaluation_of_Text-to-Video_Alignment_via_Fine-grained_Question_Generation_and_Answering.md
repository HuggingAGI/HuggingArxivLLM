# ETVA: 基于细粒度问题生成与回答的文本到视频对齐评估

发布时间：2025年03月21日

`LLM应用` `视频生成` `评估方法`

> ETVA: Evaluation of Text-to-Video Alignment via Fine-grained Question Generation and Answering

# 摘要

> 在文本到视频（T2V）生成领域，准确评估文本提示与生成视频之间的语义对齐仍是一个难题。现有的文本到视频对齐指标如CLIPScore仅生成粗粒度分数，缺乏细粒度的对齐细节，无法与人类偏好对齐。为了解决这一问题，我们提出ETVA，一种通过细粒度问题生成和回答来评估文本到视频对齐的新颖方法。首先，一个多智能体系统将提示解析为语义场景图以生成原子问题。然后，我们设计了一个知识增强的多阶段推理框架用于问题回答：辅助LLM首先检索相关常识（如物理定律），视频LLM再通过多阶段推理机制回答生成的问题。实验结果表明，ETVA实现了58.47的Spearman相关系数，与人类判断的相关性远高于现有指标（31.0）。我们还构建了一个专门用于文本到视频对齐评估的综合基准，包含2000个多样化提示和12000个原子问题，涵盖10个类别。通过对现有15个文本到视频模型的系统评估，我们识别出它们的关键能力和局限性，为下一代T2V生成铺平了道路。

> Precisely evaluating semantic alignment between text prompts and generated videos remains a challenge in Text-to-Video (T2V) Generation. Existing text-to-video alignment metrics like CLIPScore only generate coarse-grained scores without fine-grained alignment details, failing to align with human preference. To address this limitation, we propose ETVA, a novel Evaluation method of Text-to-Video Alignment via fine-grained question generation and answering. First, a multi-agent system parses prompts into semantic scene graphs to generate atomic questions. Then we design a knowledge-augmented multi-stage reasoning framework for question answering, where an auxiliary LLM first retrieves relevant common-sense knowledge (e.g., physical laws), and then video LLM answers the generated questions through a multi-stage reasoning mechanism. Extensive experiments demonstrate that ETVA achieves a Spearman's correlation coefficient of 58.47, showing a much higher correlation with human judgment than existing metrics which attain only 31.0. We also construct a comprehensive benchmark specifically designed for text-to-video alignment evaluation, featuring 2k diverse prompts and 12k atomic questions spanning 10 categories. Through a systematic evaluation of 15 existing text-to-video models, we identify their key capabilities and limitations, paving the way for next-generation T2V generation.

[Arxiv](https://arxiv.org/abs/2503.16867)