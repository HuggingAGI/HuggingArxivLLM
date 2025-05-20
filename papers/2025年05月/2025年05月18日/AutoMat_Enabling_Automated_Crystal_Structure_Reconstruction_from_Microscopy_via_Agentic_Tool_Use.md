# AutoMat：赋能显微镜晶体结构的智能自动重建

发布时间：2025年05月18日

`LLM应用` `材料科学`

> AutoMat: Enabling Automated Crystal Structure Reconstruction from Microscopy via Agentic Tool Use

# 摘要

> 基于机器学习的原子间势和力场对精确的原子结构有着关键依赖，但实验解析晶体的稀缺性导致这类数据极为匮乏。虽然原子分辨率电子显微镜提供了一种获取结构数据的可能，但将这些图像转换为可用于模拟的数据格式仍然耗时且容易出错，成为模型训练和验证的瓶颈。我们推出了AutoMat，一个端到端、智能体辅助的流水线，能够自动将扫描透射电子显微镜（STEM）图像转换为原子晶体结构，并预测其物理性质。AutoMat集成了自适应去噪、物理引导模板检索、对称性感知原子重构、快速松弛以及通过MatterSim进行的性质预测，并实现了各阶段的协调编排。我们提出了首个专注于此任务的STEM2Mat-Bench基准测试，并通过晶格RMSD、形成能MAE和结构匹配成功率来评估性能。通过协调外部工具调用，AutoMat使纯文本LLM在该领域超越了视觉-语言模型，实现了整个流水线的闭环推理。在涵盖450个结构样本的大规模实验中，AutoMat显著优于现有的多模态大语言模型和工具。这些结果不仅验证了AutoMat和STEM2Mat-Bench的有效性，也标志着在材料科学中连接显微镜与原子级模拟的关键进展。代码和数据集可在https://github.com/yyt-2378/AutoMat和https://huggingface.co/datasets/yaotianvector/STEM2Mat公开获取。

> Machine learning-based interatomic potentials and force fields depend critically on accurate atomic structures, yet such data are scarce due to the limited availability of experimentally resolved crystals. Although atomic-resolution electron microscopy offers a potential source of structural data, converting these images into simulation-ready formats remains labor-intensive and error-prone, creating a bottleneck for model training and validation. We introduce AutoMat, an end-to-end, agent-assisted pipeline that automatically transforms scanning transmission electron microscopy (STEM) images into atomic crystal structures and predicts their physical properties. AutoMat combines pattern-adaptive denoising, physics-guided template retrieval, symmetry-aware atomic reconstruction, fast relaxation and property prediction via MatterSim, and coordinated orchestration across all stages. We propose the first dedicated STEM2Mat-Bench for this task and evaluate performance using lattice RMSD, formation energy MAE, and structure-matching success rate. By orchestrating external tool calls, AutoMat enables a text-only LLM to outperform vision-language models in this domain, achieving closed-loop reasoning throughout the pipeline. In large-scale experiments over 450 structure samples, AutoMat substantially outperforms existing multimodal large language models and tools. These results validate both AutoMat and STEM2Mat-Bench, marking a key step toward bridging microscopy and atomistic simulation in materials science.The code and dataset are publicly available at https://github.com/yyt-2378/AutoMat and https://huggingface.co/datasets/yaotianvector/STEM2Mat.

[Arxiv](https://arxiv.org/abs/2505.12650)