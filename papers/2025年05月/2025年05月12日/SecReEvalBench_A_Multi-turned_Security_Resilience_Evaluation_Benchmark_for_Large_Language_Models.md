# SecReEvalBench：面向大型语言模型的多轮安全韧性评估基准

发布时间：2025年05月12日

`LLM应用` `模型评估`

> SecReEvalBench: A Multi-turned Security Resilience Evaluation Benchmark for Large Language Models

# 摘要

> 随着大型语言模型在安全敏感领域的广泛应用，其抵御对抗性提示攻击的能力评估变得尤为重要。然而，先前的基准测试虽然关注了有限的攻击领域（如网络安全攻击），却未能全面评估意图驱动的对抗性提示，也忽视了基于真实场景的多轮攻击。为此，我们推出了SecReEvalBench——安全韧性评估基准，该基准提出了四个创新指标：提示攻击韧性评分、提示攻击拒绝逻辑评分、链式攻击韧性评分和链式攻击拒绝时间评分。此外，我们设计了六种提问序列用于模型评估，包括单次攻击、连续攻击、连续逆向攻击、交替攻击、威胁等级逐步升高的序列攻击以及威胁等级逐步降低的序列攻击。我们还构建了一个专为该基准设计的数据集，包含中性和恶意提示，涵盖七个安全领域和十六种攻击技术。通过对Llama 3.1、Gemma 2、Mistral v0.3、DeepSeek-R1和Qwen 3等五种先进开源大型语言模型的系统评估，我们揭示了这些模型在防御不断演变的对抗性威胁方面的优缺点。SecReEvalBench数据集现已在Kaggle上公开（链接：https://kaggle.com/datasets/5a7ee22cf9dab6c93b55a73f630f6c9b42e936351b0ae98fbae6ddaca7fe248d），为推动大型语言模型安全研究提供了坚实基础。

> The increasing deployment of large language models in security-sensitive domains necessitates rigorous evaluation of their resilience against adversarial prompt-based attacks. While previous benchmarks have focused on security evaluations with limited and predefined attack domains, such as cybersecurity attacks, they often lack a comprehensive assessment of intent-driven adversarial prompts and the consideration of real-life scenario-based multi-turn attacks. To address this gap, we present SecReEvalBench, the Security Resilience Evaluation Benchmark, which defines four novel metrics: Prompt Attack Resilience Score, Prompt Attack Refusal Logic Score, Chain-Based Attack Resilience Score and Chain-Based Attack Rejection Time Score. Moreover, SecReEvalBench employs six questioning sequences for model assessment: one-off attack, successive attack, successive reverse attack, alternative attack, sequential ascending attack with escalating threat levels and sequential descending attack with diminishing threat levels. In addition, we introduce a dataset customized for the benchmark, which incorporates both neutral and malicious prompts, categorised across seven security domains and sixteen attack techniques. In applying this benchmark, we systematically evaluate five state-of-the-art open-weighted large language models, Llama 3.1, Gemma 2, Mistral v0.3, DeepSeek-R1 and Qwen 3. Our findings offer critical insights into the strengths and weaknesses of modern large language models in defending against evolving adversarial threats. The SecReEvalBench dataset is publicly available at https://kaggle.com/datasets/5a7ee22cf9dab6c93b55a73f630f6c9b42e936351b0ae98fbae6ddaca7fe248d, which provides a groundwork for advancing research in large language model security.

[Arxiv](https://arxiv.org/abs/2505.07584)