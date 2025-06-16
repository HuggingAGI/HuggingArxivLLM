# LoRA-Gen：在线生成LoRA实现大型语言模型专业化

发布时间：2025年06月13日

`LLM应用` `模型生成` `边缘计算`

> LoRA-Gen: Specializing Large Language Model via Online LoRA Generation

# 摘要

> 近期研究凸显了扩大语言模型规模以提升各类NLP任务表现的优势。然而，这些方法在特定领域任务，尤其是小型边缘端模型应用中仍存在局限。我们提出LoRA-Gen框架，利用大型云端模型根据任务描述生成边缘端模型的LoRA参数。通过重新参数化技术，我们将LoRA参数融入边缘端模型，实现灵活专门化。这不仅促进模型间知识迁移，还通过减少输入上下文长度显著提升推理效率。无需专门训练，LoRA-Gen超越传统LoRA微调方法，与TinyLLaMA-1.1B在推理任务中实现竞争力准确性和2.1倍速度提升。此外，我们在Gemma-2B上的方法在智能体任务中实现10.1倍压缩率。

> Recent advances have highlighted the benefits of scaling language models to enhance performance across a wide range of NLP tasks. However, these approaches still face limitations in effectiveness and efficiency when applied to domain-specific tasks, particularly for small edge-side models. We propose the LoRA-Gen framework, which utilizes a large cloud-side model to generate LoRA parameters for edge-side models based on task descriptions. By employing the reparameterization technique, we merge the LoRA parameters into the edge-side model to achieve flexible specialization. Our method facilitates knowledge transfer between models while significantly improving the inference efficiency of the specialized model by reducing the input context length. Without specialized training, LoRA-Gen outperforms conventional LoRA fine-tuning, which achieves competitive accuracy and a 2.1x speedup with TinyLLaMA-1.1B in reasoning tasks. Besides, our method delivers a compression ratio of 10.1x with Gemma-2B on intelligent agent tasks.

[Arxiv](https://arxiv.org/abs/2506.11638)