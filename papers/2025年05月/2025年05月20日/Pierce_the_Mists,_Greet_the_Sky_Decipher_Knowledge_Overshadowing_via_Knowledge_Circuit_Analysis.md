# 拨云见日：解析知识遮蔽中的知识回路分析

发布时间：2025年05月20日

`LLM理论` `人工智能`

> Pierce the Mists, Greet the Sky: Decipher Knowledge Overshadowing via Knowledge Circuit Analysis

# 摘要

> 大型语言模型（LLMs）尽管功能强大，但受幻觉问题所限。其中一种特别具有挑战性的变体是知识覆盖现象，当一条激活的知识无意中掩盖了另一条相关知识时，即使使用高质量的训练数据，也会导致错误输出。目前对覆盖现象的理解大多局限于推理过程中的观察，缺乏对其在模型训练过程中起源和内部机制的深刻见解。因此，我们引入了PhantomCircuit，一个全新的框架，旨在全面分析和检测知识覆盖现象。通过创新性地运用知识电路分析，PhantomCircuit剖析了注意力头的内部工作原理，追踪了竞争性知识路径如何导致覆盖现象及其在整个训练过程中的演变。大量实验证明了PhantomCircuit在识别此类现象方面的有效性，为这一难以捉摸的幻觉现象提供了新的见解，并为研究界提供了一个新的方法论视角，以探索其潜在的缓解途径。

> Large Language Models (LLMs), despite their remarkable capabilities, are hampered by hallucinations. A particularly challenging variant, knowledge overshadowing, occurs when one piece of activated knowledge inadvertently masks another relevant piece, leading to erroneous outputs even with high-quality training data. Current understanding of overshadowing is largely confined to inference-time observations, lacking deep insights into its origins and internal mechanisms during model training. Therefore, we introduce PhantomCircuit, a novel framework designed to comprehensively analyze and detect knowledge overshadowing. By innovatively employing knowledge circuit analysis, PhantomCircuit dissects the internal workings of attention heads, tracing how competing knowledge pathways contribute to the overshadowing phenomenon and its evolution throughout the training process. Extensive experiments demonstrate PhantomCircuit's effectiveness in identifying such instances, offering novel insights into this elusive hallucination and providing the research community with a new methodological lens for its potential mitigation.

[Arxiv](https://arxiv.org/abs/2505.14406)