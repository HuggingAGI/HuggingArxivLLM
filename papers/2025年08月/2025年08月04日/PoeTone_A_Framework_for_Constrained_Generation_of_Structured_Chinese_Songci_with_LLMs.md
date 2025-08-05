# PoeTone：基于大型语言模型的结构化中文宋词生成框架

发布时间：2025年08月04日

`LLM应用` `人工智能`

> PoeTone: A Framework for Constrained Generation of Structured Chinese Songci with LLMs

# 摘要

> 本文系统研究了大型语言模型（LLMs）生成宋词的能力。宋词是一种结构、声调和韵律均受严格约束的古典中国诗歌形式，其规范由词牌模板定义。我们开发了一个全面的多维评估框架，包含四个关键部分：形式符合度评分、基于LLMs的自动质量评估、人工评估以及分类探查任务。通过这一框架，我们在零样本、一样本、基于补全、指令微调和链式思维五种提示策略下，评估了18个LLMs的生成性能，其中包括3个专有模型和15个开源模型。最终，我们提出了一个Generate-Critic架构，其中评估框架作为自动化批评者发挥作用。利用批评者的反馈作为奖励信号，我们对三个轻量级开源LLMs进行了监督微调（SFT），使形式符合度提升了5.88%。我们的研究为理解LLMs在生成具有文化意义和形式约束的文学文本方面的优势与局限性提供了新视角。

> This paper presents a systematic investigation into the constrained generation capabilities of large language models (LLMs) in producing Songci, a classical Chinese poetry form characterized by strict structural, tonal, and rhyme constraints defined by Cipai templates. We first develop a comprehensive, multi-faceted evaluation framework that includes: (i) a formal conformity score, (ii) automated quality assessment using LLMs, (iii) human evaluation, and (iv) classification-based probing tasks. Using this framework, we evaluate the generative performance of 18 LLMs, including 3 proprietary models and 15 open-source models across four families, under five prompting strategies: zero-shot, one-shot, completion-based, instruction-tuned, and chain-of-thought. Finally, we propose a Generate-Critic architecture in which the evaluation framework functions as an automated critic. Leveraging the critic's feedback as a reward signal, we fine-tune three lightweight open-source LLMs via supervised fine-tuning (SFT), resulting in improvements of up to 5.88% in formal conformity. Our findings offer new insights into the generative strengths and limitations of LLMs in producing culturally significant and formally constrained literary texts.

[Arxiv](https://arxiv.org/abs/2508.02515)