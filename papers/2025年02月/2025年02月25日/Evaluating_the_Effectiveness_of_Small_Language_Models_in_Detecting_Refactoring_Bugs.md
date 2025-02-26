# 小型语言模型在检测重构漏洞方面的有效性评估

发布时间：2025年02月25日

`LLM应用

摘要讨论了小语言模型（SLMs）在检测重构错误中的应用，属于LLM的实际应用。` `软件工程` `编程工具`

> Evaluating the Effectiveness of Small Language Models in Detecting Refactoring Bugs

# 摘要

> # 摘要
流行的IDE中常常存在重构实现中的错误。确保重构后程序的行为不变是一项复杂的工作。传统方法依赖于为每种重构类型预定义先决条件，这限制了它们的可扩展性和对新重构的适应能力。这些方法通常需要大量的静态和动态分析，计算成本高、耗时长，且仍可能无法检测到某些重构错误。

本研究评估了小语言模型（SLMs）在检测Java和Python中的两类重构错误方面的有效性：(i) 引入错误或行为变化的重构（Type I）和(ii) 被IDE无故阻止的有效重构（Type II）。我们评估了Llama 3.2 3B、Mistral 7B、Gemma 2 9B、DeepSeek-R1 14B、Phi-4 14B、o1-mini和o3-mini-high等模型，看它们是否能准确检测到广泛使用的Java和Python IDE（如Eclipse和NetBeans）中报告的100个重构错误。本研究涵盖了16种重构类型，并通过零样本提示在消费级硬件上评估模型在未经显式训练情况下判断重构正确性的能力。

专有的o3-mini-high模型实现了最高的检测率，识别出84.3%的Type I错误。开源的Phi-4 14B表现同样出色，对两种错误类型都展示了强大的检测能力。然而，o3-mini-high在处理Type II错误时表现不佳，仅在40%的情况下能正确识别并应用被错误阻止的有效重构。

研究结果凸显了SLMs在高效检测重构错误方面的潜力，特别是在验证行为变化方面。此外，SLMs提供了更灵活的解决方案，能够跨不同重构类型和编程语言进行泛化，从而克服传统方法的关键限制。


> Popular IDEs frequently contain bugs in their refactoring implementations. Ensuring that a transformation preserves a program's behavior is a complex task. Traditional detection methods rely on predefined preconditions for each refactoring type, limiting their scalability and adaptability to new transformations. These methods often require extensive static and dynamic analyses, which are computationally expensive, time-consuming, and may still fail to detect certain refactoring bugs. This study evaluates the effectiveness of Small Language Models (SLMs) in detecting two types of refactoring bugs in Java and Python: (i) transformations that introduce errors or behavioral changes (Type I) and (ii) transformations unnecessarily blocked by IDEs despite being valid (Type II). We assess whether Llama 3.2 3B, Mistral 7B, Gemma 2 9B, DeepSeek-R1 14B, Phi-4 14B, o1-mini, and o3-mini-high can accurately detect 100 refactoring bugs reported in widely used Java and Python IDEs, such as Eclipse and NetBeans. The study covers 16 refactoring types and employs zero-shot prompting on consumer-grade hardware to evaluate the models' ability to reason about refactoring correctness without explicit prior training. The proprietary o3-mini-high model achieved the highest detection rate, identifying 84.3% of Type I bugs. The open-source Phi-4 14B performed comparably well, demonstrating strong effectiveness across both bug types. However, o3-mini-high struggled with Type II bugs, correctly identifying and applying valid but blocked transformations in only 40% of cases. The findings highlight the potential of SLMs for efficiently detecting refactoring bugs, particularly in verifying behavioral changes. Additionally, SLMs offer a more adaptable solution capable of generalizing across different refactoring types and programming languages, addressing key limitations of traditional approaches.

[Arxiv](https://arxiv.org/abs/2502.18454)