# PhantomHunter：通过家族感知学习检测未见过的私有微调LLM生成文本

发布时间：2025年06月18日

`LLM应用` `人工智能` `学术研究`

> PhantomHunter: Detecting Unseen Privately-Tuned LLM-Generated Text via Family-Aware Learning

# 摘要

> 大型语言模型 (LLMs) 的流行加剧了虚假信息生成和学术不端等不良社会问题，使检测LLM生成文本变得至关重要。虽然现有方法已取得显著进展，但来自私有微调LLM的文本带来的新挑战尚未得到充分研究。用户只需通过私有语料对开源模型进行微调，即可轻松获得私有LLM，这导致现有检测器在实际应用中性能大幅下降。为解决这一问题，我们提出了PhantomHunter，一款专注于检测不可见私有微调LLM生成文本的检测器。其家族感知学习框架能够捕捉基础模型及其衍生模型共有的家族级特征，而非仅仅记忆个体特征。在LLaMA、Gemma和Mistral家族的数据上进行的实验表明，PhantomHunter超越了7种基线和3种工业服务，F1分数高达96%以上。

> With the popularity of large language models (LLMs), undesirable societal problems like misinformation production and academic misconduct have been more severe, making LLM-generated text detection now of unprecedented importance. Although existing methods have made remarkable progress, a new challenge posed by text from privately tuned LLMs remains underexplored. Users could easily possess private LLMs by fine-tuning an open-source one with private corpora, resulting in a significant performance drop of existing detectors in practice. To address this issue, we propose PhantomHunter, an LLM-generated text detector specialized for detecting text from unseen, privately-tuned LLMs. Its family-aware learning framework captures family-level traits shared across the base models and their derivatives, instead of memorizing individual characteristics. Experiments on data from LLaMA, Gemma, and Mistral families show its superiority over 7 baselines and 3 industrial services, with F1 scores of over 96%.

[Arxiv](https://arxiv.org/abs/2506.15683)