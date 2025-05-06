# LecEval：用于评估多媒体学习中多模态知识获取的自动化指标

发布时间：2025年05月04日

`LLM应用` `评估系统`

> LecEval: An Automated Metric for Multimodal Knowledge Acquisition in Multimedia Learning

# 摘要

> 评估基于幻灯片的多媒体教学效果充满挑战。现有方法如人工评估、基于参考的指标以及大型语言模型评估器在可扩展性、上下文捕捉或偏见方面存在局限性。本文中，我们引入了LecEval，一种基于梅耶认知多媒体学习理论的自动化指标，用于评估基于幻灯片学习中的多模态知识获取。LecEval通过四个评估标准来衡量效果：内容相关性（CR）、表达清晰度（EC）、逻辑结构（LS）以及观众参与度（AE）。我们构建了一个包含50多个在线课程视频的大型数据集，其中超过2,000张幻灯片，每张幻灯片都标注了细致的人工评分。在该数据集上训练的模型相较于现有指标展现了更优的准确性和适应性，缩小了自动化评估与人工评估之间的差距。我们已在https://github.com/JoylimJY/LecEval开放了我们的数据集和工具包。


> Evaluating the quality of slide-based multimedia instruction is challenging. Existing methods like manual assessment, reference-based metrics, and large language model evaluators face limitations in scalability, context capture, or bias. In this paper, we introduce LecEval, an automated metric grounded in Mayer's Cognitive Theory of Multimedia Learning, to evaluate multimodal knowledge acquisition in slide-based learning. LecEval assesses effectiveness using four rubrics: Content Relevance (CR), Expressive Clarity (EC), Logical Structure (LS), and Audience Engagement (AE). We curate a large-scale dataset of over 2,000 slides from more than 50 online course videos, annotated with fine-grained human ratings across these rubrics. A model trained on this dataset demonstrates superior accuracy and adaptability compared to existing metrics, bridging the gap between automated and human assessments. We release our dataset and toolkits at https://github.com/JoylimJY/LecEval.

[Arxiv](https://arxiv.org/abs/2505.02078)