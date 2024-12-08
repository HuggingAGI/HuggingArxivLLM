# DroidCall：一个为 LLM 驱动的 Android 意图调用服务的数据集

发布时间：2024年11月30日

`Agent` `移动智能体` `安卓应用`

> DroidCall: A Dataset for LLM-powered Android Intent Invocation

# 摘要

> 大型语言模型在自然语言理解方面能力的不断提升，显著强化了现有的智能体系统。为了让设备上表现出色的移动智能体拥有更好的数据隐私，我们推出了 DroidCall，这是首个用于精准安卓意图调用的训练和测试数据集。凭借高度灵活且可复用的数据生成流水线，我们在 DroidCall 中构建了 1 万个样本。给定自然语言形式的任务指令，像 Qwen2.5 - 3B 和 Gemma2 - 2B 这类小型语言模型，用 DroidCall 进行微调后，在准确安卓意图调用方面能够接近甚至超越 GPT - 4o 的能力。我们还提供了一个配备这些微调模型的端到端安卓应用，来展示安卓意图调用的过程。代码和数据集可在 https://github.com/UbiquitousLearning/DroidCall 获取。

> The growing capabilities of large language models in natural language understanding significantly strengthen existing agentic systems. To power performant on-device mobile agents for better data privacy, we introduce DroidCall, the first training and testing dataset for accurate Android intent invocation. With a highly flexible and reusable data generation pipeline, we constructed 10k samples in DroidCall. Given a task instruction in natural language, small language models such as Qwen2.5-3B and Gemma2-2B fine-tuned with DroidCall can approach or even surpass the capabilities of GPT-4o for accurate Android intent invocation. We also provide an end-to-end Android app equipped with these fine-tuned models to demonstrate the Android intent invocation process. The code and dataset are available at https://github.com/UbiquitousLearning/DroidCall.

[Arxiv](https://arxiv.org/abs/2412.00402)