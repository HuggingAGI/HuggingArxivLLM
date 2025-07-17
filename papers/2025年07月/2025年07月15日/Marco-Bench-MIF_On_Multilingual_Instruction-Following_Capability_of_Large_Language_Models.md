# Marco-Bench-MIF：探讨大型语言模型的多语言指令遵循能力

发布时间：2025年07月15日

`LLM应用` `人工智能`

> Marco-Bench-MIF: On Multilingual Instruction-Following Capability of Large Language Models

# 摘要

> 指令遵循能力已成为大型语言模型（LLMs）评估中的核心能力。然而，现有的数据集，如IFEval，要么以英语为主的单语种数据集，要么只是简单地将数据集机器翻译成其他语言，这在多语言场景下的适用性受到限制。本文中，我们提出了一种精心策划的IFEval扩展版本——本地化多语言版本Marco-Bench-MIF，涵盖30种语言，且每种语言的本地化程度各不相同。我们的基准测试通过结合翻译和验证的混合管道，解决了语言约束（例如，针对中文调整大小写要求）和文化参考（例如，在提示中替换特定地区的公司名称）等问题。通过对20多种LLMs在我们的Marco-Bench-MIF上的全面评估，我们发现：（1）高/低资源语言之间的准确率差距为25-35%，（2）模型规模对性能的影响约为45-60%，但仍然存在特定脚本的挑战，（3）与本地化数据相比，机器翻译数据低估了准确率7-22%。我们的分析揭示了多语言指令遵循中的挑战，包括跨语言的关键词一致性保留和组合性约束的遵循。我们的Marco-Bench-MIF可在https://github.com/AIDC-AI/Marco-Bench-MIF获取。

> Instruction-following capability has become a major ability to be evaluated for Large Language Models (LLMs). However, existing datasets, such as IFEval, are either predominantly monolingual and centered on English or simply machine translated to other languages, limiting their applicability in multilingual contexts. In this paper, we present an carefully-curated extension of IFEval to a localized multilingual version named Marco-Bench-MIF, covering 30 languages with varying levels of localization. Our benchmark addresses linguistic constraints (e.g., modifying capitalization requirements for Chinese) and cultural references (e.g., substituting region-specific company names in prompts) via a hybrid pipeline combining translation with verification. Through comprehensive evaluation of 20+ LLMs on our Marco-Bench-MIF, we found that: (1) 25-35% accuracy gap between high/low-resource languages, (2) model scales largely impact performance by 45-60% yet persists script-specific challenges, and (3) machine-translated data underestimates accuracy by7-22% versus localized data. Our analysis identifies challenges in multilingual instruction following, including keyword consistency preservation and compositional constraint adherence across languages. Our Marco-Bench-MIF is available at https://github.com/AIDC-AI/Marco-Bench-MIF.

[Arxiv](https://arxiv.org/abs/2507.11882)