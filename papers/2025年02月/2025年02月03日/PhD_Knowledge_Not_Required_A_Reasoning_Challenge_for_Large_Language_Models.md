# 无需博士知识：大型语言模型的推理挑战

发布时间：2025年02月03日

`LLM应用

解释：这篇论文主要讨论了如何通过一个新的基准测试来评估大型语言模型（LLM）的能力，特别是它们在一般知识推理任务中的表现。论文分析了不同模型在基准测试中的表现，并揭示了现有基准测试中未显现的能力差距和失败模式。这些内容与LLM在实际应用中的表现和优化相关，因此将其分类为LLM应用。` `人工智能` `基准测试`

> PhD Knowledge Not Required: A Reasoning Challenge for Large Language Models

# 摘要

> 现有的前沿模型基准测试通常考察的是高深的、``博士级别''的知识，这对非专家来说难以掌握。相比之下，我们提出了一个基于NPR周日谜题挑战的基准测试，只需一般知识即可参与。我们的基准测试对人类和模型都颇具挑战性，但正确答案易于验证，模型的错误也一目了然。
    我们的研究揭示了现有基准测试中未显现的能力差距：OpenAI o1在考察专业知识的基准测试中显著优于其他推理模型。此外，我们对推理输出的分析还发现了新的失败模式。例如，DeepSeek R1经常在提供明知错误的答案前认输，说``我放弃了''。R1的输出有时也表现出极大的``不确定性''，甚至在极少数情况下，它不会``完成思考''，这表明需要一种推理时间技术来在达到上下文窗口限制前``收尾''。我们还量化了R1和Gemini Thinking更长时间推理的效果，以确定在我们的基准测试中，超过某一点后，更多的推理对提高准确性帮助不大。

> Existing benchmarks for frontier models often test specialized, ``PhD-level'' knowledge that is difficult for non-experts to grasp. In contrast, we present a benchmark based on the NPR Sunday Puzzle Challenge that requires only general knowledge. Our benchmark is challenging for both humans and models, however correct solutions are easy to verify, and models' mistakes are easy to spot.
  Our work reveals capability gaps that are not evident in existing benchmarks: OpenAI o1 significantly outperforms other reasoning models that are on par on benchmarks that test specialized knowledge. Furthermore, our analysis of reasoning outputs uncovers new kinds of failures. DeepSeek R1, for instance, often concedes with ``I give up'' before providing an answer that it knows is wrong. R1 can also be remarkably ``uncertain'' in its output and in rare cases, it does not ``finish thinking,'' which suggests the need for an inference-time technique to ``wrap up'' before the context window limit is reached. We also quantify the effectiveness of reasoning longer with R1 and Gemini Thinking to identify the point beyond which more reasoning is unlikely to improve accuracy on our benchmark.

[Arxiv](https://arxiv.org/abs/2502.01584)