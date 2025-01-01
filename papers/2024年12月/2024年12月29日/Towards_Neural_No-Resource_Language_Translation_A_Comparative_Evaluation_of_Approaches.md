# 朝着神经无资源语言翻译迈进：方法的对比评估

发布时间：2024年12月29日

`LLM应用` `机器翻译` `语言保护`

> Towards Neural No-Resource Language Translation: A Comparative Evaluation of Approaches

# 摘要

> 无资源语言，即数字化表征极少甚至没有的语言，给机器翻译（MT）带来了独特挑战。和依赖有限但存在的语料库的低资源语言不同，无资源语言通常可供训练的句子不足 100 句。本研究通过三种不同工作流程探索无资源翻译问题：翻译特定模型的微调、利用大型语言模型（LLMs）基于推理链提示进行上下文学习，以及无推理的直接提示。以欧文斯谷派尤特语为例，我们证实无资源翻译需要与低资源情况截然不同的方法，因为适用于低资源语言的传统机器翻译方法会失效。实证结果显示，虽然传统方法不行，但通用大型语言模型的上下文学习能力能实现无资源语言翻译，其效果超越低资源翻译方法，可与人工翻译比肩（BLEU 0.45 - 0.6）；具体来说，对于较大语料库，推理链提示表现更优，而直接提示在较小数据集上有优势。由于这些方法不受语言限制，它们有可能无需专家介入就推广到多种无资源语言的翻译任务中。这些发现将无资源翻译确立为一种独特范式，需要创新解决方案，为语言保护提供了实用和理论的启示。

> No-resource languages - those with minimal or no digital representation - pose unique challenges for machine translation (MT). Unlike low-resource languages, which rely on limited but existent corpora, no-resource languages often have fewer than 100 sentences available for training. This work explores the problem of no-resource translation through three distinct workflows: fine-tuning of translation-specific models, in-context learning with large language models (LLMs) using chain-of-reasoning prompting, and direct prompting without reasoning. Using Owens Valley Paiute as a case study, we demonstrate that no-resource translation demands fundamentally different approaches from low-resource scenarios, as traditional approaches to machine translation, such as those that work for low-resource languages, fail. Empirical results reveal that, although traditional approaches fail, the in-context learning capabilities of general-purpose large language models enable no-resource language translation that outperforms low-resource translation approaches and rivals human translations (BLEU 0.45-0.6); specifically, chain-of-reasoning prompting outperforms other methods for larger corpora, while direct prompting exhibits advantages in smaller datasets. As these approaches are language-agnostic, they have potential to be generalized to translation tasks from a wide variety of no-resource languages without expert input. These findings establish no-resource translation as a distinct paradigm requiring innovative solutions, providing practical and theoretical insights for language preservation.

[Arxiv](https://arxiv.org/abs/2412.20584)