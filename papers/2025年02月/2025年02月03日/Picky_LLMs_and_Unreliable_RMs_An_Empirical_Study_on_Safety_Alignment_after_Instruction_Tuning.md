# 挑剔的LLMs与不可靠的RMs：指令微调后安全对齐的实证研究

发布时间：2025年02月03日

`LLM理论

理由：这篇论文主要探讨了在微调大型语言模型（LLMs）时，如何保持模型的安全对齐性，并识别了导致安全对齐性下降的关键因素。论文还评估了奖励模型（RMs）在反映人类安全偏好方面的局限性。这些内容涉及LLMs的理论基础、微调过程中的安全性和对齐性问题，属于对LLMs的理论研究和分析，因此归类为LLM理论。` `人工智能`

> Picky LLMs and Unreliable RMs: An Empirical Study on Safety Alignment after Instruction Tuning

# 摘要

> 大型语言模型（LLMs）已成为解决广泛通用查询和任务的强大工具。然而，在较小的、特定领域的数据集上微调对齐的LLMs，尽管数据集是良性的，也可能无意中降低它们的安全对齐性，使模型更容易提供不适当的响应。本研究系统探讨了良性微调场景中导致安全对齐性下降的因素，识别了三个关键因素：答案结构、身份校准和角色扮演。此外，我们评估了最先进的奖励模型（RMs）的可靠性，发现它们经常无法准确反映人类在安全方面的偏好，突显了其在实际应用中的局限性。通过揭示这些挑战，我们的工作强调了在微调过程中保持安全对齐的复杂性，并为开发人员提供了帮助他们在LLMs中平衡实用性和安全性的指导。实验数据和代码可在https://github.com/GuanlinLee/llm_instruction_tuning获取。

> Large language models (LLMs) have emerged as powerful tools for addressing a wide range of general inquiries and tasks. Despite this, fine-tuning aligned LLMs on smaller, domain-specific datasets, critical to adapting them to specialized tasks, can inadvertently degrade their safety alignment, even when the datasets are benign. This phenomenon makes models more susceptible to providing inappropriate responses. In this study, we systematically examine the factors contributing to safety alignment degradation in benign fine-tuning scenarios. Our analysis identifies three critical factors affecting aligned LLMs: answer structure, identity calibration, and role-play. Additionally, we evaluate the reliability of state-of-the-art reward models (RMs), which are often used to guide alignment processes. Our findings reveal that these RMs frequently fail to accurately reflect human preferences regarding safety, underscoring their limitations in practical applications. By uncovering these challenges, our work highlights the complexities of maintaining safety alignment during fine-tuning and offers guidance to help developers balance utility and safety in LLMs. Datasets and fine-tuning code used in our experiments can be found in https://github.com/GuanlinLee/llm_instruction_tuning.

[Arxiv](https://arxiv.org/abs/2502.01116)