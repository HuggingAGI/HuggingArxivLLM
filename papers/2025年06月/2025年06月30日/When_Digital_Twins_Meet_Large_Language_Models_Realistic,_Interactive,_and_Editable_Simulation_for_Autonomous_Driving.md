# 数字孪生与大型语言模型的相遇：真实、互动且可编辑的自动驾驶模拟环境

发布时间：2025年06月30日

`LLM应用

摘要中提到的论文主要讨论了在自动驾驶仿真框架中使用大型语言模型（LLM）接口，以支持通过自然语言提示在线编辑驾驶场景。虽然主要焦点是自动驾驶仿真框架，但LLM的应用是一个关键组成部分，因此归类为LLM应用。` `自动驾驶` `数字孪生`

> When Digital Twins Meet Large Language Models: Realistic, Interactive, and Editable Simulation for Autonomous Driving

# 摘要

> 仿真框架一直是自动驾驶系统开发与验证的关键推动者。然而，现有方法难以全面满足以自主性为导向的四项核心要求：(i) 动力学保真度，(ii) 照片级渲染，(iii) 场景相关的环境编排，以及(iv) 实时性能。为了解决这些局限性，我们提出了一种统一框架，用于创建和管理高保真数字孪生体，从而加速自动驾驶研究的进步。我们的框架结合了基于物理的方法和数据驱动的技术，用于开发和模拟自动驾驶车辆及其运行环境的数字孪生。它能够以几何和照片级的精度重建现实世界中的场景和资产（即现实到仿真），并赋予它们各种物理特性，从而实现后续驾驶场景的实时动力学仿真。此外，该框架还集成了一个大型语言模型（LLM）接口，支持通过自然语言提示在线灵活编辑驾驶场景。我们从保真度、性能和服务性三个方面对所提出的框架进行了分析。结果表明，我们的框架能够以高达97%的结构相似度重建3D场景和资产，同时保持每秒60帧以上的帧率。我们还展示了它能够处理自然语言提示，生成具有高达95%可重复性和85%泛化性的多样化驾驶场景。

> Simulation frameworks have been key enablers for the development and validation of autonomous driving systems. However, existing methods struggle to comprehensively address the autonomy-oriented requirements of balancing: (i) dynamical fidelity, (ii) photorealistic rendering, (iii) context-relevant scenario orchestration, and (iv) real-time performance. To address these limitations, we present a unified framework for creating and curating high-fidelity digital twins to accelerate advancements in autonomous driving research. Our framework leverages a mix of physics-based and data-driven techniques for developing and simulating digital twins of autonomous vehicles and their operating environments. It is capable of reconstructing real-world scenes and assets (real2sim) with geometric and photorealistic accuracy and infusing them with various physical properties to enable real-time dynamical simulation of the ensuing driving scenarios. Additionally, it also incorporates a large language model (LLM) interface to flexibly edit the driving scenarios online via natural language prompts. We analyze the presented framework in terms of its fidelity, performance, and serviceability. Results indicate that our framework can reconstruct 3D scenes and assets with up to 97% structural similarity, while maintaining frame rates above 60 Hz. We also demonstrate that it can handle natural language prompts to generate diverse driving scenarios with up to 95% repeatability and 85% generalizability.

[Arxiv](https://arxiv.org/abs/2507.00319)