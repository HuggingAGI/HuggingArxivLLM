# 前提增强推理链提升了LLMs在数学推理中的错误识别能力。

发布时间：2025年02月04日

`LLM理论

理由：这篇论文主要探讨了如何通过改进推理链的表示和验证方法来提升大型语言模型（LLMs）的数学推理能力。具体来说，论文提出了一种新的框架，将传统的线性推理链重构为有向无环图（PARC），并通过实验验证了该方法在前提识别和错误检测方面的有效性。这些研究内容属于对LLM推理能力的理论改进和优化，因此归类为“LLM理论”。` `数学推理` `人工智能`

> Premise-Augmented Reasoning Chains Improve Error Identification in Math reasoning with LLMs

# 摘要

> # 摘要
Chain-of-Thought (CoT) 提示通过提供详细的逐步解决方案，显著提升了大型语言模型（LLMs）的数学推理能力。然而，由于LLMs生成的推理链往往冗长，验证推理步骤和追踪因步骤间依赖关系而产生的问题变得更具挑战性。值得注意的是，数学推理允许每个步骤从推理链中前几个步骤的子集推导而来。本文提出了一种框架，通过识别每个步骤的前提来改进推理评估。我们将传统的线性推理链重构为Premise Augmented Reasoning Chains (PARC)，引入前提链接，形成有向无环图，其中节点代表步骤，边代表前提链接。通过我们构建的基于PARC的数据集PERL（Premises and ERrors identification in LLMs）的实验，我们证明了LLMs能够在复杂推理链中可靠地识别前提。特别是，开源LLMs在前提识别中的召回率高达90%。此外，PARC还能更可靠地识别推理链中的错误。在PARC中基于前提进行逐步验证时，错误识别的准确性提升了6%到16%。我们的研究结果表明，以前提为中心的表示在解决复杂问题任务中具有显著优势，并为提升基于LLM的推理评估可靠性开辟了新途径。

> Chain-of-Thought (CoT) prompting enhances mathematical reasoning in large language models (LLMs) by enabling detailed step-by-step solutions. However, due to the verbosity of LLMs, the resulting reasoning chains can be long, making it harder to verify the reasoning steps and trace issues resulting from dependencies between the steps that may be farther away in the sequence of steps. Importantly, mathematical reasoning allows each step to be derived from a small set of premises, which are a subset of the preceding steps in the reasoning chain. In this paper, we present a framework that identifies the premises for each step, to improve the evaluation of reasoning. We restructure conventional linear reasoning chains into Premise Augmented Reasoning Chains (PARC) by introducing premise links, resulting in a directed acyclic graph where the nodes are the steps and the edges are the premise links. Through experiments with a PARC-based dataset that we built, namely PERL (Premises and ERrors identification in LLMs), we demonstrate that LLMs can reliably identify premises within complex reasoning chains. In particular, even open-source LLMs achieve 90% recall in premise identification. We also show that PARC helps to identify errors in reasoning chains more reliably. The accuracy of error identification improves by 6% to 16% absolute when step-by-step verification is carried out in PARC under the premises. Our findings highlight the utility of premise-centric representations in addressing complex problem-solving tasks and open new avenues for improving the reliability of LLM-based reasoning evaluations.

[Arxiv](https://arxiv.org/abs/2502.02362)