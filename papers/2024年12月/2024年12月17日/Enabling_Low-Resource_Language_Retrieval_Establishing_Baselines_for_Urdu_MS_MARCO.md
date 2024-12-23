# 实现低资源语言的检索：为乌尔都语 MS MARCO 确立基准

发布时间：2024年12月17日

`LLM应用` `信息检索` `多语言处理`

> Enabling Low-Resource Language Retrieval: Establishing Baselines for Urdu MS MARCO

# 摘要

> 随着信息检索（IR）领域对包容性的重视程度与日俱增，满足低资源语言的需求仍是重大挑战。本文推出首个大规模的乌尔都语 IR 数据集，它是通过机器翻译 MS MARCO 数据集而创建的。我们通过乌尔都语的零样本学习为 IR 确立了基线结果，接着将 mMARCO 多语言 IR 方法应用于这个新翻译的数据集。我们的发现表明，微调模型（Urdu-mT5-mMARCO）的平均倒数排名（MRR@10）达到 0.247，召回率@10 为 0.439，相比零样本结果有显著提升，展现出为乌尔都语使用者拓展 IR 访问的潜力。通过填补低资源语言使用者的访问缺口，此项工作不但推动了多语言 IR 研究，还突显了包容性 IR 技术在伦理和社会层面的重要性。这项工作为改善语言表征的难题与解决办法提供了宝贵见解，为未来的研究奠定了基础，尤其是对南亚语言而言，能够从本研究采用的适应性方法中获益。

> As the Information Retrieval (IR) field increasingly recognizes the importance of inclusivity, addressing the needs of low-resource languages remains a significant challenge. This paper introduces the first large-scale Urdu IR dataset, created by translating the MS MARCO dataset through machine translation. We establish baseline results through zero-shot learning for IR in Urdu and subsequently apply the mMARCO multilingual IR methodology to this newly translated dataset. Our findings demonstrate that the fine-tuned model (Urdu-mT5-mMARCO) achieves a Mean Reciprocal Rank (MRR@10) of 0.247 and a Recall@10 of 0.439, representing significant improvements over zero-shot results and showing the potential for expanding IR access for Urdu speakers. By bridging access gaps for speakers of low-resource languages, this work not only advances multilingual IR research but also emphasizes the ethical and societal importance of inclusive IR technologies. This work provides valuable insights into the challenges and solutions for improving language representation and lays the groundwork for future research, especially in South Asian languages, which can benefit from the adaptable methods used in this study.

[Arxiv](https://arxiv.org/abs/2412.12997)