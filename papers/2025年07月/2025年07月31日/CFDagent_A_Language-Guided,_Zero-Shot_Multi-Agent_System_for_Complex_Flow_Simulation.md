# CFDagent：语言引导的零样本多智能体系统，专为复杂流动模拟设计

发布时间：2025年07月31日

`Agent` `计算流体动力学` `工程应用`

> CFDagent: A Language-Guided, Zero-Shot Multi-Agent System for Complex Flow Simulation

# 摘要

> 我们推出 CFDagent，一个零样本、多智能体系统，它能够从自然语言提示中实现完全自主的计算流体动力学 (CFD) 模拟。该系统集成了三个由 LLM 驱动的专用智能体：(i) 预处理智能体，它通过混合文本到 3D 扩散模型（Point-E）从文本或视觉输入生成 3D 几何并自动进行网格划分；(ii) 求解器智能体，它负责配置和执行嵌入边界流求解器；(iii) 后处理智能体，它能够分析和可视化结果，包括多模态渲染。这些智能体由 GPT-4o 通过对话提示进行交互式引导，从而实现直观且用户友好的操作。我们通过三种不同的输入验证了 CFDagent 的性能：一个简单的文本提示（即“球体”）、一个基于图像的输入，以及一个标准球体模型，在雷诺数为 100 和 300 时成功重现了经典的球体流动。来自每个输入生成的网格的计算阻力和升力系数与现有数据非常接近。该系统能够为复杂几何体生成流模拟和 photorealistic 可视化。通过在经典和现实场景上的广泛测试，我们展示了 CFDagent 的鲁棒性、多样性和实际应用价值。通过将生成式 AI 与高保真模拟相结合，CFDagent 显著降低了达到专家级 CFD 的门槛，为教育、科学研究和实际工程应用开辟了广泛的机会。

> We introduce CFDagent, a zero-shot, multi-agent system that enables fully autonomous computational fluid dynamics (CFD) simulations from natural language prompts. CFDagent integrates three specialized LLM-driven agents: (i) the Preprocessing Agent that generates 3D geometries from textual or visual inputs using a hybrid text-to-3D diffusion model (Point-E) and automatically meshes the geometries; (ii) the Solver Agent that configures and executes an immersed boundary flow solver; and (iii) the Postprocessing Agent that analyzes and visualizes the results, including multimodal renderings. These agents are interactively guided by GPT-4o via conversational prompts, enabling intuitive and user-friendly interaction. We validate CFDagent by reproducing canonical sphere flows at Reynolds numbers of 100 and 300 using three distinct inputs: a simple text prompt (i.e., "sphere"), an image-based input, and a standard sphere model. The computed drag and lift coefficients from meshes produced by each input approach closely match available data. The proposed system enables synthesization of flow simulations and photorealistic visualizations for complex geometries. Through extensive tests on canonical and realistic scenarios, we demonstrate the robustness, versatility, and practical applicability of CFDagent. By bridging generative AI with high-fidelity simulations, CFDagent significantly lowers barriers to expert-level CFD, unlocking broad opportunities in education, scientific research, and practical engineering applications.

[Arxiv](https://arxiv.org/abs/2507.23693)