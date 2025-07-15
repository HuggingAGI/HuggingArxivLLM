# # 摘要  
MIRIX: 面向LLM智能体的多智能体内存系统

发布时间：2025年07月10日

`Agent` `人工智能` `计算机视觉`

> MIRIX: Multi-Agent Memory System for LLM-Based Agents

# 摘要

> 尽管 AI 代理的记忆能力日益受到关注，现有解决方案仍然存在根本性限制。大多数系统依赖于平面化、范围狭窄的记忆组件，这限制了它们在时间推移中个性化、抽象和可靠地回忆用户特定信息的能力。为此，我们引入了 MIRIX，这是一个模块化、多智能体记忆系统，通过解决该领域最关键挑战——让语言模型真正记住信息——重新定义了 AI 记忆的未来。

与之前的方法不同，MIRIX 超越了文本，拥抱丰富的视觉和多模态体验，使记忆在现实场景中真正有用。MIRIX 由六种独特且精心设计的记忆类型组成：核心记忆、情景记忆、语义记忆、程序记忆、资源记忆和知识库，配合一个多智能体框架，动态控制和协调更新与检索。这种设计使智能体能够持久保存、推理和大规模准确检索多样化的长期用户数据。

我们在两个具有挑战性的场景中验证了 MIRIX。首先，在包含近 20,000 高分辨率计算机截图的多模态基准测试 ScreenshotVQA 上，该任务需要深度上下文理解且现有记忆系统无法应用，MIRIX 达到了比 RAG 基线高出 35% 的准确率，同时将存储需求降低了 99.9%。其次，在单模态文本输入的长对话基准测试 LOCOMO 上，MIRIX 达到了 85.4% 的最佳性能，远超现有基线。

这些结果表明，MIRIX 为增强记忆的 LLM 智能体设定了新的性能标准。为了让用户亲身体验我们的记忆系统，我们提供了一个由 MIRIX 驱动的打包应用程序。它实时监控屏幕，构建个性化的记忆库，并提供直观的可视化和安全的本地存储，以确保隐私。

> Although memory capabilities of AI agents are gaining increasing attention, existing solutions remain fundamentally limited. Most rely on flat, narrowly scoped memory components, constraining their ability to personalize, abstract, and reliably recall user-specific information over time. To this end, we introduce MIRIX, a modular, multi-agent memory system that redefines the future of AI memory by solving the field's most critical challenge: enabling language models to truly remember. Unlike prior approaches, MIRIX transcends text to embrace rich visual and multimodal experiences, making memory genuinely useful in real-world scenarios. MIRIX consists of six distinct, carefully structured memory types: Core, Episodic, Semantic, Procedural, Resource Memory, and Knowledge Vault, coupled with a multi-agent framework that dynamically controls and coordinates updates and retrieval. This design enables agents to persist, reason over, and accurately retrieve diverse, long-term user data at scale. We validate MIRIX in two demanding settings. First, on ScreenshotVQA, a challenging multimodal benchmark comprising nearly 20,000 high-resolution computer screenshots per sequence, requiring deep contextual understanding and where no existing memory systems can be applied, MIRIX achieves 35% higher accuracy than the RAG baseline while reducing storage requirements by 99.9%. Second, on LOCOMO, a long-form conversation benchmark with single-modal textual input, MIRIX attains state-of-the-art performance of 85.4%, far surpassing existing baselines. These results show that MIRIX sets a new performance standard for memory-augmented LLM agents. To allow users to experience our memory system, we provide a packaged application powered by MIRIX. It monitors the screen in real time, builds a personalized memory base, and offers intuitive visualization and secure local storage to ensure privacy.

[Arxiv](https://arxiv.org/abs/2507.07957)