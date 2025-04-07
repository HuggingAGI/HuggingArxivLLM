# 立场驱动的多模态可控声明生成：新数据集与任务

发布时间：2025年04月04日

`LLM应用` `社交媒体` `政治传播`

> Stance-Driven Multimodal Controlled Statement Generation: New Dataset and Task

# 摘要

> # 摘要
在特定话题上制定支持多样化或有争议立场的陈述，对于支持用户表达、重塑政治话语、推动社会批判和信息传播的平台至关重要。随着大型语言模型（LLMs）的兴起，面向特定立场的可控文本生成已成为一个有前景的研究领域，其应用涵盖塑造公众舆论和商业营销。然而，当前的数据集往往仅关注纯文本，缺乏多模态内容和有效的上下文，特别是在立场检测的背景下。

本文中，我们正式定义并研究了针对推文文本和图像的立场驱动可控内容生成这一新问题。给定一个多模态帖子（文本和图像/视频），模型生成一个立场可控的响应。为此，我们创建了多模态立场生成数据集（StanceGen2024），这是首个专为政治话语中的多模态立场可控文本生成设计的资源。它包含了2024年美国总统大选的帖子和用户评论，涵盖了文本、图像、视频以及立场标注，以探索多模态政治内容如何塑造立场表达。

此外，我们提出了一种基于立场驱动的多模态生成（SDMG）框架，该框架集成了多模态特征的加权融合和立场引导，以提升语义一致性和立场控制能力。我们公开发布了该数据集和代码（https://anonymous.4open.science/r/StanceGen-BE9D），供公众使用和进一步研究。

> Formulating statements that support diverse or controversial stances on specific topics is vital for platforms that enable user expression, reshape political discourse, and drive social critique and information dissemination. With the rise of Large Language Models (LLMs), controllable text generation towards specific stances has become a promising research area with applications in shaping public opinion and commercial marketing. However, current datasets often focus solely on pure texts, lacking multimodal content and effective context, particularly in the context of stance detection. In this paper, we formally define and study the new problem of stance-driven controllable content generation for tweets with text and images, where given a multimodal post (text and image/video), a model generates a stance-controlled response. To this end, we create the Multimodal Stance Generation Dataset (StanceGen2024), the first resource explicitly designed for multimodal stance-controllable text generation in political discourse. It includes posts and user comments from the 2024 U.S. presidential election, featuring text, images, videos, and stance annotations to explore how multimodal political content shapes stance expression. Furthermore, we propose a Stance-Driven Multimodal Generation (SDMG) framework that integrates weighted fusion of multimodal features and stance guidance to improve semantic consistency and stance control. We release the dataset and code (https://anonymous.4open.science/r/StanceGen-BE9D) for public use and further research.

[Arxiv](https://arxiv.org/abs/2504.03295)