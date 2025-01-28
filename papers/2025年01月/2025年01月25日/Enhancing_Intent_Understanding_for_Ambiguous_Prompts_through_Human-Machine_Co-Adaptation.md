# 通过人机协同适应提升模糊提示的意图理解

发布时间：2025年01月25日

`LLM应用

**理由**：该论文提出了一种通过迭代优化提示来生成更贴合用户偏好的图像的框架（VCA），结合了微调语言模型、强化学习和多轮对话等技术。虽然涉及了RAG（Retrieval-Augmented Generation）和强化学习等技术，但其核心目标是优化图像生成过程，属于LLM在实际应用中的创新使用，因此归类为LLM应用。` `图像生成` `人机交互`

> Enhancing Intent Understanding for Ambiguous Prompts through Human-Machine Co-Adaptation

# 摘要

> 现代图像生成系统虽能产出高质量图像，但用户提示常含模糊性，需多次调整。现有方法难以满足非专业用户的细致需求。为此，我们提出视觉协同适应（VCA），一个通过迭代优化提示并让生成图像更贴合用户偏好的创新框架。VCA结合了微调语言模型、强化学习和多轮对话，有效解决提示模糊问题。其核心包括：增量上下文增强对话块用于交互澄清，语义探索与消歧模块（SESD）利用RAG和CLIP评分，以及像素精度和一致性优化模块（PPCO）通过PPO优化图像细节。人类反馈机制进一步提升了性能。实验显示，VCA在对话轮次（4.3）、CLIP评分（0.92）和用户满意度（4.73/5）上均优于DALL-E 3和Stable Diffusion。我们还推出了一个包含提示-图像对和用户意图注释的多轮对话数据集。

> Modern image generation systems can produce high-quality visuals, yet user prompts often contain ambiguities, requiring multiple revisions. Existing methods struggle to address the nuanced needs of non-expert users. We propose Visual Co-Adaptation (VCA), a novel framework that iteratively refines prompts and aligns generated images with user preferences. VCA employs a fine-tuned language model with reinforcement learning and multi-turn dialogues for prompt disambiguation. Key components include the Incremental Context-Enhanced Dialogue Block for interactive clarification, the Semantic Exploration and Disambiguation Module (SESD) leveraging Retrieval-Augmented Generation (RAG) and CLIP scoring, and the Pixel Precision and Consistency Optimization Module (PPCO) for refining image details using Proximal Policy Optimization (PPO). A human-in-the-loop feedback mechanism further improves performance. Experiments show that VCA surpasses models like DALL-E 3 and Stable Diffusion, reducing dialogue rounds to 4.3, achieving a CLIP score of 0.92, and enhancing user satisfaction to 4.73/5. Additionally, we introduce a novel multi-round dialogue dataset with prompt-image pairs and user intent annotations.

[Arxiv](https://arxiv.org/abs/2501.15167)