# 链式思维推理在现实应用中并非总是可靠

发布时间：2025年03月11日

`LLM应用` `人工智能` `人工智能安全`

> Chain-of-Thought Reasoning In The Wild Is Not Always Faithful

# 摘要

> CoT推理显著提升了当前最先进的AI能力，然而近期研究表明，其推理过程并非总是可靠。与以往研究多关注于不自然情境中的偏见问题不同，我们发现即使在没有人工偏见的现实提示中，模型也可能出现不忠实的CoT推理。研究结果显示，前沿模型在多种不忠实推理形式上的表现令人担忧：Sonnet 3.7（30.6%）、DeepSeek R1（15.8%）和ChatGPT-4o（12.6%）在回答问题对时，有相当高比例的回答是不忠实的。具体而言，我们发现模型会在回答二元问题时，通过事后合理化来掩饰其隐性偏见。例如，当分别面对“X比Y大吗？”和“Y比X大吗？”这两个问题时，模型有时会生成表面上连贯的理由，以支持对两个问题都回答“是”或都回答“否”，尽管这种回答在逻辑上是自相矛盾的。我们还研究了推理修复错误（Dziri et al., 2023），即模型在推理过程中出现错误后自行纠正，以及在解决普特南问题（一个困难基准）时，模型使用明显不合逻辑的推理来简化问题的“不忠实捷径”。我们的发现对依赖通过监控CoT推理来检测不良行为的AI安全工作提出了挑战。

> Chain-of-Thought (CoT) reasoning has significantly advanced state-of-the-art AI capabilities. However, recent studies have shown that CoT reasoning is not always faithful, i.e. CoT reasoning does not always reflect how models arrive at conclusions. So far, most of these studies have focused on unfaithfulness in unnatural contexts where an explicit bias has been introduced. In contrast, we show that unfaithful CoT can occur on realistic prompts with no artificial bias. Our results reveal concerning rates of several forms of unfaithful reasoning in frontier models: Sonnet 3.7 (30.6%), DeepSeek R1 (15.8%) and ChatGPT-4o (12.6%) all answer a high proportion of question pairs unfaithfully. Specifically, we find that models rationalize their implicit biases in answers to binary questions ("implicit post-hoc rationalization"). For example, when separately presented with the questions "Is X bigger than Y?" and "Is Y bigger than X?", models sometimes produce superficially coherent arguments to justify answering Yes to both questions or No to both questions, despite such responses being logically contradictory. We also investigate restoration errors (Dziri et al., 2023), where models make and then silently correct errors in their reasoning, and unfaithful shortcuts, where models use clearly illogical reasoning to simplify solving problems in Putnam questions (a hard benchmark). Our findings raise challenges for AI safety work that relies on monitoring CoT to detect undesired behavior.

[Arxiv](https://arxiv.org/abs/2503.08679)