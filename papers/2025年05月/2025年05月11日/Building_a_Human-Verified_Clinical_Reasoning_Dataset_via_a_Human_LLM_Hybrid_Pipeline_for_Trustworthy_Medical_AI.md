# 构建值得信赖的医疗人工智能：通过人机混合流水线创建人机协同验证的临床推理数据集

发布时间：2025年05月11日

`LLM应用` `数据集`

> Building a Human-Verified Clinical Reasoning Dataset via a Human LLM Hybrid Pipeline for Trustworthy Medical AI

# 摘要

> 尽管大型语言模型（LLMs）在医疗问答领域表现出色，但其不透明的'黑箱'推理机制严重阻碍了临床应用，影响了医生的信任。当前医疗LLMs主要依赖科学文献或合成数据，缺乏精细的专家验证和高临床相关性，这对提升其专业医疗能力至关重要。为解决这些关键问题，我们推出一个包含31,247个医疗问答对的高临床相关性数据集，每个问答都配有专家验证的链式思维（CoT）解释。这一跨多临床领域的资源通过可扩展的人工-LLM混合流程整理：LLM生成的理由经医学专家迭代审查、评分和优化，参照结构化标准，不合格内容通过人工或引导LLM再生至专家共识。该公开数据集为开发具备透明可验证推理的医疗LLMs提供了宝贵资源，推动了更安全、更易解释的医疗AI发展。

> Despite strong performance in medical question-answering, the clinical adoption of Large Language Models (LLMs) is critically hampered by their opaque 'black-box' reasoning, limiting clinician trust. This challenge is compounded by the predominant reliance of current medical LLMs on corpora from scientific literature or synthetic data, which often lack the granular expert validation and high clinical relevance essential for advancing their specialized medical capabilities. To address these critical gaps, we introduce a highly clinically relevant dataset with 31,247 medical question-answer pairs, each accompanied by expert-validated chain-of-thought (CoT) explanations. This resource, spanning multiple clinical domains, was curated via a scalable human-LLM hybrid pipeline: LLM-generated rationales were iteratively reviewed, scored, and refined by medical experts against a structured rubric, with substandard outputs revised through human effort or guided LLM regeneration until expert consensus. This publicly available dataset provides a vital source for the development of medical LLMs that capable of transparent and verifiable reasoning, thereby advancing safer and more interpretable AI in medicine.

[Arxiv](https://arxiv.org/abs/2505.06912)