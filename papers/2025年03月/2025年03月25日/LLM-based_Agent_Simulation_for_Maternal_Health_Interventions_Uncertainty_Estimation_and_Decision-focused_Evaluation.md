# 基于大型语言模型的智能体模拟在孕产妇健康干预中的应用研究：不确定性估计与决策导向的评估方法

发布时间：2025年03月25日

`Agent` `公共卫生` `母婴健康`

> LLM-based Agent Simulation for Maternal Health Interventions: Uncertainty Estimation and Decision-focused Evaluation

# 摘要

> 基于代理的模拟在建模复杂人类行为方面发挥着重要作用，但传统方法需要依赖大量领域知识和大规模数据集支持。在医疗数据稀缺的环境下，由于历史和反事实数据有限，大型语言模型（LLMs）凭借其广泛的世界知识提供了一种有前景的替代方案。本研究聚焦于一个由LLM驱动的母婴移动健康项目模拟，旨在预测受益者在接收健康信息时的倾听行为，具体比较了通过自动化消息（对照组）和现场代表（干预组）两种信息来源的效果。鉴于不确定性量化在健康干预决策中的关键作用，我们提出了一种基于多样本二元熵的LLM知识不确定性估计方法。通过集成方法，我们显著提升了模型的鲁棒性，与单一模型相比，F1分数和模型校准效果均得到了显著提升。除了直接评估模型性能，我们还采取了以决策为导向的研究方法，重点展示LLM预测结果如何指导数据有限环境下的干预方案可行性和试验实施策略。该方法不仅适用于公共卫生和灾害响应领域，还为其他需要在数据严重受限条件下快速评估干预措施的领域提供了有效工具。本研究的所有代码和提示均可在GitHub上找到：https://github.com/sarahmart/LLM-ABS-ARMMAN-prediction.

> Agent-based simulation is crucial for modeling complex human behavior, yet traditional approaches require extensive domain knowledge and large datasets. In data-scarce healthcare settings where historic and counterfactual data are limited, large language models (LLMs) offer a promising alternative by leveraging broad world knowledge. This study examines an LLM-driven simulation of a maternal mobile health program, predicting beneficiaries' listening behavior when they receive health information via automated messages (control) or live representatives (intervention). Since uncertainty quantification is critical for decision-making in health interventions, we propose an LLM epistemic uncertainty estimation method based on binary entropy across multiple samples. We enhance model robustness through ensemble approaches, improving F1 score and model calibration compared to individual models. Beyond direct evaluation, we take a decision-focused approach, demonstrating how LLM predictions inform intervention feasibility and trial implementation in data-limited settings. The proposed method extends to public health, disaster response, and other domains requiring rapid intervention assessment under severe data constraints. All code and prompts used for this work can be found at https://github.com/sarahmart/LLM-ABS-ARMMAN-prediction.

[Arxiv](https://arxiv.org/abs/2503.22719)