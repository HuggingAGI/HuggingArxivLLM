# 统一多模态大语言模型在图像生成中的公平性探讨

发布时间：2025年02月05日

`LLM理论

**理由**：这篇论文主要探讨了统一多模态大型语言模型（U-MLLMs）中的偏见问题，并提出了一种“定位-修复”策略来减少偏见。研究重点在于理解偏见的来源并提出理论上的解决方案，属于对大型语言模型的理论分析和改进，因此分类为LLM理论。` `人工智能` `社会偏见`

> On Fairness of Unified Multimodal Large Language Model for Image Generation

# 摘要

> 统一多模态大型语言模型（U-MLLMs）在视觉理解和生成方面表现出色，但其输出中的偏见问题也引发了新的关注。与仅生成模型（如Stable Diffusion）相比，U-MLLMs的统一能力可能导致偏见问题更加复杂。鉴于传播有害刻板印象的风险尚未被充分研究，这一问题尤为紧迫。本文对最新的U-MLLMs进行了基准测试，发现大多数模型在性别和种族等方面存在显著偏见。为此，我们提出了一种“定位-修复”策略，通过审计模型组件，揭示偏见的具体来源。分析表明，偏见主要来自语言模型。有趣的是，U-MLLMs中存在“部分对齐”现象：理解偏见较少，但生成偏见依然显著。为此，我们提出了一种基于合成数据的平衡偏好模型，实验证明该方法在保持语义准确性的同时有效减少了人口统计偏见。我们希望这一研究能推动未来对U-MLLMs的更全面解释和去偏见策略的探索。

> Unified multimodal large language models (U-MLLMs) have demonstrated impressive performance in visual understanding and generation in an end-to-end pipeline. Compared with generation-only models (e.g., Stable Diffusion), U-MLLMs may raise new questions about bias in their outputs, which can be affected by their unified capabilities. This gap is particularly concerning given the under-explored risk of propagating harmful stereotypes. In this paper, we benchmark the latest U-MLLMs and find that most exhibit significant demographic biases, such as gender and race bias. To better understand and mitigate this issue, we propose a locate-then-fix strategy, where we audit and show how the individual model component is affected by bias. Our analysis shows that bias originates primarily from the language model. More interestingly, we observe a "partial alignment" phenomenon in U-MLLMs, where understanding bias appears minimal, but generation bias remains substantial. Thus, we propose a novel balanced preference model to balance the demographic distribution with synthetic data. Experiments demonstrate that our approach reduces demographic bias while preserving semantic fidelity. We hope our findings underscore the need for more holistic interpretation and debiasing strategies of U-MLLMs in the future.

[Arxiv](https://arxiv.org/abs/2502.03429)