# 关键的思想问题：以论证性查询引导 LLM 进行推理

发布时间：2024年12月19日

`LLM应用` `人工智能`

> Critical-Questions-of-Thought: Steering LLM reasoning with Argumentative Querying

# 摘要

> 研究表明，尽管人工智能研究近来取得突破且进展迅速，但即便是最先进的大型语言模型（LLMs）在进行逻辑和数学推理时仍力不从心。结果似乎显示，LLMs 仍充当着（高度先进的）数据模式识别器，在尝试解决模型未曾见过或与训练数据中的样本差异较大的推理问题时表现欠佳。为应对这一棘手问题，本文借鉴了论证理论文献中的关键问题概念，特别聚焦于图尔敏的论证模型。我们发现，运用这些关键问题能够提升 LLMs 的推理能力。通过探寻模型推理过程的依据，LLM 能够判断是否存在逻辑错误，并在向用户提示给出最终回复前予以纠正。其核心思想源自任何有效论证程序的黄金准则：若结论由已被接受的前提所蕴含，则结论有效。或者，用现实世界中信息不完整和推测逻辑的特点来诠释这一亚里士多德原则，即若未被证明无效，则结论有效。这种方法成功引导模型的输出通过推理通道，相比基线及其思维链（CoT）实现，取得了更优的性能。为此，针对一系列 LLMs 在 MT-Bench 推理和数学任务上对所提方法进行了广泛评估。

> Studies have underscored how, regardless of the recent breakthrough and swift advances in AI research, even state-of-the-art Large Language models (LLMs) continue to struggle when performing logical and mathematical reasoning. The results seem to suggest that LLMs still work as (highly advanced) data pattern identifiers, scoring poorly when attempting to generalise and solve reasoning problems the models have never previously seen or that are not close to samples presented in their training data. To address this compelling concern, this paper makes use of the notion of critical questions from the literature on argumentation theory, focusing in particular on Toulmin's model of argumentation. We show that employing these critical questions can improve the reasoning capabilities of LLMs. By probing the rationale behind the models' reasoning process, the LLM can assess whether some logical mistake is occurring and correct it before providing the final reply to the user prompt. The underlying idea is drawn from the gold standard of any valid argumentative procedure: the conclusion is valid if it is entailed by accepted premises. Or, to paraphrase such Aristotelian principle in a real-world approximation, characterised by incomplete information and presumptive logic, the conclusion is valid if not proved otherwise. This approach successfully steers the models' output through a reasoning pipeline, resulting in better performance against the baseline and its Chain-of-Thought (CoT) implementation. To this end, an extensive evaluation of the proposed approach on the MT-Bench Reasoning and Math tasks across a range of LLMs is provided.

[Arxiv](https://arxiv.org/abs/2412.15177)