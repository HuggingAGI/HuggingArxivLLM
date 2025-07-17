# 编排器与代理的信任：一个结合信任感知编排与基于RAG推理的模块化智能体AI视觉分类系统

发布时间：2025年07月09日

`Agent`

> Orchestrator-Agent Trust: A Modular Agentic AI Visual Classification System with Trust-Aware Orchestration and RAG-Based Reasoning

# 摘要

> 现代人工智能（AI）正日益倚赖融合视觉与语言理解的多智能体架构。然而，一个亟待解决的挑战是：如何在无需微调的零样本设置中信任这些智能体？我们提出了一种创新的模块化智能体AI视觉分类框架，整合了通用多模态智能体、非视觉推理编排器以及增强生成（RAG）模块。应用于苹果叶片疾病诊断，我们评估了三种配置：（I）基于置信度的编排零样本设置，（II）性能优化的微调智能体，（III）通过CLIP基图像检索与迭代重评估增强的可信度校准编排。通过置信度校准指标（ECE、OCR、CCC），编排器调节各智能体的可信度。我们的结果表明，在零样本设置中，采用信任感知编排与RAG可实现77.94%的准确率提升，整体准确率达到85.63%。GPT-4o展现了更好的校准效果，而Qwen-2.5-VL则显得过于自信。此外，图像-RAG通过视觉相似案例为预测提供依据，通过迭代重评估纠正了智能体的过度自信。本系统将感知（视觉智能体）与元推理（编排器）分离，实现了可扩展且可解释的多智能体AI。此蓝图可扩展至诊断、生物学及其他关键信任领域。所有模型、提示、结果及系统组件，包括完整的软件源代码，均在GitHub上公开发布，以支持可重复性、透明度及社区基准测试：https://github.com/Applied-AI-Research-Lab/Orchestrator-Agent-Trust

> Modern Artificial Intelligence (AI) increasingly relies on multi-agent architectures that blend visual and language understanding. Yet, a pressing challenge remains: How can we trust these agents especially in zero-shot settings with no fine-tuning? We introduce a novel modular Agentic AI visual classification framework that integrates generalist multimodal agents with a non-visual reasoning orchestrator and a Retrieval-Augmented Generation (RAG) module. Applied to apple leaf disease diagnosis, we benchmark three configurations: (I) zero-shot with confidence-based orchestration, (II) fine-tuned agents with improved performance, and (III) trust-calibrated orchestration enhanced by CLIP-based image retrieval and re-evaluation loops. Using confidence calibration metrics (ECE, OCR, CCC), the orchestrator modulates trust across agents. Our results demonstrate a 77.94\% accuracy improvement in the zero-shot setting using trust-aware orchestration and RAG, achieving 85.63\% overall. GPT-4o showed better calibration, while Qwen-2.5-VL displayed overconfidence. Furthermore, image-RAG grounded predictions with visually similar cases, enabling correction of agent overconfidence via iterative re-evaluation. The proposed system separates perception (vision agents) from meta-reasoning (orchestrator), enabling scalable and interpretable multi-agent AI. This blueprint is extensible to diagnostics, biology, and other trust-critical domains. All models, prompts, results, and system components including the complete software source code are openly released to support reproducibility, transparency, and community benchmarking at Github: https://github.com/Applied-AI-Research-Lab/Orchestrator-Agent-Trust

[Arxiv](https://arxiv.org/abs/2507.10571)