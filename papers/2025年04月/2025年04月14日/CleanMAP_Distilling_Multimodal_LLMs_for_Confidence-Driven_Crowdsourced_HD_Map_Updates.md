# CleanMAP: 多模态大型语言模型蒸馏，用于自信度驱动的众包高精度地图更新

发布时间：2025年04月14日

`LLM应用` `智能网联汽车` `自动驾驶`

> CleanMAP: Distilling Multimodal LLMs for Confidence-Driven Crowdsourced HD Map Updates

# 摘要

> 智能网联汽车(ICVs)和车路云一体化系统的快速发展，使得对高精度地图实时准确更新的需求日益迫切。然而，由于众包数据存在运动模糊、光照变化、恶劣天气和车道标线退化等问题，确保地图可靠性仍面临挑战。本文提出CleanMAP，这是一个基于多模态大型语言模型(MLLM)的蒸馏框架，旨在通过过滤和优化众包数据，实现高置信度的高精地图更新。CleanMAP采用一种基于MLLM的车道可见性评分模型，系统量化关键视觉参数，并根据其对车道检测的影响程度，赋予0-10分的置信度评分。一种新型动态分段置信度评分函数会根据车道可见性自适应调整分数，在有效过滤不可靠数据的同时，与人工评估结果保持高度一致。为了进一步提升地图精度，提出了一种基于置信度的局部地图融合策略，该策略在最优置信度范围内(最佳分数减去10%)对局部地图进行排序和筛选，最终选取top-k高分地图进行融合，从而在数据质量和数量之间取得平衡。在真实自动驾驶车辆数据集上的实验验证了CleanMAP的有效性，结果显示融合前三名局部地图可实现最低的平均地图更新误差0.28米，优于基线方法(0.37米)，并满足严格的精度阈值(≤0.32米)。通过实车数据的进一步验证，CleanMAP与人工评估结果的匹配度达到84.88%，充分证明了模型的鲁棒性和可靠性。这项研究确立了CleanMAP作为众包高精地图更新的可扩展、可部署解决方案，为实现更精确可靠的自动驾驶导航提供了保障。代码将在https://Ankit-Zefan.github.io/CleanMap/公开。

> The rapid growth of intelligent connected vehicles (ICVs) and integrated vehicle-road-cloud systems has increased the demand for accurate, real-time HD map updates. However, ensuring map reliability remains challenging due to inconsistencies in crowdsourced data, which suffer from motion blur, lighting variations, adverse weather, and lane marking degradation. This paper introduces CleanMAP, a Multimodal Large Language Model (MLLM)-based distillation framework designed to filter and refine crowdsourced data for high-confidence HD map updates. CleanMAP leverages an MLLM-driven lane visibility scoring model that systematically quantifies key visual parameters, assigning confidence scores (0-10) based on their impact on lane detection. A novel dynamic piecewise confidence-scoring function adapts scores based on lane visibility, ensuring strong alignment with human evaluations while effectively filtering unreliable data. To further optimize map accuracy, a confidence-driven local map fusion strategy ranks and selects the top-k highest-scoring local maps within an optimal confidence range (best score minus 10%), striking a balance between data quality and quantity. Experimental evaluations on a real-world autonomous vehicle dataset validate CleanMAP's effectiveness, demonstrating that fusing the top three local maps achieves the lowest mean map update error of 0.28m, outperforming the baseline (0.37m) and meeting stringent accuracy thresholds (<= 0.32m). Further validation with real-vehicle data confirms 84.88% alignment with human evaluators, reinforcing the model's robustness and reliability. This work establishes CleanMAP as a scalable and deployable solution for crowdsourced HD map updates, ensuring more precise and reliable autonomous navigation. The code will be available at https://Ankit-Zefan.github.io/CleanMap/

[Arxiv](https://arxiv.org/abs/2504.10738)