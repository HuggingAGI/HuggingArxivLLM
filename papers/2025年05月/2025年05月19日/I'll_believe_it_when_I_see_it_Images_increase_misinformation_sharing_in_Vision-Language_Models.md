# 眼见为凭：图像加剧视觉语言模型中的虚假信息传播。

发布时间：2025年05月19日

`LLM应用` `新闻传播` `推荐系统`

> I'll believe it when I see it: Images increase misinformation sharing in Vision-Language Models

# 摘要

> 大型语言模型正逐步融入新闻推荐系统，引发对其在传播虚假信息中角色的担忧。在人类中，视觉内容已知能增强信息的可信度和传播性，但其对视觉语言模型（VLMs）的影响尚不明朗。本研究旨在探讨图像如何影响VLMs的新闻内容传播倾向，不同模型家族间是否存在差异，以及人格设定和内容属性如何调节这一行为。为此分析，我们提出了两项方法学贡献：一种启发自越狱技术的提示策略，模拟具有反社会特质和政治倾向的用户，促使VLMs做出传播决策；以及一个多模态数据集，包含来自PolitiFact的事实核查政治新闻，配对相关图像和真实性的标签。实验结果表明，图像的存在使真实新闻的传播率提高了4.8%，虚假新闻则提高了15.0%。人格设定进一步调节了这一效果：Dark Triad特质会放大虚假新闻的传播，而具有共和党倾向的配置文件则表现出较低的真实敏感度。在所有测试的模型中，只有Claude-3-Haiku表现出对视觉虚假信息的鲁棒性。这些发现凸显了多模态模型行为中新兴的风险，并推动了针对个性化AI系统定制化评估框架和缓解策略的发展。代码和数据集可在以下链接获取：【数学公式】

> Large language models are increasingly integrated into news recommendation systems, raising concerns about their role in spreading misinformation. In humans, visual content is known to boost credibility and shareability of information, yet its effect on vision-language models (VLMs) remains unclear. We present the first study examining how images influence VLMs' propensity to reshare news content, whether this effect varies across model families, and how persona conditioning and content attributes modulate this behavior. To support this analysis, we introduce two methodological contributions: a jailbreaking-inspired prompting strategy that elicits resharing decisions from VLMs while simulating users with antisocial traits and political alignments; and a multimodal dataset of fact-checked political news from PolitiFact, paired with corresponding images and ground-truth veracity labels. Experiments across model families reveal that image presence increases resharing rates by 4.8% for true news and 15.0% for false news. Persona conditioning further modulates this effect: Dark Triad traits amplify resharing of false news, whereas Republican-aligned profiles exhibit reduced veracity sensitivity. Of all the tested models, only Claude-3-Haiku demonstrates robustness to visual misinformation. These findings highlight emerging risks in multimodal model behavior and motivate the development of tailored evaluation frameworks and mitigation strategies for personalized AI systems. Code and dataset are available at: https://github.com/3lis/misinfo_vlm

[Arxiv](https://arxiv.org/abs/2505.13302)