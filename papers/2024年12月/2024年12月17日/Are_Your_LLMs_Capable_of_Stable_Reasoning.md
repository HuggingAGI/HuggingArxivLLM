# 您的大型语言模型具备稳定推理的能力吗？

发布时间：2024年12月17日

`LLM应用` `评估方法`

> Are Your LLMs Capable of Stable Reasoning?

# 摘要

> 大型语言模型（LLMs）发展迅猛，在复杂推理任务方面成果斐然。但基准性能与实际应用之间仍存在巨大差距。我们觉得这主要是因为当前的评估协议和指标无法全面展现LLM的能力，尤其是在复杂推理任务中，准确性和一致性都极为关键。本研究有两大关键贡献。其一，我们推出了G-Pass@k这一全新评估指标，能通过多次采样尝试对模型性能进行持续评估，量化模型的峰值性能潜力及其稳定性。其二，我们构建了LiveMathBench这一动态基准，涵盖了颇具挑战性的当代数学难题，旨在最大程度降低评估期间的数据泄露风险。通过在最先进的LLM上利用LiveMathBench开展广泛实验并使用G-Pass@k，我们对其最大能力和操作一致性有了全面深入的认识。我们的发现表明，LLM的“实际”推理能力尚有很大提升空间，凸显出需要更有力的评估方法。基准和详细结果见：https://github.com/open-compass/GPassK 。

> The rapid advancement of Large Language Models (LLMs) has demonstrated remarkable progress in complex reasoning tasks. However, a significant discrepancy persists between benchmark performances and real-world applications. We identify this gap as primarily stemming from current evaluation protocols and metrics, which inadequately capture the full spectrum of LLM capabilities, particularly in complex reasoning tasks where both accuracy and consistency are crucial. This work makes two key contributions. First, we introduce G-Pass@k, a novel evaluation metric that provides a continuous assessment of model performance across multiple sampling attempts, quantifying both the model's peak performance potential and its stability. Second, we present LiveMathBench, a dynamic benchmark comprising challenging, contemporary mathematical problems designed to minimize data leakage risks during evaluation. Through extensive experiments using G-Pass@k on state-of-the-art LLMs with LiveMathBench, we provide comprehensive insights into both their maximum capabilities and operational consistency. Our findings reveal substantial room for improvement in LLMs' "realistic" reasoning capabilities, highlighting the need for more robust evaluation methods. The benchmark and detailed results are available at: https://github.com/open-compass/GPassK.

[Arxiv](https://arxiv.org/abs/2412.13147)