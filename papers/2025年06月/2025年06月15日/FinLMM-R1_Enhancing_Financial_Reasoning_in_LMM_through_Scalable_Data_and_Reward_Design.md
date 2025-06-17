# FinLMM-R1: 基于可扩展数据与奖励设计优化 LMM 的金融推理能力

发布时间：2025年06月15日

`LLM应用`

> FinLMM-R1: Enhancing Financial Reasoning in LMM through Scalable Data and Reward Design

# 摘要

> 大型多模态模型（LMMs）展现了强大的跨模态推理能力，但在金融应用中，由于高质量多模态推理数据集的匮乏以及现有训练范式效率低下，仍面临诸多挑战。为解决这些问题，我们提出了一体化框架FinLMM-R1，结合自动化可扩展管道（ASP）与增强训练策略，致力于提升LMM的多模态推理能力。ASP通过独立的问答生成与图像-问题对齐范式，有效解决了财务报告中的文本-视觉对齐问题，确保了数据完整性和提取效率。通过ASP，我们从23,397份财务报告中收集了89,378对对齐的图像-问题，涵盖算术推理、统计推理、财务解释和财务知识等任务。此外，我们引入了大型多模态模型中的对抗奖励推理（TAR-LMM），在先前的两阶段训练框架基础上增加了额外的奖励机制。在第一阶段，我们专注于文本任务，通过格式和准确性奖励引导模型生成结构良好的思考内容。在第二阶段，我们构建多图像对比样本，并引入图像选择、思考内容长度和对抗奖励等额外奖励组件，以联合优化LMM在视觉感知、推理效率和逻辑连贯性方面的能力。在7个基准上的广泛实验表明，基于ASP的数据集和训练框架在通用和金融多模态场景下，显著提升了现有推理LMM的回答准确性和推理深度。


> Large Multimodal Models (LMMs) demonstrate significant cross-modal reasoning capabilities. However, financial applications face challenges due to the lack of high-quality multimodal reasoning datasets and the inefficiency of existing training paradigms for reasoning enhancement. To address these issues, we propose an integrated framework, FinLMM-R1, combining an automated and scalable pipeline for data construction with enhanced training strategies to improve the multimodal reasoning of LMM. The Automated and Scalable Pipeline (ASP) resolves textual-visual misalignment in financial reports through a separate paradigm of question-answer generation and image-question alignment, ensuring data integrity and extraction efficiency. Through ASP, we collect 89,378 aligned image-question pairs from 23,397 financial reports, covering tasks such as arithmetic reasoning, statistics reasoning, financial explanation, and financial knowledge. Moreover, we introduce the Thinking with Adversarial Reward in LMM (TAR-LMM), extending the prior two-stage training framework [1] with additional reward mechanisms. In the first stage, we focus on text-only tasks with format and accuracy rewards to guide the model in generating well-structured thinking contents. In the second stage, we construct multi-image contrastive samples with additional reward components including image selection, thinking content length, and adversarial reward to jointly optimize the LMM across visual perception, reasoning efficiency, and logical coherence. Extensive experiments on 7 benchmarks show ASP-derived dataset and training framework significantly improve answer accuracy and reasoning depth over existing reasoning LMMs in both general and financial multimodal contexts.

[Arxiv](https://arxiv.org/abs/2506.13066)