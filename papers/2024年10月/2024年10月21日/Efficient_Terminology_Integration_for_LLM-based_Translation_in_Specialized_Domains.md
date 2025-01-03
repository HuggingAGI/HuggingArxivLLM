# 基于LLM的专业领域翻译中的高效术语集成

发布时间：2024年10月21日

`LLM应用

**理由**：这篇论文主要讨论了如何利用LLM（大型语言模型）来提升专业术语翻译的准确性，特别是在专利、金融或生物医学等领域。论文提出了一种方法，通过Trie Tree算法提取术语并创建词汇表，随后教导LLM如何整合这些专业术语。这种方法直接应用了LLM的能力来解决特定领域的问题，因此属于LLM应用。`

> Efficient Terminology Integration for LLM-based Translation in Specialized Domains

# 摘要

> 传统机器翻译方法通常依赖大规模平行语料库进行模型训练，但对专业术语的关注有限。然而，在专利、金融或生物医学等领域，术语翻译至关重要，许多术语需遵循特定规范。本文提出了一种方法，能够在少量数据下高效训练模型，同时确保术语翻译的准确性。我们通过Trie Tree算法系统性地提取术语并创建词汇表，随后进行数据重建，教导LLM如何整合这些专业术语。该方法提升了模型处理专业术语的能力，确保了高质量的翻译，尤其在术语一致性至关重要的领域。我们的方法在WMT专利任务中表现卓越，取得了迄今为止最高的翻译分数，展示了其在专业翻译领域的有效性和广泛适用性，而通用方法往往在这些领域表现不佳。

> Traditional machine translation methods typically involve training models directly on large parallel corpora, with limited emphasis on specialized terminology. However, In specialized fields such as patent, finance, or biomedical domains, terminology is crucial for translation, with many terms that needs to be translated following agreed-upon conventions. In this paper we introduce a methodology that efficiently trains models with a smaller amount of data while preserving the accuracy of terminology translation. We achieve this through a systematic process of term extraction and glossary creation using the Trie Tree algorithm, followed by data reconstruction to teach the LLM how to integrate these specialized terms. This methodology enhances the model's ability to handle specialized terminology and ensures high-quality translations, particularly in fields where term consistency is crucial. Our approach has demonstrated exceptional performance, achieving the highest translation score among participants in the WMT patent task to date, showcasing its effectiveness and broad applicability in specialized translation domains where general methods often fall short.

[Arxiv](https://arxiv.org/abs/2410.15690)