# ISACL：针对版权训练数据泄露的内部状态分析器

发布时间：2025年08月25日

`LLM应用` `法律科技`

> ISACL: Internal State Analyzer for Copyrighted Training Data Leakage

# 摘要

> 大型语言模型（LLMs）虽彻底革新了自然语言处理（NLP），却存在无意中泄露受版权保护或专有数据的风险——尤其是当这些数据仅用于训练、并不打算对外分发时。传统方法仅在内容生成后才着手处理这些泄露问题，这难免会造成敏感信息的外泄。本研究提出了一种主动防御方案：在文本生成前对LLMs的内部状态进行检测，以识别潜在的泄露风险。我们利用精心构建的受版权保护材料数据集，训练了一个神经网络分类器来识别风险，进而可通过终止生成过程或调整输出内容进行早期干预，避免信息泄露。该框架与检索增强生成（RAG）系统集成后，既能确保符合版权及许可要求，又能提升数据隐私保护水平与伦理标准。研究结果显示，对内部状态的分析可有效降低受版权保护数据的泄露风险，所提出的方案具备可扩展性，能无缝融入AI工作流，在确保遵守版权法规的同时，还能维持高质量的文本生成。相关实现代码已在GitHub上开源。ootnote{https://github.com/changhu73/Internal_states_leakage}

> Large Language Models (LLMs) have revolutionized Natural Language Processing (NLP) but pose risks of inadvertently exposing copyrighted or proprietary data, especially when such data is used for training but not intended for distribution. Traditional methods address these leaks only after content is generated, which can lead to the exposure of sensitive information. This study introduces a proactive approach: examining LLMs' internal states before text generation to detect potential leaks. By using a curated dataset of copyrighted materials, we trained a neural network classifier to identify risks, allowing for early intervention by stopping the generation process or altering outputs to prevent disclosure. Integrated with a Retrieval-Augmented Generation (RAG) system, this framework ensures adherence to copyright and licensing requirements while enhancing data privacy and ethical standards. Our results show that analyzing internal states effectively mitigates the risk of copyrighted data leakage, offering a scalable solution that fits smoothly into AI workflows, ensuring compliance with copyright regulations while maintaining high-quality text generation. The implementation is available on GitHub.\footnote{https://github.com/changhu73/Internal_states_leakage}

[Arxiv](https://arxiv.org/abs/2508.17767)