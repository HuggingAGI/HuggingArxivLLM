# # 图像修复的混合智能体方案

发布时间：2025年03月13日

`Agent` `图像处理` `计算机视觉`

> Hybrid Agents for Image Restoration

# 摘要

> 现有图像修复 (IR) 研究通常分别专注于特定任务或通用模式，依赖用户的模式选择，缺乏多种特定任务/通用修复模式之间的协作。这导致了对非专业用户的交互不足，限制了他们在复杂现实应用中的修复能力。在本研究中，我们提出了HybridAgent，旨在将多种修复模式整合到一个统一的图像修复模型中，并通过我们的混合智能体实现智能高效的用户交互。具体来说，我们提出了快速、慢速和反馈修复智能体的混合规则。其中，慢速修复智能体通过我们的指令微调数据集优化了强大的多模态大型语言模型 (MLLM)，以识别具有模糊用户提示的图像中的退化，并相应地调用合适的修复工具。快速修复智能体基于轻量级大型语言模型 (LLM) 通过上下文学习设计，能够理解具有简单清晰要求的用户提示，从而避免了MLLM不必要的时间和资源消耗。此外，我们为HybridAgents引入了混合失真去除模式，这是之前基于智能体的工作中未关注但至关重要的内容。它可以有效防止分步图像修复中的错误传播，并大幅提高智能体系统的效率。我们通过合成和真实世界的图像修复任务验证了HybridAgent的有效性。

> Existing Image Restoration (IR) studies typically focus on task-specific or universal modes individually, relying on the mode selection of users and lacking the cooperation between multiple task-specific/universal restoration modes. This leads to insufficient interaction for unprofessional users and limits their restoration capability for complicated real-world applications. In this work, we present HybridAgent, intending to incorporate multiple restoration modes into a unified image restoration model and achieve intelligent and efficient user interaction through our proposed hybrid agents. Concretely, we propose the hybrid rule of fast, slow, and feedback restoration agents. Here, the slow restoration agent optimizes the powerful multimodal large language model (MLLM) with our proposed instruction-tuning dataset to identify degradations within images with ambiguous user prompts and invokes proper restoration tools accordingly. The fast restoration agent is designed based on a lightweight large language model (LLM) via in-context learning to understand the user prompts with simple and clear requirements, which can obviate the unnecessary time/resource costs of MLLM. Moreover, we introduce the mixed distortion removal mode for our HybridAgents, which is crucial but not concerned in previous agent-based works. It can effectively prevent the error propagation of step-by-step image restoration and largely improve the efficiency of the agent system. We validate the effectiveness of HybridAgent with both synthetic and real-world IR tasks.

[Arxiv](https://arxiv.org/abs/2503.10120)