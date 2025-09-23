# AgriDoctor：面向农业的多模态智能助手

发布时间：2025年09月21日

`Agent` `农业科技`

> AgriDoctor: A Multimodal Intelligent Assistant for Agriculture

# 摘要

> 作物病害的精准诊断对可持续农业发展和全球粮食安全而言至关重要。现有方法多依赖图像分类器、目标检测器等单模态模型，不仅难以整合特定领域的农业知识，也无法支持交互式的语言理解。近年来，大型语言模型（LLMs）与大型视觉-语言模型（LVLMs）的突破为多模态推理带来了新可能，但受限于农业领域专用数据集的缺失和领域适配的不足，这些模型在农业场景中的表现仍不尽如人意。为此，我们提出了AgriDoctor——一个模块化、可扩展的多模态框架，专门用于智能作物病害诊断与农业知识交互。作为首次将智能体多模态推理引入农业领域的尝试，AgriDoctor为打造交互式、领域自适应的作物健康解决方案提供了全新范式。该框架集成五大核心组件：路由模块、分类器、检测器、知识检索器及LLMs。为支持高效训练与评估，我们构建了综合基准数据集AgriMM，涵盖40万张标注病害图像、831条专家精选知识条目，以及30万条用于意图驱动工具选择的双语提示。大量实验证实，基于AgriMM训练的AgriDoctor在细粒度农业任务上性能远超当前最先进的LVLMs，为智能、可持续农业应用树立了新标杆。

> Accurate crop disease diagnosis is essential for sustainable agriculture and global food security. Existing methods, which primarily rely on unimodal models such as image-based classifiers and object detectors, are limited in their ability to incorporate domain-specific agricultural knowledge and lack support for interactive, language-based understanding. Recent advances in large language models (LLMs) and large vision-language models (LVLMs) have opened new avenues for multimodal reasoning. However, their performance in agricultural contexts remains limited due to the absence of specialized datasets and insufficient domain adaptation. In this work, we propose AgriDoctor, a modular and extensible multimodal framework designed for intelligent crop disease diagnosis and agricultural knowledge interaction. As a pioneering effort to introduce agent-based multimodal reasoning into the agricultural domain, AgriDoctor offers a novel paradigm for building interactive and domain-adaptive crop health solutions. It integrates five core components: a router, classifier, detector, knowledge retriever and LLMs. To facilitate effective training and evaluation, we construct AgriMM, a comprehensive benchmark comprising 400000 annotated disease images, 831 expert-curated knowledge entries, and 300000 bilingual prompts for intent-driven tool selection. Extensive experiments demonstrate that AgriDoctor, trained on AgriMM, significantly outperforms state-of-the-art LVLMs on fine-grained agricultural tasks, establishing a new paradigm for intelligent and sustainable farming applications.

[Arxiv](https://arxiv.org/abs/2509.17044)