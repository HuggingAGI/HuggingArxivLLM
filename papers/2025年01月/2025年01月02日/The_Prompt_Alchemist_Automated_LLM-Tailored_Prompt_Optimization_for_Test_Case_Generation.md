# 提示炼金术士：自动化LLM定制提示优化，助力测试用例生成

发布时间：2025年01月02日

`LLM应用

**理由**：这篇论文主要讨论了如何利用大型语言模型（LLMs）为源代码生成有效的测试用例，并指出了现有方法在提示优化方面的不足。这属于LLM在实际应用中的使用，特别是如何通过优化提示来提升LLM在特定任务（如测试用例生成）中的表现。因此，将其分类为“LLM应用”是合适的。` `软件测试`

> The Prompt Alchemist: Automated LLM-Tailored Prompt Optimization for Test Case Generation

# 摘要

> 测试用例是验证软件可靠性和质量的关键。最近的研究显示，大型语言模型（LLMs）能够为源代码生成有效的测试用例。然而，现有方法主要依赖人工编写的简单提示，这往往导致效果不佳，因为LLMs的表现受提示影响很大。此外，这些方法对所有LLMs使用相同的提示，忽略了不同LLMs可能适合不同提示的事实。鉴于提示表述的多样性，自动为每个LLM找到最佳提示是一个巨大挑战。尽管自然语言处理领域有自动提示优化的方法，但它们难以生成有效的测试用例提示。首先，这些方法通过简单组合和变异现有提示来优化，缺乏指导，导致提示缺乏多样性，且生成的测试用例常重复相同错误。其次，这些提示通常缺乏领域知识，限制了LLMs的表现。

> Test cases are essential for validating the reliability and quality of software applications. Recent studies have demonstrated the capability of Large Language Models (LLMs) to generate useful test cases for given source code. However, the existing work primarily relies on human-written plain prompts, which often leads to suboptimal results since the performance of LLMs can be highly influenced by the prompts. Moreover, these approaches use the same prompt for all LLMs, overlooking the fact that different LLMs might be best suited to different prompts. Given the wide variety of possible prompt formulations, automatically discovering the optimal prompt for each LLM presents a significant challenge. Although there are methods on automated prompt optimization in the natural language processing field, they are hard to produce effective prompts for the test case generation task. First, the methods iteratively optimize prompts by simply combining and mutating existing ones without proper guidance, resulting in prompts that lack diversity and tend to repeat the same errors in the generated test cases. Second, the prompts are generally lack of domain contextual knowledge, limiting LLMs' performance in the task.

[Arxiv](https://arxiv.org/abs/2501.01329)