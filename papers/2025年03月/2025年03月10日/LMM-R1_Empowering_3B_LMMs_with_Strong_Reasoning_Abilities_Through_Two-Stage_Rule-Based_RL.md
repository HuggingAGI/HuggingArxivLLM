# LMM-R1：助力30亿参数的大型语言模型具备强大推理能力

发布时间：2025年03月10日

`LLM应用` `人工智能` `计算机视觉`

> LMM-R1: Empowering 3B LMMs with Strong Reasoning Abilities Through Two-Stage Rule-Based RL

# 摘要

> 提升大型多模态模型（LMMs）的推理能力，面临着视觉感知与逻辑推理之间复杂交互带来的独特挑战，尤其在参数量较小的3B架构中，架构限制进一步制约了推理能力和模态对齐。尽管基于规则的强化学习（RL）在纯文本领域表现出色，但其多模态扩展却面临两大关键障碍：（1）由于答案模糊和复杂推理示例稀缺导致的数据限制；（2）多模态预训练引发的基础推理能力下降。针对这些挑战，我们提出	extbf{\method}，一个分阶段的框架，通过	extbf{基础推理增强（FRE）}和随后的	extbf{多模态泛化训练（MGT）}，将基于规则的RL适应于多模态推理。FRE阶段首先利用纯文本数据和基于规则的RL强化推理能力，随后MGT阶段将这些推理能力泛化到多模态领域。在Qwen2.5-VL-Instruct-3B上的实验表明，与基线相比，\method在多模态和纯文本基准测试中分别实现了4.83%和4.5%的平均提升，并在复杂的Football Game任务中取得了3.63%的性能提升。这些结果验证了基于文本的推理增强能够实现有效的多模态泛化，提供了一种数据高效的范式，绕过了对昂贵的高质量多模态训练数据的依赖。

> Enhancing reasoning in Large Multimodal Models (LMMs) faces unique challenges from the complex interplay between visual perception and logical reasoning, particularly in compact 3B-parameter architectures where architectural constraints limit reasoning capacity and modality alignment.
  While rule-based reinforcement learning (RL) excels in text-only domains, its multimodal extension confronts two critical barriers: (1) data limitations due to ambiguous answers and scarce complex reasoning examples, and (2) degraded foundational reasoning induced by multimodal pretraining.
  To address these challenges, we propose \textbf{\method}, a two-stage framework adapting rule-based RL for multimodal reasoning through \textbf{Foundational Reasoning Enhancement (FRE)} followed by \textbf{Multimodal Generalization Training (MGT)}. The FRE stage first strengthens reasoning abilities using text-only data with rule-based RL, then the MGT stage generalizes these reasoning capabilities to multimodal domains.
  Experiments on Qwen2.5-VL-Instruct-3B demonstrate that \method achieves 4.83\% and 4.5\% average improvements over baselines in multimodal and text-only benchmarks, respectively, with a 3.63\% gain in complex Football Game tasks. These results validate that text-based reasoning enhancement enables effective multimodal generalization, offering a data-efficient paradigm that bypasses costly high-quality multimodal training data.

[Arxiv](https://arxiv.org/abs/2503.07536)