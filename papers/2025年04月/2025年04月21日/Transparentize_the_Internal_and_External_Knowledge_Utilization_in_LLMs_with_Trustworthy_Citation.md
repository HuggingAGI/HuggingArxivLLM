# 揭示 LLMs 内部与外部知识利用机制，打造值得信赖的引用方式

发布时间：2025年04月21日

`RAG` `信息检索`

> Transparentize the Internal and External Knowledge Utilization in LLMs with Trustworthy Citation

# 摘要

> 尽管检索增强生成和引用生成在一定程度上缓解了大语言模型的幻觉问题，但模型对内部知识的利用机制仍然模糊不清，生成答案的可信度也令人存疑。为此，我们提出了基于上下文优先增强的引用生成任务，要求模型在生成引用时兼顾外部和内部知识，并提供可靠参考。我们设计了包含3个维度、共计5项的评估指标，涵盖答案 helpfulness、引用忠实度和可信度。为实现这一目标，我们提出了RAEL范式，并开发了INTRALIGN方法，该方法结合了传统数据生成技术和对齐算法。实验结果表明，我们的方法在跨场景性能上显著优于其他基线模型。进一步研究发现，检索质量、问题类型和模型知识储备对引用生成的可信度具有重要影响。

> While hallucinations of large language models could been alleviated through retrieval-augmented generation and citation generation, how the model utilizes internal knowledge is still opaque, and the trustworthiness of its generated answers remains questionable. In this work, we introduce Context-Prior Augmented Citation Generation task, requiring models to generate citations considering both external and internal knowledge while providing trustworthy references, with 5 evaluation metrics focusing on 3 aspects: answer helpfulness, citation faithfulness, and trustworthiness. We introduce RAEL, the paradigm for our task, and also design INTRALIGN, an integrated method containing customary data generation and an alignment algorithm. Our experimental results show that our method achieves a better cross-scenario performance with regard to other baselines. Our extended experiments further reveal that retrieval quality, question types, and model knowledge have considerable influence on the trustworthiness in citation generation.

[Arxiv](https://arxiv.org/abs/2504.14856)