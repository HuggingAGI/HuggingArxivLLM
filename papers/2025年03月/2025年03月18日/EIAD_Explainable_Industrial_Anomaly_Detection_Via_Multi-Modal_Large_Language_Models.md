# EIAD：基于多模态大型语言模型的可解释工业异常检测

发布时间：2025年03月18日

`LLM应用` `工业制造` `多模态模型`

> EIAD: Explainable Industrial Anomaly Detection Via Multi-Modal Large Language Models

# 摘要

> 工业异常检测（IAD）是保障制造产品质量的关键技术。现有的零样本缺陷分割和检测方法虽有效，但难以提供缺陷的详细描述。目前，大型多模态模型在工业异常检测中的应用尚处于初期阶段，面临问答（QA）性能与基于掩码的定位能力之间平衡的挑战，这通常源于微调过程中的过拟合问题。为解决这些挑战，我们提出了一种创新方法，通过引入专用的多模态缺陷定位模块，将对话功能与核心特征提取功能解耦。这种解耦通过独立的优化目标和定制化的学习策略实现。此外，我们构建了首个多模态工业异常检测训练数据集——缺陷检测问答（DDQA），涵盖多种缺陷类型和工业场景。与依赖GPT生成数据的传统数据集不同，DDQA确保了数据的真实性和可靠性，为模型训练提供了坚实基础。实验结果表明，我们提出的可解释工业异常检测助手（EIAD）在缺陷检测和定位任务中表现优异，不仅显著提高了准确性，还增强了可解释性。这些进展凸显了EIAD在工业实际应用中的潜力。

> Industrial Anomaly Detection (IAD) is critical to ensure product quality during manufacturing. Although existing zero-shot defect segmentation and detection methods have shown effectiveness, they cannot provide detailed descriptions of the defects. Furthermore, the application of large multi-modal models in IAD remains in its infancy, facing challenges in balancing question-answering (QA) performance and mask-based grounding capabilities, often owing to overfitting during the fine-tuning process. To address these challenges, we propose a novel approach that introduces a dedicated multi-modal defect localization module to decouple the dialog functionality from the core feature extraction. This decoupling is achieved through independent optimization objectives and tailored learning strategies. Additionally, we contribute to the first multi-modal industrial anomaly detection training dataset, named Defect Detection Question Answering (DDQA), encompassing a wide range of defect types and industrial scenarios. Unlike conventional datasets that rely on GPT-generated data, DDQA ensures authenticity and reliability and offers a robust foundation for model training. Experimental results demonstrate that our proposed method, Explainable Industrial Anomaly Detection Assistant (EIAD), achieves outstanding performance in defect detection and localization tasks. It not only significantly enhances accuracy but also improves interpretability. These advancements highlight the potential of EIAD for practical applications in industrial settings.

[Arxiv](https://arxiv.org/abs/2503.14162)