# 关于大型语言模型的 AI 生成文本检测器的实际考察

发布时间：2024年12月06日

`LLM应用` `人工智能` `内容检测`

> A Practical Examination of AI-Generated Text Detectors for Large Language Models

# 摘要

> 大型语言模型的大量涌现，引发了人们对其被滥用的日益担忧，尤其是在人工智能生成的文本被错认为出自人类作者之手的情况下。机器生成内容检测器宣称能在各种条件下及来自任何语言模型的文本中有效识别此类内容。本文通过在一系列领域、数据集以及这些检测器未曾接触过的模型上对几个热门检测器（RADAR、Wild、T5Sentinel、Fast-DetectGPT、GPTID、LogRank、Binoculars）进行评估，对这些宣称予以批判性考量。我们运用各种提示策略来模拟对抗性攻击，结果表明，哪怕是适度的努力也能大幅躲避检测。我们着重强调了在特定误报率（TPR@FPR）指标下真正阳性率的重要性，并指出这些检测器在某些情形下表现欠佳，TPR@.01 甚至低至 0%。我们的发现表明，无论是经过训练的检测器还是零样本检测器，在保持高灵敏度的同时实现合理的真正阳性率方面都面临困境。

> The proliferation of large language models has raised growing concerns about their misuse, particularly in cases where AI-generated text is falsely attributed to human authors. Machine-generated content detectors claim to effectively identify such text under various conditions and from any language model. This paper critically evaluates these claims by assessing several popular detectors (RADAR, Wild, T5Sentinel, Fast-DetectGPT, GPTID, LogRank, Binoculars) on a range of domains, datasets, and models that these detectors have not previously encountered. We employ various prompting strategies to simulate adversarial attacks, demonstrating that even moderate efforts can significantly evade detection. We emphasize the importance of the true positive rate at a specific false positive rate (TPR@FPR) metric and demonstrate that these detectors perform poorly in certain settings, with TPR@.01 as low as 0\%. Our findings suggest that both trained and zero-shot detectors struggle to maintain high sensitivity while achieving a reasonable true positive rate.

[Arxiv](https://arxiv.org/abs/2412.05139)