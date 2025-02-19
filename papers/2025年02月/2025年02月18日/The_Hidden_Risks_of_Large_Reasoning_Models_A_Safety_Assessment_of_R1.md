# 大型推理模型的潜在风险：R1安全评估研究

发布时间：2025年02月18日

`LLM应用

理由：这篇论文主要研究大型语言模型（LLMs）的安全性，特别是开源推理模型DeepSeek-R1在对抗攻击中的脆弱性。研究通过安全基准测试和攻击测试评估模型的合规性，探讨了模型推理能力越强可能带来的更大危害，以及模型思考过程中的安全风险。这些内容属于大语言模型在实际应用中的安全性问题，因此归类为LLM应用。` `信息安全`

> The Hidden Risks of Large Reasoning Models: A Safety Assessment of R1

# 摘要

> 大型推理模型（如 OpenAI-o3 和 DeepSeek-R1）在复杂推理能力上显著超越了不具备推理能力的大语言模型（LLMs）。然而，这些模型的强大能力，尤其是开源模型 DeepSeek-R1 的广泛可访问性，引发了严重的安全担忧，尤其是在滥用风险方面。本研究对这些推理模型进行了全面的安全评估，利用现有安全基准测试评估其合规性。同时，我们深入研究了模型在对抗攻击（如越狱攻击和提示注入）中的脆弱性，以评估其在实际应用中的稳健性。通过多维度分析，我们得出四个重要发现：(1) 开源 R1 模型与 o3-mini 模型在安全基准测试和攻击测试中存在显著差距，表明需要进一步加强对 R1 的安全优化。 (2) 蒸馏后的推理模型在安全性能上劣于其安全对齐的基线模型。 (3) 模型推理能力越强，在回答不安全问题时可能造成的危害也越大。 (4) R1 模型的思考过程相较于其最终答案更值得关注安全风险。本研究为推理模型的安全性提供了深刻见解，并强调了进一步提升 R1 模型安全性的必要性，以缩小现有差距。

> The rapid development of large reasoning models, such as OpenAI-o3 and DeepSeek-R1, has led to significant improvements in complex reasoning over non-reasoning large language models~(LLMs). However, their enhanced capabilities, combined with the open-source access of models like DeepSeek-R1, raise serious safety concerns, particularly regarding their potential for misuse. In this work, we present a comprehensive safety assessment of these reasoning models, leveraging established safety benchmarks to evaluate their compliance with safety regulations. Furthermore, we investigate their susceptibility to adversarial attacks, such as jailbreaking and prompt injection, to assess their robustness in real-world applications. Through our multi-faceted analysis, we uncover four key findings: (1) There is a significant safety gap between the open-source R1 models and the o3-mini model, on both safety benchmark and attack, suggesting more safety effort on R1 is needed. (2) The distilled reasoning model shows poorer safety performance compared to its safety-aligned base models. (3) The stronger the model's reasoning ability, the greater the potential harm it may cause when answering unsafe questions. (4) The thinking process in R1 models pose greater safety concerns than their final answers. Our study provides insights into the security implications of reasoning models and highlights the need for further advancements in R1 models' safety to close the gap.

[Arxiv](https://arxiv.org/abs/2502.12659)