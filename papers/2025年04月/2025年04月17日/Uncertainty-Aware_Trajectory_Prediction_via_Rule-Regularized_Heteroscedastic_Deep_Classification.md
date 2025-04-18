# # 考虑不确定性的轨迹预测方法：基于规则约束的异方差深度分类

发布时间：2025年04月17日

`LLM应用` `自动驾驶` `交通管理`

> Uncertainty-Aware Trajectory Prediction via Rule-Regularized Heteroscedastic Deep Classification

# 摘要

> 深度学习在轨迹预测领域展现了卓越的复杂交互捕捉能力，但其分布外泛化性能仍受制于数据不平衡和多样性不足的挑战。为突破这一瓶颈，我们提出了SHIFT框架——一个将精准不确定性建模与自动化规则提取相结合的创新方案。通过将轨迹预测转化为分类任务，并借助异方差谱归一化高斯过程，SHIFT实现了知识不确定性与偶然不确定性的确切分离。我们从自然语言驾驶规则（如停止规则和可驾驶性约束）中提取训练标签，并借助大型语言模型驱动的检索增强生成框架，构建了信息丰富的先验知识库。在nuScenes数据集上的全面测试，包括极具挑战性的低数据量和跨地点场景，均证实了SHIFT超越现有最先进方法，尤其在不确定性校准和位移指标方面表现突出。特别值得一提的是，在交叉路口等复杂场景中，SHIFT的卓越性能更是凸显无疑。项目页面：https://kumarmanas.github.io/SHIFT/。

> Deep learning-based trajectory prediction models have demonstrated promising capabilities in capturing complex interactions. However, their out-of-distribution generalization remains a significant challenge, particularly due to unbalanced data and a lack of enough data and diversity to ensure robustness and calibration. To address this, we propose SHIFT (Spectral Heteroscedastic Informed Forecasting for Trajectories), a novel framework that uniquely combines well-calibrated uncertainty modeling with informative priors derived through automated rule extraction. SHIFT reformulates trajectory prediction as a classification task and employs heteroscedastic spectral-normalized Gaussian processes to effectively disentangle epistemic and aleatoric uncertainties. We learn informative priors from training labels, which are automatically generated from natural language driving rules, such as stop rules and drivability constraints, using a retrieval-augmented generation framework powered by a large language model. Extensive evaluations over the nuScenes dataset, including challenging low-data and cross-location scenarios, demonstrate that SHIFT outperforms state-of-the-art methods, achieving substantial gains in uncertainty calibration and displacement metrics. In particular, our model excels in complex scenarios, such as intersections, where uncertainty is inherently higher. Project page: https://kumarmanas.github.io/SHIFT/.

[Arxiv](https://arxiv.org/abs/2504.13111)