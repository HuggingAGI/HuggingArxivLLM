# 由推理攻击引导的真实文本清理

发布时间：2024年12月17日

`LLM应用` `隐私保护` `文本处理`

> Truthful Text Sanitization Guided by Inference Attacks

# 摘要

> 文本清理旨在改写文档中那些可能直接或间接识别个人身份的文本片段，确保不再泄露个人信息。文本清理得在防止个人信息泄露（隐私保护）与尽可能多地保留文档原始内容（实用性保留）之间达成平衡。我们给出了一种基于泛化的自动文本清理策略，泛化是更抽象（但仍具信息性）的术语，涵盖了原始文本片段的语义内容。此方法依赖于经指令调整的大型语言模型（LLMs），并分为两个阶段。先是运用LLM获取保留真相的替换候选，并依其抽象程度排序。接着通过LLM进行推理攻击，评估这些候选保护隐私的能力。最终，系统选取最具信息性且能抵御攻击的替换。正因这两阶段流程，所选替换有效平衡了实用性与隐私性。我们还提出新指标，无需人工标注数据就能自动评估这两方面。在文本匿名化基准上的实证结果显示，相比完全抑制原始信息，所提方法提升了实用性，重新识别受保护个人的风险仅略有增加。而且，所选替换比以往方法更能保真且更具抽象性。

> The purpose of text sanitization is to rewrite those text spans in a document that may directly or indirectly identify an individual, to ensure they no longer disclose personal information. Text sanitization must strike a balance between preventing the leakage of personal information (privacy protection) while also retaining as much of the document's original content as possible (utility preservation). We present an automated text sanitization strategy based on generalizations, which are more abstract (but still informative) terms that subsume the semantic content of the original text spans. The approach relies on instruction-tuned large language models (LLMs) and is divided into two stages. The LLM is first applied to obtain truth-preserving replacement candidates and rank them according to their abstraction level. Those candidates are then evaluated for their ability to protect privacy by conducting inference attacks with the LLM. Finally, the system selects the most informative replacement shown to be resistant to those attacks. As a consequence of this two-stage process, the chosen replacements effectively balance utility and privacy. We also present novel metrics to automatically evaluate these two aspects without the need to manually annotate data. Empirical results on the Text Anonymization Benchmark show that the proposed approach leads to enhanced utility, with only a marginal increase in the risk of re-identifying protected individuals compared to fully suppressing the original information. Furthermore, the selected replacements are shown to be more truth-preserving and abstractive than previous methods.

[Arxiv](https://arxiv.org/abs/2412.12928)