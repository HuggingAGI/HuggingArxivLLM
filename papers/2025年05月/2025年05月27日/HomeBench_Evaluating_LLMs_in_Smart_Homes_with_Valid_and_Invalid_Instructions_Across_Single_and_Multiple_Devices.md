# HomeBench：基于有效与无效指令，跨设备评估智能家居中的大型语言模型

发布时间：2025年05月27日

`LLM应用` `智能家居` `对话系统`

> HomeBench: Evaluating LLMs in Smart Homes with Valid and Invalid Instructions Across Single and Multiple Devices

# 摘要

> 大型语言模型 (LLMs) 有望通过提升智能家居助手对用户需求的理解和回应能力，推动智能家居环境向更智能的方向发展。尽管近期研究将 LLMs 集成到智能家居系统中，但这些研究主要聚焦于处理简单有效的单一设备操作指令。然而，现实场景远比这复杂，用户常会发出无效指令或同时控制多个设备。这带来了两大挑战：LLMs 需要精准识别并修正用户指令中的错误，并完美执行多个指令。为解决这些问题并推动基于 LLM 的智能家居助手的发展，我们在本文中推出了 HomeBench，这是首个涵盖单设备和多设备有效及无效指令的智能家居数据集。我们在 13 种不同 LLM 上进行了实验，例如 GPT-4o 在处理无效多设备指令时的成功率仅为 0.0%，这表明即使借助 in-context learning、检索增强生成和微调，现有的先进 LLMs 在这种复杂场景下仍表现欠佳。我们的代码和数据集已在 https://github.com/BITHLP/HomeBench 开源。

> Large language models (LLMs) have the potential to revolutionize smart home assistants by enhancing their ability to accurately understand user needs and respond appropriately, which is extremely beneficial for building a smarter home environment. While recent studies have explored integrating LLMs into smart home systems, they primarily focus on handling straightforward, valid single-device operation instructions. However, real-world scenarios are far more complex and often involve users issuing invalid instructions or controlling multiple devices simultaneously. These have two main challenges: LLMs must accurately identify and rectify errors in user instructions and execute multiple user instructions perfectly. To address these challenges and advance the development of LLM-based smart home assistants, we introduce HomeBench, the first smart home dataset with valid and invalid instructions across single and multiple devices in this paper. We have experimental results on 13 distinct LLMs; e.g., GPT-4o achieves only a 0.0% success rate in the scenario of invalid multi-device instructions, revealing that the existing state-of-the-art LLMs still cannot perform well in this situation even with the help of in-context learning, retrieval-augmented generation, and fine-tuning. Our code and dataset are publicly available at https://github.com/BITHLP/HomeBench.

[Arxiv](https://arxiv.org/abs/2505.19628)