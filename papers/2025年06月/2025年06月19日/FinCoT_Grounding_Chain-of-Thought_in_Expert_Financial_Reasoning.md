# FinCoT：将链式思维融入专家级财务推理

发布时间：2025年06月19日

`LLM应用`

> FinCoT: Grounding Chain-of-Thought in Expert Financial Reasoning

# 摘要

> 本文介绍了一种名为 FinCoT 的结构化思维链（CoT）提示方法，该方法整合了特定领域专家的财务推理，用于指导大型语言模型的推理轨迹。我们发现，在 FinNLP 中主要有三种提示风格：（1）标准提示——零样本提示；（2）非结构化 CoT——未显式定义推理结构的 CoT 提示（如使用标签）；（3）结构化 CoT——带有显式指令或示例的 CoT 提示，这些指令或示例定义了结构化的推理步骤。此前，FinNLP 主要关注标准提示或非结构化 CoT 提示的提示工程，但结构化 CoT 提示在以往研究中并未受到足够重视。此外，结构化 CoT 提示中的推理结构设计往往基于非领域专家的启发式方法。本研究探讨了 FinNLP 中的每种提示方法，并在涵盖十个金融领域的 CFA 风格问题上评估了三种主要的提示风格和 FinCoT。结果显示，FinCoT 将性能从 63.2% 提升至 80.5%，并将 Qwen-2.5-7B-Instruct 的性能从 69.7% 提升至 74.2%，同时生成的令牌数量减少了八倍。研究发现表明，与领域对齐的结构化提示不仅提高了性能、降低了推理成本，还生成了更具可解释性和与专家一致的推理轨迹。

> This paper presents FinCoT, a structured chain-of-thought (CoT) prompting approach that incorporates insights from domain-specific expert financial reasoning to guide the reasoning traces of large language models. We investigate that there are three main prompting styles in FinNLP: (1) standard prompting--zero-shot prompting; (2) unstructured CoT--CoT prompting without an explicit reasoning structure, such as the use of tags; and (3) structured CoT prompting--CoT prompting with explicit instructions or examples that define structured reasoning steps. Previously, FinNLP has primarily focused on prompt engineering with either standard or unstructured CoT prompting. However, structured CoT prompting has received limited attention in prior work. Furthermore, the design of reasoning structures in structured CoT prompting is often based on heuristics from non-domain experts. In this study, we investigate each prompting approach in FinNLP. We evaluate the three main prompting styles and FinCoT on CFA-style questions spanning ten financial domains. We observe that FinCoT improves performance from 63.2% to 80.5% and Qwen-2.5-7B-Instruct from 69.7% to 74.2%, while reducing generated tokens eight-fold compared to structured CoT prompting. Our findings show that domain-aligned structured prompts not only improve performance and reduce inference costs but also yield more interpretable and expert-aligned reasoning traces.

[Arxiv](https://arxiv.org/abs/2506.16123)