# MetaLLMix：一种XAI辅助的基于LLM元学习的超参数优化方法

发布时间：2025年09月11日

`LLM应用` `医疗健康`

> MetaLLMix : An XAI Aided LLM-Meta-learning Based Approach for Hyper-parameters Optimization

# 摘要

> 在深度学习领域，模型与超参数的高效选择一直是核心难题，往往需要深厚的专业积累与大量计算资源。尽管AutoML与大型语言模型（LLMs）为自动化带来希望，但现有基于LLM的方法依赖反复试错和昂贵的API，可解释性与泛化能力均有限。为此，我们提出MetaLLMiX——一个融合元学习、可解释AI与高效LLM推理的零样本超参数优化框架。该框架通过SHAP解释挖掘历史实验数据，无需额外试验即可推荐最优超参数与预训练模型。我们还引入LLM作为“评判者”进行评估，以确保输出格式规范、结果准确且内容完整。在8个医学影像数据集上使用9个开源轻量级LLM的实验表明，MetaLLMiX不仅性能媲美甚至超越传统HPO方法，还大幅降低了计算成本。本地部署版本更是超越了以往基于API的方案：在8项任务中5项取得最优结果，响应时间缩短99.6-99.9%，6个数据集的训练速度提升2.4-15.7倍，同时精度保持在最佳基线的1-5%范围内。

> Effective model and hyperparameter selection remains a major challenge in deep learning, often requiring extensive expertise and computation. While AutoML and large language models (LLMs) promise automation, current LLM-based approaches rely on trial and error and expensive APIs, which provide limited interpretability and generalizability. We propose MetaLLMiX, a zero-shot hyperparameter optimization framework combining meta-learning, explainable AI, and efficient LLM reasoning. By leveraging historical experiment outcomes with SHAP explanations, MetaLLMiX recommends optimal hyperparameters and pretrained models without additional trials. We further employ an LLM-as-judge evaluation to control output format, accuracy, and completeness. Experiments on eight medical imaging datasets using nine open-source lightweight LLMs show that MetaLLMiX achieves competitive or superior performance to traditional HPO methods while drastically reducing computational cost. Our local deployment outperforms prior API-based approaches, achieving optimal results on 5 of 8 tasks, response time reductions of 99.6-99.9%, and the fastest training times on 6 datasets (2.4-15.7x faster), maintaining accuracy within 1-5% of best-performing baselines.

[Arxiv](https://arxiv.org/abs/2509.09387)