# # Lshan-1.0 技术报告

发布时间：2025年03月10日

`LLM应用`

> Lshan-1.0 Technical Report

# 摘要

> 在本报告中，我们正式推出第一代推理模型 Lshan-1.0，专为中文法律领域量身打造，具备全方位能力以满足各类现实需求。现有法律 LLMs 面临两大核心挑战：首先，设计与评估主要基于计算机科学视角，忽视了法律专业知识与逻辑的融入，这对高精度法律应用（如处理复杂公诉任务）至关重要。其次，这些模型常因缺乏全面的法律领域训练数据而表现欠佳，限制了其应对现实法律场景的能力。为解决这些问题，我们从全国31个省份收集了数百万份法律文件，涵盖20多种犯罪类型，用于模型训练。从中精选高质量文档进行监督微调，提升相关性与精确度。随后，模型还进行了大规模强化学习，着重增强推理能力与可解释性。为验证其在复杂法律应用中的有效性，我们邀请法律专家进行人工评估。基于 DeepSeek-R1-Distilled 版本，我们开发了三种配置的微调模型：14B、32B 和 70B。

> In this report, we introduce our first-generation reasoning model, Lshan-1.0, a large language model designed for the highly specialized Chinese legal domain, offering comprehensive capabilities to meet diverse realistic needs. Existing legal LLMs face two primary challenges. Firstly, their design and evaluation are predominantly driven by computer science perspectives, leading to insufficient incorporation of legal expertise and logic, which is crucial for high-precision legal applications, such as handling complex prosecutorial tasks. Secondly, these models often underperform due to a lack of comprehensive training data from the legal domain, limiting their ability to effectively address real-world legal scenarios. To address this, we first compile millions of legal documents covering over 20 types of crimes from 31 provinces in China for model training. From the extensive dataset, we further select high-quality for supervised fine-tuning, ensuring enhanced relevance and precision. The model further undergoes large-scale reinforcement learning without additional supervision, emphasizing the enhancement of its reasoning capabilities and explainability. To validate its effectiveness in complex legal applications, we also conduct human evaluations with legal experts. We develop fine-tuned models based on DeepSeek-R1-Distilled versions, available in three dense configurations: 14B, 32B, and 70B.

[Arxiv](https://arxiv.org/abs/2503.06949)