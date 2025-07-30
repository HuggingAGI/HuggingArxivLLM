# TRIDENT：金融、医学与法律领域中的大型语言模型安全性评估

发布时间：2025年07月22日

`LLM应用`

> TRIDENT: Benchmarking LLM Safety in Finance, Medicine, and Law

# 摘要

> 随着大型语言模型（LLMs）在法律、金融和医学等高风险领域的广泛应用，系统性评估其领域特定的安全性和合规性变得至关重要。尽管此前研究主要致力于提升LLMs在这些领域的性能，却往往忽视了对领域特定安全风险的评估。为填补这一空白，我们基于美国医学协会（AMA）的医学伦理原则、美国律师协会（ABA）的职业行为模范规则以及特许金融分析师（CFA）协会的道德准则，制定了适用于LLMs的领域特定安全原则。基于这些原则，我们推出了Trident-Bench，这是一个专为评估法律、金融和医学领域LLM安全性设计的基准测试框架。我们对19个通用和领域专用模型在Trident-Bench上的表现进行了评估，结果表明该基准能够有效揭示关键的安全性差距：强大的通用模型（如GPT、Gemini）能够满足基本期望，而领域专用模型往往难以应对微妙的伦理细节。这一发现凸显了对更精细的领域特定安全性改进的迫切需求。通过推出Trident-Bench，我们的工作为研究法律和金融领域中的LLM安全性提供了首批系统性资源之一，并为未来旨在降低在专业监管领域部署LLMs安全风险的研究奠定了基础。代码和基准测试将发布于：https://github.com/zackhuiiiii/TRIDENT

> As large language models (LLMs) are increasingly deployed in high-risk domains such as law, finance, and medicine, systematically evaluating their domain-specific safety and compliance becomes critical. While prior work has largely focused on improving LLM performance in these domains, it has often neglected the evaluation of domain-specific safety risks. To bridge this gap, we first define domain-specific safety principles for LLMs based on the AMA Principles of Medical Ethics, the ABA Model Rules of Professional Conduct, and the CFA Institute Code of Ethics. Building on this foundation, we introduce Trident-Bench, a benchmark specifically targeting LLM safety in the legal, financial, and medical domains. We evaluated 19 general-purpose and domain-specialized models on Trident-Bench and show that it effectively reveals key safety gaps -- strong generalist models (e.g., GPT, Gemini) can meet basic expectations, whereas domain-specialized models often struggle with subtle ethical nuances. This highlights an urgent need for finer-grained domain-specific safety improvements. By introducing Trident-Bench, our work provides one of the first systematic resources for studying LLM safety in law and finance, and lays the groundwork for future research aimed at reducing the safety risks of deploying LLMs in professionally regulated fields. Code and benchmark will be released at: https://github.com/zackhuiiiii/TRIDENT

[Arxiv](https://arxiv.org/abs/2507.21134)