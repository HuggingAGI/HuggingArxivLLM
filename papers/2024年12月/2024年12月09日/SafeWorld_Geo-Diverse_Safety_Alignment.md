# SafeWorld：地域多元的安全对齐

发布时间：2024年12月09日

`LLM应用` `语言模型` `安全评估`

> SafeWorld: Geo-Diverse Safety Alignment

# 摘要

> 在大型语言模型（LLMs）迅猛发展的领域，保障安全性是关键且广受热议的话题。然而，现有的成果往往忽视了全球文化和法律标准的地域差异。为展现地域多样的安全标准带来的挑战，我们推出了 SafeWorld，这一全新的基准专门用于评估 LLMs 生成既有益，又在全球不同情境下具备文化敏感性和合法合规性回应的能力。SafeWorld 涵盖 2342 个测试用户的查询，每个查询都基于来自 50 个国家和 493 个地区/种族的高质量、经人工核实的文化规范与法律政策。在此之上，我们提出了一个多维的自动安全评估框架，以评估回应的上下文适宜性、准确性和全面性。我们的评估显示，当下的 LLMs 难以达到这些标准。为增强 LLMs 与地域多样的安全标准的契合度，我们为直接偏好优化（DPO）对齐训练合成了有用的偏好对。偏好对的构建旨在促使 LLMs 表现恰当，并在必要时为相关文化规范和政策提供精准参考。我们训练的 SafeWorldLM 在所有三个评估维度上大幅超越包括 GPT-4o 在内的所有竞争模型。全球人类评估者还指出，在有用性和有害性评估中的获胜率近乎高出 20%。我们的代码和数据可在此处获取：https://github.com/PlusLabNLP/SafeWorld。

> In the rapidly evolving field of Large Language Models (LLMs), ensuring safety is a crucial and widely discussed topic. However, existing works often overlook the geo-diversity of cultural and legal standards across the world. To demonstrate the challenges posed by geo-diverse safety standards, we introduce SafeWorld, a novel benchmark specifically designed to evaluate LLMs' ability to generate responses that are not only helpful but also culturally sensitive and legally compliant across diverse global contexts. SafeWorld encompasses 2,342 test user queries, each grounded in high-quality, human-verified cultural norms and legal policies from 50 countries and 493 regions/races. On top of it, we propose a multi-dimensional automatic safety evaluation framework that assesses the contextual appropriateness, accuracy, and comprehensiveness of responses. Our evaluations reveal that current LLMs struggle to meet these criteria. To enhance LLMs' alignment with geo-diverse safety standards, we synthesize helpful preference pairs for Direct Preference Optimization (DPO) alignment training. The preference pair construction aims to encourage LLMs to behave appropriately and provide precise references to relevant cultural norms and policies when necessary. Our trained SafeWorldLM outperforms all competing models, including GPT-4o on all three evaluation dimensions by a large margin. Global human evaluators also note a nearly 20% higher winning rate in helpfulness and harmfulness evaluation. Our code and data can be found here: https://github.com/PlusLabNLP/SafeWorld.

[Arxiv](https://arxiv.org/abs/2412.06483)