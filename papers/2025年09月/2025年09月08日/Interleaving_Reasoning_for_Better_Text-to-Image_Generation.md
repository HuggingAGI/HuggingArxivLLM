# 交织推理：提升文本到图像生成效果

发布时间：2025年09月08日

`LLM应用` `媒体与娱乐`

> Interleaving Reasoning for Better Text-to-Image Generation

# 摘要

> 统一多模态理解与生成模型近年来在图像生成能力上已取得显著进步，但与GPT-4o等深度融合理解与生成的系统相比，在指令遵循度和细节还原度上仍有较大差距。受近期交错推理技术进展的启发，我们探索此类推理能否进一步提升文本到图像（T2I）生成效果。为此，我们提出交错推理生成（IRG）框架，该框架在文本思考与图像合成间交替进行：模型先通过文本思考指导初始图像生成，再通过反思生成结果来优化细粒度细节、视觉质量与美学表现，同时确保语义不变。为高效训练IRG，我们设计了交错推理生成学习（IRGL）方法，聚焦两个子目标：（1）强化初始思考-生成阶段，奠定核心内容与基础质量；（2）实现高质量文本反思，并在后续图像中准确落实这些优化。我们构建了IRGL-300K数据集，该数据集分为六种分解学习模式，全面覆盖文本思考学习与完整的思考-图像轨迹。我们以原生支持交错文本-图像输出的统一基础模型为起点，通过两阶段训练：先构建稳健的思考与反思能力，再在完整思考-图像轨迹数据中高效调优IRG流水线。大量实验表明，该模型达到最先进（SoTA）性能，在GenEval、WISE、TIIF、GenAI-Bench和OneIG-EN等基准测试中实现5-10分的绝对提升，同时在视觉质量和细粒度保真度上也有显著改善。代码、模型权重及数据集将发布于：https://github.com/Osilly/Interleaving-Reasoning-Generation 。

> Unified multimodal understanding and generation models recently have achieve significant improvement in image generation capability, yet a large gap remains in instruction following and detail preservation compared to systems that tightly couple comprehension with generation such as GPT-4o. Motivated by recent advances in interleaving reasoning, we explore whether such reasoning can further improve Text-to-Image (T2I) generation. We introduce Interleaving Reasoning Generation (IRG), a framework that alternates between text-based thinking and image synthesis: the model first produces a text-based thinking to guide an initial image, then reflects on the result to refine fine-grained details, visual quality, and aesthetics while preserving semantics. To train IRG effectively, we propose Interleaving Reasoning Generation Learning (IRGL), which targets two sub-goals: (1) strengthening the initial think-and-generate stage to establish core content and base quality, and (2) enabling high-quality textual reflection and faithful implementation of those refinements in a subsequent image. We curate IRGL-300K, a dataset organized into six decomposed learning modes that jointly cover learning text-based thinking, and full thinking-image trajectories. Starting from a unified foundation model that natively emits interleaved text-image outputs, our two-stage training first builds robust thinking and reflection, then efficiently tunes the IRG pipeline in the full thinking-image trajectory data. Extensive experiments show SoTA performance, yielding absolute gains of 5-10 points on GenEval, WISE, TIIF, GenAI-Bench, and OneIG-EN, alongside substantial improvements in visual quality and fine-grained fidelity. The code, model weights and datasets will be released in: https://github.com/Osilly/Interleaving-Reasoning-Generation .

[Arxiv](https://arxiv.org/abs/2509.06945)