# PseudoBridge：以伪代码为桥梁，实现代码检索中更优的语义与逻辑对齐

发布时间：2025年09月25日

`LLM应用` `工业与制造`

> PseudoBridge: Pseudo Code as the Bridge for Better Semantic and Logic Alignment in Code Retrieval

# 摘要

> 代码搜索旨在从海量代码库中精准定位与自然语言查询匹配的相关代码片段，是软件开发中的关键环节。近年来，预训练语言模型（PLMs）的应用有效弥合了非结构化自然语言（NL）与结构化编程语言（PL）之间的语义鸿沟，较传统信息检索和早期深度学习方法有显著改进。然而，现有基于PLM的方法仍面临两大核心挑战：一是人类意图与机器执行逻辑存在根本性语义鸿沟，二是对多样化代码风格的鲁棒性不足。为解决这些问题，我们提出了PseudoBridge——一种新颖的代码检索框架，它引入伪代码作为中间半结构化模态，以更好地对齐自然语言语义与编程语言逻辑。具体而言，PseudoBridge包含两个阶段。第一阶段，利用先进的大型语言模型（LLM）合成伪代码，实现自然语言查询与伪代码的显式对齐。第二阶段，引入逻辑不变的代码风格增强策略，利用LLM基于伪代码生成风格多样但逻辑等效的代码实现，再将不同风格的代码片段与伪代码对齐，从而增强模型对代码风格变化的鲁棒性。我们在10种不同的PLM上构建了PseudoBridge，并在6种主流编程语言上进行了评估。大量实验表明，PseudoBridge在性能上持续优于基线模型，在检索准确率和泛化能力方面均有显著提升，尤其在Solidity和XLCoST数据集等零样本领域迁移场景中表现突出。这些结果验证了通过伪代码实现显式逻辑对齐的有效性，并凸显了PseudoBridge作为稳健、可泛化的代码检索解决方案的潜力。

> Code search aims to precisely find relevant code snippets that match natural language queries within massive codebases, playing a vital role in software development. Recent advances leverage pre-trained language models (PLMs) to bridge the semantic gap between unstructured natural language (NL) and structured programming languages (PL), yielding significant improvements over traditional information retrieval and early deep learning approaches. However, existing PLM-based methods still encounter key challenges, including a fundamental semantic gap between human intent and machine execution logic, as well as limited robustness to diverse code styles. To address these issues, we propose PseudoBridge, a novel code retrieval framework that introduces pseudo-code as an intermediate, semi-structured modality to better align NL semantics with PL logic. Specifically, PseudoBridge consists of two stages. First, we employ an advanced large language model (LLM) to synthesize pseudo-code, enabling explicit alignment between NL queries and pseudo-code. Second, we introduce a logic-invariant code style augmentation strategy and employ the LLM to generate stylistically diverse yet logically equivalent code implementations with pseudo-code, then align the code snippets of different styles with pseudo-code, enhancing model robustness to code style variation. We build PseudoBridge across 10 different PLMs and evaluate it on 6 mainstream programming languages. Extensive experiments demonstrate that PseudoBridge consistently outperforms baselines, achieving significant gains in retrieval accuracy and generalization, particularly under zero-shot domain transfer scenarios such as Solidity and XLCoST datasets. These results demonstrate the effectiveness of explicit logical alignment via pseudo-code and highlight PseudoBridge's potential as a robust, generalizable solution for code retrieval.

[Arxiv](https://arxiv.org/abs/2509.20881)