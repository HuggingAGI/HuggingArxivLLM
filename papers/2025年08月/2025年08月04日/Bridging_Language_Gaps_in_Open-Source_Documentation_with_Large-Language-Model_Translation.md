# 借助大语言模型翻译，跨越开源文档中的语言鸿沟

发布时间：2025年08月04日

`LLM应用

LLM应用` `软件工程` `文档管理`

> Bridging Language Gaps in Open-Source Documentation with Large-Language-Model Translation

# 摘要

> 尽管开源社区吸引了全球各地的多元化贡献者，但鲜有代码仓库提供非英语的必要文档。大型语言模型（LLMs）在软件工程任务和跨领域翻译方面展现出了非凡的能力，但其在翻译技术文档（包含自然语言、代码、URL和Markdown格式）方面的潜力尚未得到充分探索。为了深入理解这一潜力，我们评估了社区翻译活动，并使用OpenAI的ChatGPT 4和Anthropic的Claude对50份README文件进行了英译德测试。我们发现翻译活动稀缺，主要集中在大型仓库中，并且具有社区驱动的性质。LLMs性能对比表明它们能够提供准确的翻译，但分析揭示了保真度方面的挑战：两种模型在保留结构组件（例如超链接）方面都存在困难，并且格式上也存在不一致。这些发现凸显了LLM辅助文档国际化所面临的机遇与挑战。作为迈向翻译感知持续集成管道的第一步，我们介绍了TRIFID，这是一个早期阶段的翻译保真度评分框架，能够自动检查翻译在保留代码、链接和格式方面的效果。我们的工作为利用LLM驱动的自动化工具创建和维护开源文档奠定了基础。

> While open source communities attract diverse contributors globally, few repositories provide essential documentation in languages other than English. Large language models (LLMs) have demonstrated remarkable capabilities in software engineering tasks and translations across domains. However, little is known about LLM capabilities in translating open-source technical documentation, which mixes natural language, code, URLs, and markdown formatting. To understand the need and potential for LLMs in technical documentation translation, we evaluated community translation activity and English-to-German translations of 50 README files using OpenAI's ChatGPT 4 and Anthropic's Claude. We found scarce translation activity, mostly in larger repositories and community-driven in nature. LLM performance comparison suggests they can provide accurate translations. However, analysis revealed fidelity challenges: both models struggled to preserve structural components (e.g., hyperlinks) and exhibited formatting inconsistencies. These findings highlight both promise and challenges of LLM-assisted documentation internationalization. As a first step toward translation-aware continuous integration pipelines, we introduce TRIFID, an early-stage translation fidelity scoring framework that automatically checks how well translations preserve code, links, and formatting. Our efforts provide a foundation for automated LLM-driven support for creating and maintaining open source documentation.

[Arxiv](https://arxiv.org/abs/2508.02497)