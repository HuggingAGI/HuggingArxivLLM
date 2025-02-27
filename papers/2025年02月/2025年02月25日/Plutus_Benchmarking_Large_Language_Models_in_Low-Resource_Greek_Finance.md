# 普路托斯：针对低资源希腊金融领域的大型语言模型基准测试

发布时间：2025年02月25日

`LLM应用

<example>
论文摘要：将文本信息表示为实数嵌入已成为 NLP 的规范。此外，随着公众对大型语言模型 (LLM) 兴趣的增加，嵌入即服务 (EaaS) 作为一种商业模式迅速受到关注。这并非没有突出的安全风险，因为之前的研究已经证明，即使不了解生成敏感数据的底层模型，也可以从嵌入中重建敏感数据。然而，此类工作因其仅关注英语而受到限制，使得所有其他语言都容易受到恶意行为者的攻击。由于许多国际和多语言公司利用 EaaS，迫切需要研究多语言 LLM 安全性。为此，本工作从多语言嵌入反转的角度研究LLM安全性。具体来说，我们定义了黑盒多语言和跨语言反转攻击问题，特别关注跨域场景。我们的研究结果表明，多语言模型可能比单语言模型更容易受到反转攻击。这是因为在底层语言事先未知的情况下，实现可比较的反演性能所需的数据量减少了。据我们所知，这项工作是第一个在反转攻击的背景下深入研究多语言性的工作，我们的发现强调了在 NLP 安全领域进一步调查和加强防御的必要性。
LLM应用
</example>

论文摘要：尽管希腊在全球经济中扮演着关键角色，大型语言模型（LLMs）在希腊金融领域的应用仍研究不足，主要归因于希腊语的复杂性及特定领域数据集的稀缺性。此前在多语言金融自然语言处理（NLP）领域的努力揭示了显著的性能差异，但至今仍未开发出专门针对希腊金融领域的基准测试或希腊语特定的金融LLMs。为填补这一空白，我们推出了Plutus-ben——首个希腊金融评估基准，以及Plutus-8B——首个基于希腊领域数据微调的希腊金融LLM。Plutus-ben涵盖了希腊语下的五个核心金融NLP任务：数值与文本命名实体识别、问答、摘要、以及主题分类，为系统化和可复现的LLM评估提供了支持。为支撑这些任务，我们发布了三个全新的高质量希腊金融数据集，均由专家级希腊语母语者进行标注，并结合了两个现有资源。对22个LLMs在Plutus-ben上的全面评估表明，希腊语金融NLP仍具挑战性，原因包括语言复杂性、领域特定术语以及金融推理能力的不足。这些发现凸显了跨语言迁移的局限性，凸显了在希腊语训练模型中融入金融专业知识的必要性，同时也揭示了将金融LLMs适应希腊语文本的挑战。我们公开发布了Plutus-ben、Plutus-8B及所有相关数据集，以推动可复现的研究，促进希腊语金融NLP的发展，并在金融领域推动更广泛的多语言包容性。
LLM应用`

> Plutus: Benchmarking Large Language Models in Low-Resource Greek Finance

# 摘要

> 尽管希腊在全球经济中扮演着关键角色，大型语言模型（LLMs）在希腊金融领域的应用仍研究不足，主要归因于希腊语的复杂性及特定领域数据集的稀缺性。此前在多语言金融自然语言处理（NLP）领域的努力揭示了显著的性能差异，但至今仍未开发出专门针对希腊金融领域的基准测试或希腊语特定的金融LLMs。为填补这一空白，我们推出了Plutus-ben——首个希腊金融评估基准，以及Plutus-8B——首个基于希腊领域数据微调的希腊金融LLM。Plutus-ben涵盖了希腊语下的五个核心金融NLP任务：数值与文本命名实体识别、问答、摘要、以及主题分类，为系统化和可复现的LLM评估提供了支持。为支撑这些任务，我们发布了三个全新的高质量希腊金融数据集，均由专家级希腊语母语者进行标注，并结合了两个现有资源。对22个LLMs在Plutus-ben上的全面评估表明，希腊语金融NLP仍具挑战性，原因包括语言复杂性、领域特定术语以及金融推理能力的不足。这些发现凸显了跨语言迁移的局限性，凸显了在希腊语训练模型中融入金融专业知识的必要性，同时也揭示了将金融LLMs适应希腊语文本的挑战。我们公开发布了Plutus-ben、Plutus-8B及所有相关数据集，以推动可复现的研究，促进希腊语金融NLP的发展，并在金融领域推动更广泛的多语言包容性。

> Despite Greece's pivotal role in the global economy, large language models (LLMs) remain underexplored for Greek financial context due to the linguistic complexity of Greek and the scarcity of domain-specific datasets. Previous efforts in multilingual financial natural language processing (NLP) have exposed considerable performance disparities, yet no dedicated Greek financial benchmarks or Greek-specific financial LLMs have been developed until now. To bridge this gap, we introduce Plutus-ben, the first Greek Financial Evaluation Benchmark, and Plutus-8B, the pioneering Greek Financial LLM, fine-tuned with Greek domain-specific data. Plutus-ben addresses five core financial NLP tasks in Greek: numeric and textual named entity recognition, question answering, abstractive summarization, and topic classification, thereby facilitating systematic and reproducible LLM assessments. To underpin these tasks, we present three novel, high-quality Greek financial datasets, thoroughly annotated by expert native Greek speakers, augmented by two existing resources. Our comprehensive evaluation of 22 LLMs on Plutus-ben reveals that Greek financial NLP remains challenging due to linguistic complexity, domain-specific terminology, and financial reasoning gaps. These findings underscore the limitations of cross-lingual transfer, the necessity for financial expertise in Greek-trained models, and the challenges of adapting financial LLMs to Greek text. We release Plutus-ben, Plutus-8B, and all associated datasets publicly to promote reproducible research and advance Greek financial NLP, fostering broader multilingual inclusivity in finance.

[Arxiv](https://arxiv.org/abs/2502.18772)