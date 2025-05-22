# # 盲点导航：LVLMs敏感语义概念的进化发现

发布时间：2025年05月21日

`LLM应用` `计算机视觉` `对抗攻击`

> Blind Spot Navigation: Evolutionary Discovery of Sensitive Semantic Concepts for LVLMs

# 摘要

> 对抗攻击通过生成恶意输入欺骗深度模型，但它们无法解释“输入中的哪些内容更可能让模型出错？”这样的问题。然而，这种信息对提升模型鲁棒性至关重要。研究表明，模型可能对视觉输入中的某些特定语义（如“湿润”、“有雾”）特别敏感，容易出错。受此启发，我们首次研究了大型视觉语言模型（LVLMs），发现它们在面对特定图像语义时容易产生幻觉和错误。为了高效搜索这些敏感语义，我们整合了大型语言模型（LLMs）和文本到图像（T2I）模型，提出了新型语义演化框架。随机初始化的语义概念通过LLM基的交叉和变异操作形成图像描述，然后通过T2I模型转换为LVLMs的视觉输入。LVLMs在每个输入上的特定任务性能被量化为相关语义的适应度分数，并作为奖励信号进一步引导LLMs探索引发LVLMs的概念。在七种主流LVLMs和两种多模态任务上的大量实验验证了我们方法的有效性。此外，我们还提供了关于LVLMs敏感语义的有趣发现，旨在启发进一步的深入研究。

> Adversarial attacks aim to generate malicious inputs that mislead deep models, but beyond causing model failure, they cannot provide certain interpretable information such as ``\textit{What content in inputs make models more likely to fail?}'' However, this information is crucial for researchers to specifically improve model robustness. Recent research suggests that models may be particularly sensitive to certain semantics in visual inputs (such as ``wet,'' ``foggy''), making them prone to errors. Inspired by this, in this paper we conducted the first exploration on large vision-language models (LVLMs) and found that LVLMs indeed are susceptible to hallucinations and various errors when facing specific semantic concepts in images. To efficiently search for these sensitive concepts, we integrated large language models (LLMs) and text-to-image (T2I) models to propose a novel semantic evolution framework. Randomly initialized semantic concepts undergo LLM-based crossover and mutation operations to form image descriptions, which are then converted by T2I models into visual inputs for LVLMs. The task-specific performance of LVLMs on each input is quantified as fitness scores for the involved semantics and serves as reward signals to further guide LLMs in exploring concepts that induce LVLMs. Extensive experiments on seven mainstream LVLMs and two multimodal tasks demonstrate the effectiveness of our method. Additionally, we provide interesting findings about the sensitive semantics of LVLMs, aiming to inspire further in-depth research.

[Arxiv](https://arxiv.org/abs/2505.15265)