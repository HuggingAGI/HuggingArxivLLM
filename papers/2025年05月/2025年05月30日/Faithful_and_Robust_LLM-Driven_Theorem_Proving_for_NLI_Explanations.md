# 可靠且稳健的LLM驱动定理证明用于NLI解释

发布时间：2025年05月30日

`LLM应用` `人工智能`

> Faithful and Robust LLM-Driven Theorem Proving for NLI Explanations

# 摘要

> 自然语言解释在自然语言推理（NLI）中发挥着基础性作用，通过揭示前提如何逻辑蕴含假设。近期研究表明，大型语言模型（LLMs）与定理证明器（TPs）的交互能够有效验证并提升NLI解释的可靠性。然而，将自然语言转化为机器可验证的正式表示形式时，存在语义信息丢失和不忠实解释的风险，这一问题因LLMs在精确捕捉关键逻辑结构方面的能力不足而进一步加剧。此外，LLMs在形式化验证框架内构建严谨且稳健证明的能力仍显有限。为缓解与忠实性和稳健性相关的问题，本文提出了以下策略：（1）减少自动形式化过程中的语义损失；（2）高效识别并修正逻辑表示中的句法错误；（3）通过显式使用逻辑表达式引导LLMs生成结构化的证明草稿；（4）提升LLMs对TP反馈的解释能力以实现迭代改进。我们在e-SNLI、QASC和WorldTree数据集上使用不同LLMs进行的实证结果显示，所提出的策略在自动形式化（+18.46%、+34.2%、+39.77%）和解释改进（+29.5%、+51.5%、+41.25%）方面显著优于现有最优模型。此外，我们发现对混合LLM-TP架构的特定干预能够大幅提高效率，极大减少成功验证所需的迭代次数。

> Natural language explanations play a fundamental role in Natural Language Inference (NLI) by revealing how premises logically entail hypotheses. Recent work has shown that the interaction of large language models (LLMs) with theorem provers (TPs) can help verify and improve the validity of NLI explanations. However, TPs require translating natural language into machine-verifiable formal representations, a process that introduces the risk of semantic information loss and unfaithful interpretation, an issue compounded by LLMs' challenges in capturing critical logical structures with sufficient precision. Moreover, LLMs are still limited in their capacity for rigorous and robust proof construction within formal verification frameworks. To mitigate issues related to faithfulness and robustness, this paper investigates strategies to (1) alleviate semantic loss during autoformalisation, (2) efficiently identify and correct syntactic errors in logical representations, (3) explicitly use logical expressions to guide LLMs in generating structured proof sketches, and (4) increase LLMs' capacity of interpreting TP's feedback for iterative refinement. Our empirical results on e-SNLI, QASC and WorldTree using different LLMs demonstrate that the proposed strategies yield significant improvements in autoformalisation (+18.46%, +34.2%, +39.77%) and explanation refinement (+29.5%, +51.5%, +41.25%) over the state-of-the-art model. Moreover, we show that specific interventions on the hybrid LLM-TP architecture can substantially improve efficiency, drastically reducing the number of iterations required for successful verification.

[Arxiv](https://arxiv.org/abs/2505.24264)