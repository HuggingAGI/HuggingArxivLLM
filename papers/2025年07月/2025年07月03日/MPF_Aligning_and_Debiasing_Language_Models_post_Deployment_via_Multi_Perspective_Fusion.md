# MPF：通过多视角融合对齐并去偏见部署后的语言模型

发布时间：2025年07月03日

`LLM应用` `公平性` `人力资源`

> MPF: Aligning and Debiasing Language Models post Deployment via Multi Perspective Fusion

# 摘要

> 多视角融合（MPF）是一种为大型语言模型（LLMs）开发的新型后训练对齐框架，旨在应对日益增长的偏见缓解需求。MPF建立在SAGED管道之上，这是一个用于构建偏见基准并提取可解释基线分布的自动化系统。通过利用多角度生成，MPF能够揭示并使LLM输出中的偏见与微妙的人类基线相一致。通过将基线（如人力资源专业人士的情绪分布）分解为可解释的角度组件，MPF通过采样和平衡响应来引导生成，这些响应的权重基于分解过程中获得的概率。实证研究表明，MPF能够使LLM的情绪分布与反事实基线（绝对平等）以及人力资源基线（偏袒顶尖大学）对齐，从而实现较小的KL散度、校准误差的降低以及对未见问题的泛化能力。这表明MPF为对齐和偏见缓解提供了一种可扩展且可解释的方法，与已部署的LLMs兼容，且无需进行大量的提示工程或微调。

> Multiperspective Fusion (MPF) is a novel posttraining alignment framework for large language models (LLMs) developed in response to the growing need for easy bias mitigation. Built on top of the SAGED pipeline, an automated system for constructing bias benchmarks and extracting interpretable baseline distributions, MPF leverages multiperspective generations to expose and align biases in LLM outputs with nuanced, humanlike baselines. By decomposing baseline, such as sentiment distributions from HR professionals, into interpretable perspective components, MPF guides generation through sampling and balancing of responses, weighted by the probabilities obtained in the decomposition. Empirically, we demonstrate its ability to align LLM sentiment distributions with both counterfactual baselines (absolute equality) and the HR baseline (biased for Top Univeristy), resulting in small KL divergence, reduction of calibration error and generalization to unseen questions. This shows that MPF offers a scalable and interpretable method for alignment and bias mitigation, compatible with deployed LLMs and requiring no extensive prompt engineering or finetuning.

[Arxiv](https://arxiv.org/abs/2507.02595)