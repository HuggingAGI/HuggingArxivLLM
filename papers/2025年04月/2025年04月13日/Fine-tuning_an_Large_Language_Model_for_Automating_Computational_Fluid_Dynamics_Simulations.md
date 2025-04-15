# # 微调大型语言模型，实现计算流体动力学模拟的自动化

发布时间：2025年04月13日

`LLM应用

理由：这篇论文探讨了将大型语言模型（LLM）应用于计算流体动力学（CFD）模拟配置的自动化过程。通过微调领域特定的LLM并结合多智能体框架，论文展示了LLM在科学计算中的实际应用，属于LLM应用类别。` `计算流体动力学`

> Fine-tuning an Large Language Model for Automating Computational Fluid Dynamics Simulations

# 摘要

> 配置计算流体动力学（CFD）模拟通常需要深厚的领域专业知识，这限制了更广泛的访问。尽管大型语言模型（LLMs）在科学计算方面取得了进展，但它们在自动化 CFD 工作流程方面的应用仍不成熟。我们提出了一种基于领域特定 LLM 适配的新方法。通过对 Qwen2.5-7B-Instruct 进行微调，使用我们的自定义数据集 NL2FOAM，其中包含 28716 个自然语言到 OpenFOAM 配置对，并带有链式思维（CoT）注释，我们实现了从自然语言描述到可执行 CFD 设置的直接翻译。一个多智能体框架协调整个过程，自主验证输入、生成配置、运行模拟并纠正错误。在包含 21 个不同流动案例的基准上进行评估，结果显示了最先进的性能，实现了 88.7% 的解决方案准确性和 82.6% 的首次尝试成功率。这显著优于更大规模的通用模型如 Qwen2.5-72B-Instruct、DeepSeek-R1 和 Llama3.3-70B-Instruct，同时减少了校正迭代次数并保持了高计算效率。结果突显了领域特定适配在部署 LLM 助手处理复杂工程工作流程中的关键作用。

> Configuring computational fluid dynamics (CFD) simulations typically demands extensive domain expertise, limiting broader access. Although large language models (LLMs) have advanced scientific computing, their use in automating CFD workflows is underdeveloped. We introduce a novel approach centered on domain-specific LLM adaptation. By fine-tuning Qwen2.5-7B-Instruct on NL2FOAM, our custom dataset of 28716 natural language-to-OpenFOAM configuration pairs with chain-of-thought (CoT) annotations, we enable direct translation from natural language descriptions to executable CFD setups. A multi-agent framework orchestrates the process, autonomously verifying inputs, generating configurations, running simulations, and correcting errors. Evaluation on a benchmark of 21 diverse flow cases demonstrates state-of-the-art performance, achieving 88.7% solution accuracy and 82.6% first-attempt success rate. This significantly outperforms larger general-purpose models like Qwen2.5-72B-Instruct, DeepSeek-R1, and Llama3.3-70B-Instruct, while also requiring fewer correction iterations and maintaining high computational efficiency. The results highlight the critical role of domain-specific adaptation in deploying LLM assistants for complex engineering workflows.

[Arxiv](https://arxiv.org/abs/2504.09602)