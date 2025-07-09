# SynapseRoute: 一种基于双态大型语言模型的自动路由切换框架

发布时间：2025年07月03日

`LLM应用` `系统优化`

> SynapseRoute: An Auto-Route Switching Framework on Dual-State Large Language Model

# 摘要

> 随着大型语言模型（LLMs）在实际应用中的普及，选择合适的模型需要在性能和运营成本之间找到平衡。具有推理能力的模型的出现，进一步拉大了“思考”（高推理）与“非思考”（快速、低成本）模式之间的成本差距。本研究发现，约58%的医学问题仅通过“非思考”模式即可准确回答，无需复杂的推理过程。这一发现凸显了问题复杂度的二元分化，并表明根据问题复杂度动态路由查询至合适的模式，可以优化准确率、成本效益和用户体验。为此，我们提出了基于机器学习的动态路由框架SynapseRoute，它能智能地将输入查询分配到“思考”或“非思考”模式。在多个医学数据集上的实验结果显示，与仅使用“思考”模式相比，SynapseRoute不仅将整体准确率提升了0.8390（对比0.8272），还将推理时间减少了36.8%，token消耗降低了39.66%。此外，定性分析表明，对简单查询的过度推理不仅会导致不必要的延迟，还可能降低准确率，而我们的自适应路由则避免了这一问题。最后，本研究引入了准确率-推理-Token（AIT）指数，以全面评估准确率、延迟和token成本之间的权衡。

> With the widespread adoption of large language models (LLMs) in practical applications, selecting an appropriate model requires balancing not only performance but also operational cost. The emergence of reasoning-capable models has further widened the cost gap between "thinking" (high reasoning) and "non-thinking" (fast, low-cost) modes. In this work, we reveal that approximately 58% of medical questions can be accurately answered by the non-thinking mode alone, without requiring the high-cost reasoning process. This highlights a clear dichotomy in problem complexity and suggests that dynamically routing queries to the appropriate mode based on complexity could optimize accuracy, cost-efficiency, and overall user experience. Based on this, we further propose SynapseRoute, a machine learning-based dynamic routing framework that intelligently assigns input queries to either thinking or non-thinking modes. Experimental results on several medical datasets demonstrate that SynapseRoute not only improves overall accuracy (0.8390 vs. 0.8272) compared to the thinking mode alone but also reduces inference time by 36.8% and token consumption by 39.66%. Importantly, qualitative analysis indicates that over-reasoning on simpler queries can lead to unnecessary delays and even decreased accuracy, a pitfall avoided by our adaptive routing. Finally, this work further introduces the Accuracy-Inference-Token (AIT) index to comprehensively evaluate the trade-offs among accuracy, latency, and token cost.

[Arxiv](https://arxiv.org/abs/2507.02822)