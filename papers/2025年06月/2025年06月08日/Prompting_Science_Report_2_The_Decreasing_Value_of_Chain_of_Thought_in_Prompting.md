# 提示科学报告2：链式思维在提示中的价值正在下降

发布时间：2025年06月08日

`LLM应用`

> Prompting Science Report 2: The Decreasing Value of Chain of Thought in Prompting

# 摘要

> 这是系列简报的第二篇，旨在通过严格的测试帮助商业、教育和政策领袖理解与AI协作的技术细节。在这份报告中，我们探讨了链式思维提示（Chain-of-Thought, CoT），一种鼓励大型语言模型（LLM）"逐步思考"的技术（Wei et al., 2022）。CoT是一种广泛采用的提升推理任务效果的方法，然而，我们的研究揭示了其有效性更为复杂的一面。

研究发现：
- 链式思维提示的效果因任务类型和模型而异。对于非推理型模型，CoT通常能小幅提升平均表现，特别是当模型本身并不默认进行逐步处理时。然而，CoT也可能增加答案的变异性，有时会导致模型在本应正确回答的问题上出错。我们还发现，许多近期模型即使未被要求，也会进行某种形式的CoT推理；对于这些模型，要求进行CoT的影响微乎其微。进行CoT通常需要消耗大量tokens（增加成本和时间），远超直接回答。
- 针对具备显式推理能力设计的模型，CoT提示往往只会带来微乎其微甚至没有的准确性提升。然而，它显著增加了生成响应所需的时间和tokens。

> This is the second in a series of short reports that seek to help business, education, and policy leaders understand the technical details of working with AI through rigorous testing. In this report, we investigate Chain-of-Thought (CoT) prompting, a technique that encourages a large language model (LLM) to "think step by step" (Wei et al., 2022). CoT is a widely adopted method for improving reasoning tasks, however, our findings reveal a more nuanced picture of its effectiveness. We demonstrate two things:
  - The effectiveness of Chain-of-Thought prompting can vary greatly depending on the type of task and model. For non-reasoning models, CoT generally improves average performance by a small amount, particularly if the model does not inherently engage in step-by-step processing by default. However, CoT can introduce more variability in answers, sometimes triggering occasional errors in questions the model would otherwise get right. We also found that many recent models perform some form of CoT reasoning even if not asked; for these models, a request to perform CoT had little impact. Performing CoT generally requires far more tokens (increasing cost and time) than direct answers.
  - For models designed with explicit reasoning capabilities, CoT prompting often results in only marginal, if any, gains in answer accuracy. However, it significantly increases the time and tokens needed to generate a response.

[Arxiv](https://arxiv.org/abs/2506.07142)