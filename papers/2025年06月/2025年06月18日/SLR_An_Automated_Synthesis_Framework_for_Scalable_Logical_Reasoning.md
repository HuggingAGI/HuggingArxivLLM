# SLR：用于可扩展逻辑推理的自动化合成框架。

发布时间：2025年06月18日

`LLM理论

理由：这篇论文提出了一种基于可扩展逻辑推理的框架，用于评估和训练大型语言模型，并探讨了模型在逻辑推理方面的表现和改进方法。它专注于模型的理论和训练，属于LLM理论类别。` `人工智能`

> SLR: An Automated Synthesis Framework for Scalable Logical Reasoning

# 摘要

> 我们提出了SLR，一个基于可扩展逻辑推理实现LLMs系统性评估与训练的端到端框架。根据用户提供的任务规范，SLR能够生成难度可控的可扩展自动化归纳推理任务。针对每个任务，SLR会生成（i）潜在的地面真实规则，（ii）用于符号裁判确定性验证模型输出的可执行验证程序，以及（iii）推理任务的指令提示。借助SLR，我们开发了包含19,000多个提示的SLR-Bench基准测试，覆盖20个循序渐进的课程级别，这些级别在关系、算术和递归复杂性上逐步增加。大规模评估表明，当前的大型语言模型能够轻易生成语法正确的规则，但常常在正确的逻辑推理上表现不佳。近期的推理型LLMs表现有所提升，但测试时的计算开销大幅增加，有时甚至超过15,000个完成标记。最后，通过SLR进行的逻辑微调使Llama-3-8B在SLR-Bench上的准确率翻倍，达到了与Gemini-Flash-Thinking相当的水平，但计算成本却大幅降低。SLR完全自动化，无需人工标注，确保了数据集的新颖性，并为探索和提升LLMs的推理能力提供了一个可扩展的环境。

> We introduce SLR, an end-to-end framework for systematic evaluation and training of Large Language Models (LLMs) via Scalable Logical Reasoning. Given a user's task specification, SLR enables scalable, automated synthesis of inductive reasoning tasks with precisely controlled difficulty. For each task, SLR synthesizes (i) a latent ground-truth rule, (ii) an executable validation program used by a symbolic judge to deterministically verify model outputs, and (iii) an instruction prompt for the reasoning task. Using SLR, we create SLR-Bench, a benchmark comprising over 19k prompts spanning 20 curriculum levels that progressively increase in relational, arithmetic, and recursive complexity. Large-scale evaluation reveals that contemporary LLMs readily produce syntactically valid rules, yet often fail at correct logical inference. Recent reasoning LLMs do somewhat better, but incur substantial increases in test-time compute, sometimes exceeding 15k completion tokens. Finally, logic-tuning via SLR doubles Llama-3-8B accuracy on SLR-Bench, achieving parity with Gemini-Flash-Thinking at a fraction of computational cost. SLR is fully automated, requires no human annotation, ensures dataset novelty, and offers a scalable environment for probing and advancing LLMs' reasoning capabilities.

[Arxiv](https://arxiv.org/abs/2506.15787)