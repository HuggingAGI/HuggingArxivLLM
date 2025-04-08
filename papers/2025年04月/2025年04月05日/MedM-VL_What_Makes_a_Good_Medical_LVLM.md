# MedM-VL：什么成就优秀的医疗大规模视觉-语言模型？

发布时间：2025年04月05日

`LLM应用` `医学图像分析`

> MedM-VL: What Makes a Good Medical LVLM?

# 摘要

> 医学图像分析是医疗领域的重要环节。随着深度学习技术的进步，研究焦点已从单一任务（如分类和分割）转向更复杂的多模态任务，例如医学视觉问答和报告生成。传统的浅层和特定任务模型在应对临床实践中的复杂性和扩展性需求时显得力不从心。大型语言模型（LLMs）的兴起推动了医学大型视觉-语言模型（LVLMs）的发展，为多样化的视觉-语言任务提供了一个统一的解决方案。本研究基于广受欢迎的 LLaVA 框架，该框架采用编码器-连接器-LLM 的架构，深入探索了医学 LVLM 的多种设计。我们开发了两个分别针对 2D 和 3D 图像的独立模型，旨在支持通用医疗任务的同时，也能进行特定领域的微调，从而作为有效的基础模型。为了促进研究的可重复性和进一步发展，我们开发了一个模块化且可扩展的代码库 MedM-VL，并发布了两个 LVLM 变体：MedM-VL-2D 专注于 2D 医学图像分析，MedM-VL-CT-Chest 则针对基于 3D CT 的应用。代码和模型可在以下链接获取：https://github.com/MSIIP/MedM-VL

> Medical image analysis is a fundamental component. As deep learning progresses, the focus has shifted from single-task applications, such as classification and segmentation, to more complex multimodal tasks, including medical visual question answering and report generation. Traditional shallow and task-specific models are increasingly limited in addressing the complexity and scalability required in clinical practice. The emergence of large language models (LLMs) has driven the development of medical Large Vision-Language Models (LVLMs), offering a unified solution for diverse vision-language tasks. In this study, we investigate various architectural designs for medical LVLMs based on the widely adopted LLaVA framework, which follows an encoder-connector-LLM paradigm. We construct two distinct models targeting 2D and 3D modalities, respectively. These models are designed to support both general-purpose medical tasks and domain-specific fine-tuning, thereby serving as effective foundation models. To facilitate reproducibility and further research, we develop a modular and extensible codebase, MedM-VL, and release two LVLM variants: MedM-VL-2D for 2D medical image analysis and MedM-VL-CT-Chest for 3D CT-based applications. The code and models are available at: https://github.com/MSIIP/MedM-VL

[Arxiv](https://arxiv.org/abs/2504.04323)