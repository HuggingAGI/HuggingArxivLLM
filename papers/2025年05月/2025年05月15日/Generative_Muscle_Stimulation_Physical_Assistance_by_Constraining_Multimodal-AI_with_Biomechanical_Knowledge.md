# 生成式肌肉刺激：用生物力学知识约束多模态AI，实现物理辅助

发布时间：2025年05月15日

`LLM应用` `可穿戴技术`

> Generative Muscle Stimulation: Physical Assistance by Constraining Multimodal-AI with Biomechanical Knowledge

# 摘要

> 数十年的交互式电肌肉刺激（EMS）研究表明，它有望成为一种物理辅助的可穿戴界面——通过用户自身身体直接演示动作（例如，在喷漆前摇晃喷漆罐）。然而，交互式EMS系统存在两大局限：反馈固定且缺乏情境感知。为突破这些限制，我们开发了一款更灵活的系统，可根据用户场景生成肌肉刺激指令。通过实例演示，该系统不仅能实现前所未有的EMS交互（例如，打开儿童安全药瓶盖），还能完美复现现有功能（例如，摇晃喷漆罐），这一切均无需特定编程。系统通过语音请求和用户视角图像输入，结合计算机视觉（如物体/手部检测）和大型语言模型（如情境推理），生成文本指令。最终，借助 biomechanical 知识（如关节限制、运动链等）对指令进行约束，生成合适的手势刺激。我们相信，这一创新标志着EMS界面向更通用、更智能的方向迈进，将带来更灵活、更具情境感知的辅助体验。

> Decades of interactive electrical-muscle-stimulation (EMS) revealed its promise as a wearable interface for physical assistance-EMS directly demonstrates movements through the users' body (e.g., shaking a spray-can before painting). However, interactive EMS-systems are highly-specialized because their feedback is (1) fixed (e.g., one program executes spray-can instructions, another executes piano instructions) and (2) non-contextual (e.g., using a spray-can while cooking likely involves cooking oil, not paint, and thus shaking is unnecessary). To address this, we explored a more flexible approach and engineered a system that generates muscle-stimulation-instructions given the user's context. Through our examples, we show that such a system is flexible: it enables unprecedented EMS-interactions (e.g., opening a child-proof pill bottle cap) but also replicates existing systems (e.g., shake a spray can)-all without requiring task-specific programming. To achieve this, our system takes in user's spoken-requests and images from their point of view. It uses computer vision (e.g., detect objects/handedness) and large-language-models (e.g., reason about objects/situations) to generate textual-instructions. Finally, these instructions are then constrained by biomechanical-knowledge (e.g., joint limits, kinematic-chain, EMS capabilities) to produce suitable muscle-stimulation gestures. We believe our concept marks a shift toward more general-purpose EMS-interfaces, enabling more flexible and context-aware assistance.

[Arxiv](https://arxiv.org/abs/2505.10648)