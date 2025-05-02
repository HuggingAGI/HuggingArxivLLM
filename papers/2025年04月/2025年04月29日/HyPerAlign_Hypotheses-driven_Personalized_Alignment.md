# HyPerAlign：以假设为驱动的个性化对齐方法

发布时间：2025年04月29日

`LLM应用` `人工智能`

> HyPerAlign: Hypotheses-driven Personalized Alignment

# 摘要

> 对齐算法在大型语言模型（LLMs）与人类用户对齐方面发挥着重要作用，主要依据反映用户预期真实使用场景的偏好标注。传统方法通常汇总多样用户群体中的（常相互矛盾的）偏好，生成与“平均用户”偏好一致的微调模型。然而，实际应用中，LLM模型被个体用户在具体情境下使用，凸显了对用户个性化偏好控制的需求。本研究聚焦于个性化LLM输出，旨在为每位用户定制专属响应，而非生成模仿多样化人群集体声音的通用输出。我们提出了一种可解释且样本高效的基于假设的个性化方法（HyPerAlign），该方法通过分析用户提供的少量示例，推断用户的沟通策略、个性特征和写作风格，结合用户特定属性，生成定制化输出。实验涵盖作者归属和审慎对齐两个任务，采用来自新闻、博客、邮件及越狱基准测试等多领域的数据集，结果显示基于假设的个性化方法显著优于传统基于偏好的微调方法。在审慎对齐任务中，LLM模型的有用性平均提升达【数学公式】。在作者归属任务中，该方法在多样化用户群体和LLM模型上展现出持续的高胜率（通常超过【数学公式】），超越现有基于偏好的微调方法。总体而言，我们的方法为LLM模型的个性化提供了一种可解释且高效的新策略。

> Alignment algorithms are widely used to align large language models (LLMs) to human users based on preference annotations that reflect their intended real-world use cases. Typically these (often divergent) preferences are aggregated over a diverse set of users, resulting in fine-tuned models that are aligned to the ``average-user'' preference. Nevertheless, current models are used by individual users in very specific contexts and situations, emphasizing the need for user-dependent preference control. In this work we address the problem of personalizing LLM outputs to their users, aiming to generate customized responses tailored to individual users, instead of generic outputs that emulate the collective voices of diverse populations. We propose a novel interpretable and sample-efficient hypotheses-driven personalization approach (HyPerAlign) where given few-shot examples written by a particular user, we first infer hypotheses about their communication strategies, personality and writing style, then prompt LLM models with these hypotheses and user specific attributes to generate customized outputs. We conduct experiments on two different personalization tasks, authorship attribution and deliberative alignment, with datasets from diverse domains (news articles, blog posts, emails, jailbreaking benchmarks), and demonstrate the superiority of hypotheses-driven personalization approach when compared to preference-based fine-tuning methods. For deliberative alignment, the helpfulness of LLM models is improved by up to $70\%$ on average. For authorship attribution, results indicate consistently high win-rates (commonly $>90\%$) against state-of-the-art preference fine-tuning approaches for LLM personalization across diverse user profiles and LLM models. Overall, our approach represents an interpretable and sample-efficient strategy for the personalization of LLM models to individual users.

[Arxiv](https://arxiv.org/abs/2505.00038)