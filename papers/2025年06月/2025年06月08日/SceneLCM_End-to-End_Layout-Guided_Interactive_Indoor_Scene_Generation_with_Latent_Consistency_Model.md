# SceneLCM: 端到端布局引导交互式室内场景生成，基于潜在一致性模型

发布时间：2025年06月08日

`LLM应用` `室内设计` `计算机图形学`

> SceneLCM: End-to-End Layout-Guided Interactive Indoor Scene Generation with Latent Consistency Model

# 摘要

> # 项目概述  
我们的项目页面：https://scutyklin.github.io/SceneLCM/  
针对用户提示自动生成复杂且交互式的室内场景仍然是一项巨大挑战。现有方法虽然能实现室内场景的合成，但面临着编辑约束 rigid、物理不一致、人工投入过大、仅限单室以及材质质量不佳等多重挑战。  
为了解决这些问题，我们提出了SceneLCM，一个结合大型语言模型（LLM）进行布局设计和潜在一致性模型（LCM）进行场景优化的端到端框架。我们的方法将场景生成分解为四个模块化流程：  
1. **布局生成**：我们采用LLM引导的3D空间推理，将文本描述转化为参数化蓝图（3D布局）。通过LLM介导的对话循环，迭代验证机制逐步优化布局参数；  
2. **家具生成**：SceneLCM采用一致性轨迹采样（CTS），这是一种由LCM引导的一致性蒸馏采样损失，能够快速生成语义丰富且高质量的表示。我们还提供了两个理论依据，证明我们的CTS损失等价于一致性损失，且其蒸馏误差由欧拉求解器的截断误差所限制；  
3. **环境优化**：我们利用多分辨率纹理场对场景外观进行编码，并通过CTS损失进行优化。为保持跨几何纹理的一致性，我们引入了基于法线的交叉注意力解码器，通过跨注意机制预测RGB，关注几何异质实例中的锚点位置；  
4. **物理编辑**：SceneLCM通过集成物理模拟实现了物理编辑，从而保持了持续的物理真实性。  
通过大量实验，我们验证了SceneLCM相较于现有技术的优越性，展示了其在多样应用场景中的广泛潜力。

> Our project page: https://scutyklin.github.io/SceneLCM/. Automated generation of complex, interactive indoor scenes tailored to user prompt remains a formidable challenge. While existing methods achieve indoor scene synthesis, they struggle with rigid editing constraints, physical incoherence, excessive human effort, single-room limitations, and suboptimal material quality. To address these limitations, we propose SceneLCM, an end-to-end framework that synergizes Large Language Model (LLM) for layout design with Latent Consistency Model(LCM) for scene optimization. Our approach decomposes scene generation into four modular pipelines: (1) Layout Generation. We employ LLM-guided 3D spatial reasoning to convert textual descriptions into parametric blueprints(3D layout). And an iterative programmatic validation mechanism iteratively refines layout parameters through LLM-mediated dialogue loops; (2) Furniture Generation. SceneLCM employs Consistency Trajectory Sampling(CTS), a consistency distillation sampling loss guided by LCM, to form fast, semantically rich, and high-quality representations. We also offer two theoretical justification to demonstrate that our CTS loss is equivalent to consistency loss and its distillation error is bounded by the truncation error of the Euler solver; (3) Environment Optimization. We use a multiresolution texture field to encode the appearance of the scene, and optimize via CTS loss. To maintain cross-geometric texture coherence, we introduce a normal-aware cross-attention decoder to predict RGB by cross-attending to the anchors locations in geometrically heterogeneous instance. (4)Physically Editing. SceneLCM supports physically editing by integrating physical simulation, achieved persistent physical realism. Extensive experiments validate SceneLCM's superiority over state-of-the-art techniques, showing its wide-ranging potential for diverse applications.

[Arxiv](https://arxiv.org/abs/2506.07091)