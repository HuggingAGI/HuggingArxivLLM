# LLMs应遗忘什么？量化评估LLMs中的个人数据以应对被遗忘权请求

发布时间：2025年07月15日

`LLM理论` `隐私保护` `隐私技术`

> What Should LLMs Forget? Quantifying Personal Data in LLMs for Right-to-Be-Forgotten Requests

# 摘要

> 大型语言模型 (LLMs) 存在记忆并泄露个人信息的风险，这引发了对欧盟 GDPR 法规，尤其是“被遗忘权”(RTBF) 的合规性担忧。现有机器学习方法假设要遗忘的数据已知，但未解决如何识别模型中存储的个体-事实关联。隐私审核技术通常在人口层面或针对少量标识符运行，限制了其在个体数据查询中的应用。我们推出了 WikiMem，一个涵盖 Wikidata 中 243 个人类属性的 5,000 多个自然语言“ Canary”数据集，以及一个量化 LLM 中人类-事实关联的模型无关指标。我们的方法通过校准的负对数似然对 paraphrased 提示进行反事实比较，对真实值进行排序。我们评估了 15 个 LLM（410M-70B 参数）中的 200 个个体，发现记忆与主体网络存在和模型规模相关。我们为在个体层面上识别 LLM 中的记忆个人信息奠定了基础，从而能够动态构建遗忘集，用于机器学习和 RTBF 请求。

> Large Language Models (LLMs) can memorize and reveal personal information, raising concerns regarding compliance with the EU's GDPR, particularly the Right to Be Forgotten (RTBF). Existing machine unlearning methods assume the data to forget is already known but do not address how to identify which individual-fact associations are stored in the model. Privacy auditing techniques typically operate at the population level or target a small set of identifiers, limiting applicability to individual-level data inquiries. We introduce WikiMem, a dataset of over 5,000 natural language canaries covering 243 human-related properties from Wikidata, and a model-agnostic metric to quantify human-fact associations in LLMs. Our approach ranks ground-truth values against counterfactuals using calibrated negative log-likelihood across paraphrased prompts. We evaluate 200 individuals across 15 LLMs (410M-70B parameters), showing that memorization correlates with subject web presence and model scale. We provide a foundation for identifying memorized personal data in LLMs at the individual level, enabling the dynamic construction of forget sets for machine unlearning and RTBF requests.

[Arxiv](https://arxiv.org/abs/2507.11128)