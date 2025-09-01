# ISACL：针对版权训练数据泄露的内部状态分析器

发布时间：2025年08月25日

`LLM应用` `法律科技`

> ISACL: Internal State Analyzer for Copyrighted Training Data Leakage

# 摘要

> 大型语言模型（LLMs）彻底革新了自然语言处理（NLP），但也带来了无意中泄露受版权保护或专有数据的风险——尤其是当这类数据用于训练却不计划对外分发时。传统方法仅在内容生成后才处理这些泄露问题，这可能导致敏感信息外泄。本研究提出了一种主动预防方法：在文本生成前检查LLMs的内部状态，以检测潜在的泄露风险。我们利用精心筛选的受版权保护材料数据集，训练了一个神经网络分类器来识别风险，从而能够通过停止生成过程或修改输出来进行早期干预，防止信息泄露。该框架与检索增强生成（RAG）系统集成后，既能确保遵守版权和许可要求，又能提升数据隐私保护水平和伦理标准。研究结果显示，分析内部状态可有效降低受版权保护数据的泄露风险，提供了一种可扩展的解决方案，能无缝融入AI工作流，在确保遵守版权法规的同时，还能维持高质量的文本生成。本研究的实现代码已在GitHub上公开。ootnote{https://github.com/changhu73/Internal_states_leakage}

> Large Language Models (LLMs) have revolutionized Natural Language Processing (NLP) but pose risks of inadvertently exposing copyrighted or proprietary data, especially when such data is used for training but not intended for distribution. Traditional methods address these leaks only after content is generated, which can lead to the exposure of sensitive information. This study introduces a proactive approach: examining LLMs' internal states before text generation to detect potential leaks. By using a curated dataset of copyrighted materials, we trained a neural network classifier to identify risks, allowing for early intervention by stopping the generation process or altering outputs to prevent disclosure. Integrated with a Retrieval-Augmented Generation (RAG) system, this framework ensures adherence to copyright and licensing requirements while enhancing data privacy and ethical standards. Our results show that analyzing internal states effectively mitigates the risk of copyrighted data leakage, offering a scalable solution that fits smoothly into AI workflows, ensuring compliance with copyright regulations while maintaining high-quality text generation. The implementation is available on GitHub.\footnote{https://github.com/changhu73/Internal_states_leakage}

[Arxiv](https://arxiv.org/abs/2508.17767)