# 生成、判别、进化：通过精细的句子级自我进化提升上下文忠实度

发布时间：2025年03月03日

`LLM理论` `问答系统`

> Generate, Discriminate, Evolve: Enhancing Context Faithfulness via Fine-Grained Sentence-Level Self-Evolution

# 摘要

> 提升大型语言模型的上下文忠实度对于构建可靠的知识增强生成系统至关重要，尤其是在长文本问答（LFQA）任务或涉及知识冲突的场景中。现有方法要么仅在推理阶段干预LLMs而未解决其内在局限，要么忽视了模型自我改进的可能性。本文中，我们提出了GenDiE（生成、判别、进化），一种新颖的自进化框架，通过细粒度的句子级优化来提升上下文忠实度。GenDiE结合了生成式和判别式训练，赋予LLMs自我生成和自我评分的能力，从而支持迭代式的自我进化。这不仅有助于构建模型对齐的数据，还支持推理过程中的评分引导搜索。此外，通过将响应中的每个句子视为独立的优化单元，GenDiE有效克服了以往方法在整体答案级别进行优化的局限性，避免遗漏不忠实的细节。在ASQA（领域内LFQA）和ConFiQA（领域外反事实问答）数据集上的实验表明，GenDiE在忠实度和正确性方面均超越了多种基线方法，并在领域适应中展现出强大的性能。

> Improving context faithfulness in large language models is essential for developing trustworthy retrieval augmented generation systems and mitigating hallucinations, especially in long-form question answering (LFQA) tasks or scenarios involving knowledge conflicts. Existing methods either intervene LLMs only at inference without addressing their inherent limitations or overlook the potential for self-improvement. In this paper, we introduce GenDiE (Generate, Discriminate, Evolve), a novel self-evolving framework that enhances context faithfulness through fine-grained sentence-level optimization. GenDiE combines both generative and discriminative training, equipping LLMs with self-generation and self-scoring capabilities to facilitate iterative self-evolution. This supports both data construction for model alignment and score-guided search during inference. Furthermore, by treating each sentence in a response as an independent optimization unit, GenDiE effectively addresses the limitations of previous approaches that optimize at the holistic answer level, which may miss unfaithful details. Experiments on ASQA (in-domain LFQA) and ConFiQA (out-of-domain counterfactual QA) datasets demonstrate that GenDiE surpasses various baselines in both faithfulness and correctness, and exhibits robust performance for domain adaptation.

[Arxiv](https://arxiv.org/abs/2503.01695)