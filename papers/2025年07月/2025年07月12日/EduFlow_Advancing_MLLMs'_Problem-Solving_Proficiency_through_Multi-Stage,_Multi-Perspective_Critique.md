# EduFlow: 通过多阶段、多视角批注提升多语言大语言模型的问题解决能力

发布时间：2025年07月12日

`LLM应用` `科学推理`

> EduFlow: Advancing MLLMs' Problem-Solving Proficiency through Multi-Stage, Multi-Perspective Critique

# 摘要

> 多模态大型语言模型（MLLMs）在科学任务上的表现仍然欠佳，尤其是那些需要多步推理和可解释性推理的任务。它们的局限性包括科学推理模式不足、多步推理缺乏全局连贯性、以及缺乏反思性自我纠错能力，使其在有结构的科学场景中难以信赖。我们提出了EduFlow——首个覆盖教育领域科学推理全流程的端到端框架，涵盖了数据选择、基于MCTS的轨迹构建、模型训练和输出优化等环节。其核心是EduPRM，一个过程感知的奖励模型，能够通过标签和理由对推理步骤进行评估。EduPRM通过基于课程学习的三种互补监督源进行训练：MCTS引导的轨迹、注入错误的批评以及师生对话，使其能够动态适应多阶段问题解决和推理过程中的迭代优化。我们进一步提出了EduMCTS，一个针对教育推理任务的领域自适应搜索框架，其中包含了专为教育推理设计的引导动作，例如促进反思性错误修正的自我反思机制。它还利用EduPRM的精细反馈来引导搜索向更高质量的推理轨迹发展。通过自洽性和拒绝采样方法，我们构建了EduMCTS-160K，一个大规模的教育推理轨迹数据集。大量实验表明，EduFlow能够显著提升推理的一致性和连贯性。代码、数据和模型将对外开放。

> Multimodal large language models (MLLMs) still perform poorly on scientific tasks, particularly those requiring multi-step and interpretable reasoning. Their limitations include insufficient scientific reasoning patterns, lack of global coherence in multi-step inference, and the absence of reflective self-correction, making them unreliable in structured scientific contexts. We introduce EduFlow, the first end-to-end framework that covers the full pipeline of educational scientific reasoning, including data selection, MCTS-based trajectory construction, model training, and output optimization. At its core is EduPRM, a process-aware reward model that critiques reasoning steps with tags and justifications. EduPRM is trained via curriculum learning on three complementary supervision sources: MCTS-guided trajectories, error-injected critiques, and teacher-student dialogues, enabling dynamic adaptation to multi-stage problem solving and iterative refinement during inference. We further propose EduMCTS, a domain-adapted search framework that introduces bootstrapping actions specifically designed for educational reasoning, such as a self-reflection mechanism that promotes reflective error correction. It further leverages EduPRM's fine-grained feedback to guide the search toward higher-quality reasoning trajectories. By applying self-consistency and rejection sampling, we constructed EduMCTS-160K, a large-scale dataset of educational reasoning trajectories. Extensive experiments demonstrate that EduFlow enhances reasoning consistency and coherence. Code, data, and models will be released.

[Arxiv](https://arxiv.org/abs/2507.09374)