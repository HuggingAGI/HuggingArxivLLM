# # TD-Interpreter：通过视觉语言学习增强时序图理解

发布时间：2025年07月20日

`LLM应用` `工程领域` `机器学习`

> TD-Interpreter: Enhancing the Understanding of Timing Diagrams with Visual-Language Learning

# 摘要

> 我们推出 TD-Interpreter，一款专为工程师设计的机器学习工具，旨在帮助他们在设计和验证流程中理解源自第三方的复杂时序图 (TD)。TD-Interpreter 是一个视觉问答环境，工程师可以输入一组时序图并针对这些时序图提出设计和验证相关的问题。我们通过微调轻量级 7B 多模态大型语言模型（MLLM）LLaVA，实现了 TD-Interpreter 的多模态学习功能。为了解决训练数据不足的问题，我们开发了一个合成数据生成工作流，将视觉信息与其文本解释对齐。实验评估结果表明，TD-Interpreter 具有显著的实用性，在评估基准上远超未经微调的 GPT-4o。

> We introduce TD-Interpreter, a specialized ML tool that assists engineers in understanding complex timing diagrams (TDs), originating from a third party, during their design and verification process. TD-Interpreter is a visual question-answer environment which allows engineers to input a set of TDs and ask design and verification queries regarding these TDs. We implemented TD-Interpreter with multimodal learning by fine-tuning LLaVA, a lightweight 7B Multimodal Large Language Model (MLLM). To address limited training data availability, we developed a synthetic data generation workflow that aligns visual information with its textual interpretation. Our experimental evaluation demonstrates the usefulness of TD-Interpreter which outperformed untuned GPT-4o by a large margin on the evaluated benchmarks.

[Arxiv](https://arxiv.org/abs/2507.16844)