# 大型语言模型的可解释性研究：通过SMILE方法实现统计模型不可知的局部解释

发布时间：2025年05月27日

`LLM理论` `人工智能`

> Explainability of Large Language Models using SMILE: Statistical Model-agnostic Interpretability with Local Explanations

# 摘要

> GPT、LLAMA 和 Claude 等大型语言模型在文本生成方面已展现出非凡实力，但它们仍是黑箱模型，难以窥探其输出决策机制。这种不透明性在需要信任与责任的领域尤为棘手。为此，我们推出 SMILE，一种全新的方法，旨在揭示模型对提示不同部分的响应机制。SMILE 不依赖特定模型，通过微调输入内容，观察输出变化，从而识别出对结果影响最大的关键词。我们生成直观的可视化热图，突出提示中关键部分。在多个领先 LLM 上的测试表明，SMILE 以准确度、一致性、稳定性和保真度为标准，提供了清晰可靠的解释。通过让模型更易理解，SMILE 助推 AI 向透明与可信迈进一步。

> Large language models like GPT, LLAMA, and Claude have become incredibly powerful at generating text, but they are still black boxes, so it is hard to understand how they decide what to say. That lack of transparency can be problematic, especially in fields where trust and accountability matter. To help with this, we introduce SMILE, a new method that explains how these models respond to different parts of a prompt. SMILE is model-agnostic and works by slightly changing the input, measuring how the output changes, and then highlighting which words had the most impact. Create simple visual heat maps showing which parts of a prompt matter the most. We tested SMILE on several leading LLMs and used metrics such as accuracy, consistency, stability, and fidelity to show that it gives clear and reliable explanations. By making these models easier to understand, SMILE brings us one step closer to making AI more transparent and trustworthy.

[Arxiv](https://arxiv.org/abs/2505.21657)