# ProRefine: 基于文本反馈的推理阶段提示优化

发布时间：2025年06月05日

`LLM应用` `AI协作` `智能体优化`

> ProRefine: Inference-time Prompt Refinement with Textual Feedback

# 摘要

> 智能体协作完成复杂任务的现象日益普遍，但提示设计不当导致的错误传播和性能问题亟待解决。我们推出创新方法ProRefine，通过LLMs反馈优化提示，显著提升推理任务表现。实验证明，ProRefine不仅提升准确率，还让小模型媲美大模型，助力高效AI部署与普及。

> Agentic workflows, where multiple AI agents collaborate to accomplish complex tasks like reasoning or planning, are becoming increasingly prevalent. However, these workflows often suffer from error propagation and sub-optimal performance, largely due to poorly designed prompts that fail to effectively guide individual agents. This is a critical problem because it limits the reliability and scalability of these powerful systems. We introduce ProRefine, an innovative inference-time prompt optimization method that leverages textual feedback from large language models (LLMs) to address this challenge. ProRefine dynamically refines prompts for multi-step reasoning tasks without additional training or ground truth labels. Evaluated on five benchmark mathematical reasoning datasets, ProRefine significantly surpasses zero-shot Chain-of-Thought baselines by 3 to 37 percentage points. This approach not only boosts accuracy but also allows smaller models to match the performance of larger ones, highlighting its potential for efficient and scalable AI deployment, and democratizing access to high-performing AI.

[Arxiv](https://arxiv.org/abs/2506.05305)