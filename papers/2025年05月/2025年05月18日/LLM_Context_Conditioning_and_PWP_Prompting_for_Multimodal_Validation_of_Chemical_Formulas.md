# 大型语言模型的上下文调节与PWP提示，实现化学公式的多模态验证

发布时间：2025年05月18日

`LLM应用` `科学文档` `技术文档`

> LLM Context Conditioning and PWP Prompting for Multimodal Validation of Chemical Formulas

# 摘要

> 在复杂科学和技术文档中，尤其是涉及多模态解读（如图像中的公式）时，识别细微的技术错误对大型语言模型（LLMs）来说是一项重大挑战。LLMs固有的纠错倾向可能会掩盖不准确之处。本研究是一项探索性的概念验证（PoC）研究，旨在通过基于持续工作流提示（PWP）原则的结构化LLM上下文条件设置，作为一种方法论策略，来调节LLM在推理时的行为。这种方法旨在增强现成通用型LLM（具体为Gemini 2.5 Pro和ChatGPT Plus o3）在精准验证任务中的可靠性，仅依赖其标准聊天界面，无需API访问或模型修改。为了探索这一方法，我们专注于验证一份包含已知文本和图像错误的复杂测试论文中的化学公式。评估了多种提示策略：虽然基本提示不可靠，但一种将PWP结构应用于严格条件设置LLM分析思维的方法似乎能提高文本错误识别的准确性。值得注意的是，这种方法还引导Gemini 2.5 Pro多次识别出之前人工审查中被忽视的细微图像公式错误，而ChatGPT Plus o3在此任务中未能成功。这些初步发现揭示了特定LLM运行模式如何阻碍细节导向的验证，并表明基于PWP的上下文条件设置提供了一种有前景且高度可访问的技术，用于开发更稳健的LLM驱动分析工作流程，特别是在需要在科学和技术文档中细致检测错误的任务中。需要进行更广泛的验证，以确定这一方法的更广泛应用前景。

> Identifying subtle technical errors within complex scientific and technical documents, especially those requiring multimodal interpretation (e.g., formulas in images), presents a significant hurdle for Large Language Models (LLMs) whose inherent error-correction tendencies can mask inaccuracies. This exploratory proof-of-concept (PoC) study investigates structured LLM context conditioning, informed by Persistent Workflow Prompting (PWP) principles, as a methodological strategy to modulate this LLM behavior at inference time. The approach is designed to enhance the reliability of readily available, general-purpose LLMs (specifically Gemini 2.5 Pro and ChatGPT Plus o3) for precise validation tasks, crucially relying only on their standard chat interfaces without API access or model modifications. To explore this methodology, we focused on validating chemical formulas within a single, complex test paper with known textual and image-based errors. Several prompting strategies were evaluated: while basic prompts proved unreliable, an approach adapting PWP structures to rigorously condition the LLM's analytical mindset appeared to improve textual error identification with both models. Notably, this method also guided Gemini 2.5 Pro to repeatedly identify a subtle image-based formula error previously overlooked during manual review, a task where ChatGPT Plus o3 failed in our tests. These preliminary findings highlight specific LLM operational modes that impede detail-oriented validation and suggest that PWP-informed context conditioning offers a promising and highly accessible technique for developing more robust LLM-driven analytical workflows, particularly for tasks requiring meticulous error detection in scientific and technical documents. Extensive validation beyond this limited PoC is necessary to ascertain broader applicability.

[Arxiv](https://arxiv.org/abs/2505.12257)