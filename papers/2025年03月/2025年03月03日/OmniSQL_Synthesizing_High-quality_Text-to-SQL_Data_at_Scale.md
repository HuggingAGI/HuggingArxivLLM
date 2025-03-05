# OmniSQL：大规模生成高质量文本到SQL数据

发布时间：2025年03月03日

`LLM应用

<example>
论文摘要：将文本信息表示为实数嵌入已成为 NLP 的规范。此外，随着公众对大型语言模型 (LLM) 兴趣的增加，嵌入即服务 (EaaS) 作为一种商业模式迅速受到关注。这并非没有突出的安全风险，因为之前的研究已经证明，即使不了解生成敏感数据的底层模型，也可以从嵌入中重建敏感数据。然而，此类工作因其仅关注英语而受到限制，使得所有其他语言都容易受到恶意行为者的攻击。由于许多国际和多语言公司利用 EaaS，迫切需要研究多语言 LLM 安全性。为此，本工作从多语言嵌入反转的角度研究LLM安全性。具体来说，我们定义了黑盒多语言和跨语言反转攻击问题，特别关注跨域场景。我们的研究结果表明，多语言模型可能比单语言模型更容易受到反转攻击。这是因为在底层语言事先未知的情况下，实现可比较的反演性能所需的数据量减少了。据我们所知，这项工作是第一个在反转攻击的背景下深入研究多语言性的工作，我们的发现强调了在 NLP 安全领域进一步调查和加强防御的必要性。
LLM应用
</example>

论文摘要：文本到SQL任务在帮助非专业人士与数据库交互方面发挥着关键作用。尽管大型语言模型的最新进展显著提升了文本到SQL的表现，现有方法在实际应用中仍存在明显局限。基于提示的方法通常依赖闭源LLMs，这不仅成本高昂，还引发隐私担忧，并缺乏定制性。而基于微调的方法则因公开可用训练数据覆盖范围有限，导致泛化能力欠佳。为克服这些挑战，我们提出了一种新颖且可扩展的文本到SQL数据合成框架，用于在无需大量人工干预的情况下，自动合成大规模、高质量且多样化的数据集。借助此框架，我们推出了SynSQL-2.5M，首个百万规模的文本到SQL数据集，包含250万个样本，覆盖超过1.6万个合成数据库。每个样本包括数据库、SQL查询、自然语言问题及链式思维（CoT）解决方案。基于SynSQL-2.5M，我们开发了OmniSQL，一款强大的开源文本到SQL模型，提供7B、14B和32B三种规模。在九个数据集上的广泛评估表明，尽管OmniSQL规模较小，但其性能已达到前沿水平，与领先闭源和开源LLMs（包括GPT-4o和DeepSeek-V3）相媲美或超越。我们开源了所有代码、数据集和模型，以支持进一步研究。
LLM应用` `数据库` `数据科学`

> OmniSQL: Synthesizing High-quality Text-to-SQL Data at Scale

# 摘要

> 文本到SQL任务在帮助非专业人士与数据库交互方面发挥着关键作用。尽管大型语言模型的最新进展显著提升了文本到SQL的表现，现有方法在实际应用中仍存在明显局限。基于提示的方法通常依赖闭源LLMs，这不仅成本高昂，还引发隐私担忧，并缺乏定制性。而基于微调的方法则因公开可用训练数据覆盖范围有限，导致泛化能力欠佳。为克服这些挑战，我们提出了一种新颖且可扩展的文本到SQL数据合成框架，用于在无需大量人工干预的情况下，自动合成大规模、高质量且多样化的数据集。借助此框架，我们推出了SynSQL-2.5M，首个百万规模的文本到SQL数据集，包含250万个样本，覆盖超过1.6万个合成数据库。每个样本包括数据库、SQL查询、自然语言问题及链式思维（CoT）解决方案。基于SynSQL-2.5M，我们开发了OmniSQL，一款强大的开源文本到SQL模型，提供7B、14B和32B三种规模。在九个数据集上的广泛评估表明，尽管OmniSQL规模较小，但其性能已达到前沿水平，与领先闭源和开源LLMs（包括GPT-4o和DeepSeek-V3）相媲美或超越。我们开源了所有代码、数据集和模型，以支持进一步研究。

> Text-to-SQL, the task of translating natural language questions into SQL queries, plays a crucial role in enabling non-experts to interact with databases. While recent advancements in large language models (LLMs) have significantly enhanced text-to-SQL performance, existing approaches face notable limitations in real-world text-to-SQL applications. Prompting-based methods often depend on closed-source LLMs, which are expensive, raise privacy concerns, and lack customization. Fine-tuning-based methods, on the other hand, suffer from poor generalizability due to the limited coverage of publicly available training data. To overcome these challenges, we propose a novel and scalable text-to-SQL data synthesis framework for automatically synthesizing large-scale, high-quality, and diverse datasets without extensive human intervention. Using this framework, we introduce SynSQL-2.5M, the first million-scale text-to-SQL dataset, containing 2.5 million samples spanning over 16,000 synthetic databases. Each sample includes a database, SQL query, natural language question, and chain-of-thought (CoT) solution. Leveraging SynSQL-2.5M, we develop OmniSQL, a powerful open-source text-to-SQL model available in three sizes: 7B, 14B, and 32B. Extensive evaluations across nine datasets demonstrate that OmniSQL achieves state-of-the-art performance, matching or surpassing leading closed-source and open-source LLMs, including GPT-4o and DeepSeek-V3, despite its smaller size. We release all code, datasets, and models to support further research.

[Arxiv](https://arxiv.org/abs/2503.02240)