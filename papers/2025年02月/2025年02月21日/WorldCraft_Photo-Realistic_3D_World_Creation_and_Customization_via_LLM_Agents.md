# # WorldCraft：通过LLM智能体打造照片级真实感的3D世界创建与定制

发布时间：2025年02月21日

`LLM应用` `虚拟现实` `3D建模`

> WorldCraft: Photo-Realistic 3D World Creation and Customization via LLM Agents

# 摘要

> 构建照片级真实的虚拟世界在多个领域都有广泛应用，但传统上需要经过专业训练的人员投入大量脑力劳动来操作3D建模软件。为了让虚拟世界构建变得民主化，我们推出了WorldCraft系统。该系统利用大型语言模型（LLM）代理通过程序化生成技术创建室内和室外场景，并允许用户通过直观的自然语言命令控制物体属性和场景布局。在我们的框架中，一个协调器代理负责整体流程，并与两个专门的LLM代理协同工作：ForgeIt通过不断整合并自动验证日益丰富的手册，实现对单个物体的精确定制；ArrangeIt则通过构建分层优化问题，实现符合人体工学和美学考量的场景布局。此外，我们的系统还集成了一个轨迹控制代理，让用户能够通过自然语言交互对场景进行动画处理和操作摄像头。WorldCraft兼容现成的深度3D生成器，能够丰富场景资源。通过评估和与现有最佳方法的比较，我们展示了WorldCraft的多功能性，从单个物体的定制到复杂的大规模室内和室外场景设计。这一系统让非专业人士也能轻松将创意构想变为现实。

> Constructing photorealistic virtual worlds has applications across various fields, but it often requires the extensive labor of highly trained professionals to operate conventional 3D modeling software. To democratize this process, we introduce WorldCraft, a system where large language model (LLM) agents leverage procedural generation to create indoor and outdoor scenes populated with objects, allowing users to control individual object attributes and the scene layout using intuitive natural language commands. In our framework, a coordinator agent manages the overall process and works with two specialized LLM agents to complete the scene creation: ForgeIt, which integrates an ever-growing manual through auto-verification to enable precise customization of individual objects, and ArrangeIt, which formulates hierarchical optimization problems to achieve a layout that balances ergonomic and aesthetic considerations. Additionally, our pipeline incorporates a trajectory control agent, allowing users to animate the scene and operate the camera through natural language interactions. Our system is also compatible with off-the-shelf deep 3D generators to enrich scene assets. Through evaluations and comparisons with state-of-the-art methods, we demonstrate the versatility of WorldCraft, ranging from single-object customization to intricate, large-scale interior and exterior scene designs. This system empowers non-professionals to bring their creative visions to life.

[Arxiv](https://arxiv.org/abs/2502.15601)