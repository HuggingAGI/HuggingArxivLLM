# RedStone：为大型语言模型精心整理通用、代码、数学及问答数据

发布时间：2024年12月04日

`LLM应用` `预训练数据集`

> RedStone: Curating General, Code, Math, and QA Data for Large Language Models

# 摘要

> 在高质量、精心整理的数据集中对大型语言模型（LLMs）进行预训练，被公认为对提升其性能和泛化能力至关重要。本研究挖掘了 Common Crawl 作为预训练 LLMs 全面且灵活的资源所蕴含的未开发潜力，既涉及通用语言理解，又涵盖专业领域知识。我们推出了 RedStone，这是一条创新且可扩展的管道，用于从 Common Crawl 中提取和处理数据，助力创建丰富多样的预训练数据集。传统数据集往往需要高昂的整理成本和特定领域的专业知识，而 RedStone 借助 Common Crawl 的广泛性，提供了针对众多领域定制的数据集。在本项工作中，我们通过在多个领域构建预训练数据集来展示其能力，包括通用语言理解、代码、数学和问答任务等。RedStone 的灵活性便于适应其他专业领域，极大地降低了创建有价值的特定领域数据集的门槛。我们的发现表明，通过像 RedStone 这样的有效管道加以利用，Common Crawl 能够成为丰富且可再生的预训练数据来源，为 LLMs 的领域适应和知识发现开辟新的道路。此项工作还突显了创新数据获取策略的重要性，以及网络规模数据作为 LLMs 持续发展的强大资源所发挥的作用。RedStone 代码和数据样本将在 url{https://aka.ms/redstone} 公开可用。

> Pre-training Large Language Models (LLMs) on high-quality, meticulously curated datasets is widely recognized as critical for enhancing their performance and generalization capabilities. This study explores the untapped potential of Common Crawl as a comprehensive and flexible resource for pre-training LLMs, addressing both general-purpose language understanding and specialized domain knowledge. We introduce RedStone, an innovative and scalable pipeline engineered to extract and process data from Common Crawl, facilitating the creation of extensive and varied pre-training datasets. Unlike traditional datasets, which often require expensive curation and domain-specific expertise, RedStone leverages the breadth of Common Crawl to deliver datasets tailored to a wide array of domains. In this work, we exemplify its capability by constructing pre-training datasets across multiple fields, including general language understanding, code, mathematics, and question-answering tasks. The flexibility of RedStone allows for easy adaptation to other specialized domains, significantly lowering the barrier to creating valuable domain-specific datasets. Our findings demonstrate that Common Crawl, when harnessed through effective pipelines like RedStone, can serve as a rich, renewable source of pre-training data, unlocking new avenues for domain adaptation and knowledge discovery in LLMs. This work also underscores the importance of innovative data acquisition strategies and highlights the role of web-scale data as a powerful resource in the continued evolution of LLMs. RedStone code and data samples will be publicly available at url{https://aka.ms/redstone}.

[Arxiv](https://arxiv.org/abs/2412.03398)