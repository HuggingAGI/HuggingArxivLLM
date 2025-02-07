# BOLT：无需蒸馏，语言模型中的长链思维引导

发布时间：2025年02月06日

`LLM理论

理由：这篇论文主要探讨了如何通过一种新的方法（BOLT）来引导大型语言模型（LLMs）生成长链思维（LongCoT），从而提升模型的推理能力。论文的核心在于提出了一种理论框架和方法论，用于改进LLMs的推理能力，而不依赖于现有的模型或昂贵的人工注释。因此，这篇论文更侧重于LLM的理论研究和方法创新，而不是具体的应用或实现。` `人工智能`

> BOLT: Bootstrap Long Chain-of-Thought in Language Models without Distillation

# 摘要

> 大型语言模型（LLMs），如OpenAI的o1，展现了卓越的推理能力。o1在回答问题前会生成一个长链思维（LongCoT），帮助模型分析问题、制定计划、反思和回溯，从而解决复杂问题。o1发布后，许多团队尝试复制其LongCoT和推理能力。他们主要依赖从现有模型（如OpenAI-o1、Qwen-QwQ、DeepSeek-R1-Preview）中进行知识蒸馏，但这种方法在系统开发推理能力上存在不确定性。此外，这些研究多集中在数学领域，少数涉及编码，限制了其通用性。本文提出了一种新方法，无需依赖类似o1的模型或昂贵的人工注释，通过从标准指令模型中引导LongCoT（BOLT）来实现。BOLT分为三个阶段：1）在标准指令模型上通过上下文学习引导LongCoT数据；2）LongCoT监督微调；3）在线训练进一步优化LongCoT能力。在引导阶段，仅需构建少量上下文示例（实验中仅10个），证明了该方法的可行性。我们使用Llama-3.1-70B-Instruct引导LongCoT，并将其应用于不同规模的模型（7B、8B、70B）。在Arena-Hard、MT-Bench、WildBench、ZebraLogic、MATH500等基准测试中，我们的方法展现了出色的任务解决和推理能力。

> Large language models (LLMs), such as o1 from OpenAI, have demonstrated remarkable reasoning capabilities. o1 generates a long chain-of-thought (LongCoT) before answering a question. LongCoT allows LLMs to analyze problems, devise plans, reflect, and backtrack effectively. These actions empower LLM to solve complex problems. After the release of o1, many teams have attempted to replicate its LongCoT and reasoning capabilities. In terms of methods, they primarily rely on knowledge distillation with data from existing models with LongCoT capacities (e.g., OpenAI-o1, Qwen-QwQ, DeepSeek-R1-Preview), leaving significant uncertainties on systematically developing such reasoning abilities. In terms of data domains, these works focus narrowly on math while a few others include coding, limiting their generalizability. This paper introduces a novel approach to enable LLM's LongCoT capacity without distillation from o1-like models or expensive human annotations, where we bootstrap LongCoT (BOLT) from a standard instruct model. BOLT involves three stages: 1) LongCoT data bootstrapping with in-context learning on a standard instruct model; 2) LongCoT supervised finetuning; 3) online training to further refine LongCoT capacities. In BOLT, only a few in-context examples need to be constructed during the bootstrapping stage; in our experiments, we created 10 examples, demonstrating the feasibility of this approach. We use Llama-3.1-70B-Instruct to bootstrap LongCoT and apply our method to various model scales (7B, 8B, 70B). We achieve impressive performance on a variety of benchmarks, Arena-Hard, MT-Bench, WildBench, ZebraLogic, MATH500, which evaluate diverse task-solving and reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2502.03860)