# Farseer：大型语言模型的优化缩放定律

发布时间：2025年06月12日

`LLM应用` `人工智能`

> Farseer: A Refined Scaling Law in Large Language Models

# 摘要

> 训练大型语言模型 (LLMs) 的成本极其高昂，导致小规模实验的成果难以直接应用于大规模生产系统，严重阻碍了创新效率。为解决这一难题，我们提出了 Farseer，一种新型优化的缩放定律，显著提升了跨尺度的预测精度。通过系统构建模型损失曲面 $L(N,D)$，Farseer 在拟合实际数据方面远超先前的定律（如 Chinchilla 定律）。我们的方法不仅预测精准、稳健，还具有强大的泛化能力，展现出卓越的外推能力，与 Chinchilla 定律相比，外推误差降低了 433%。这使我们能够全面评估各种 $(N,D)$ 设置下的训练策略，并能将小规模实验的结论可靠地外推至大规模场景，从而准确预测大规模性能。此外，Farseer 还为最优计算资源分配提供了全新视角，更好地满足现代 LLM 训练的多样化需求。为验证我们的方法，我们在不同规模和配置下训练了约 1,000 个 LLM，耗时约 300 万个 NVIDIA H100 GPU 小时。我们已全面开源所有模型、数据、结果和日志至 https://github.com/Farseer-Scaling-Law/Farseer，以推动进一步研究。


> Training Large Language Models (LLMs) is prohibitively expensive, creating a critical scaling gap where insights from small-scale experiments often fail to transfer to resource-intensive production systems, thereby hindering efficient innovation. To bridge this, we introduce Farseer, a novel and refined scaling law offering enhanced predictive accuracy across scales. By systematically constructing a model loss surface $L(N,D)$, Farseer achieves a significantly better fit to empirical data than prior laws (e.g., Chinchilla's law). Our methodology yields accurate, robust, and highly generalizable predictions, demonstrating excellent extrapolation capabilities, improving upon Chinchilla's law by reducing extrapolation error by 433\%. This allows for the reliable evaluation of competing training strategies across all $(N,D)$ settings, enabling conclusions from small-scale ablation studies to be confidently extrapolated to predict large-scale performance. Furthermore, Farseer provides new insights into optimal compute allocation, better reflecting the nuanced demands of modern LLM training. To validate our approach, we trained an extensive suite of approximately 1,000 LLMs across diverse scales and configurations, consuming roughly 3 million NVIDIA H100 GPU hours. We are comprehensively open-sourcing all models, data, results, and logs at https://github.com/Farseer-Scaling-Law/Farseer to foster further research.

[Arxiv](https://arxiv.org/abs/2506.10972)