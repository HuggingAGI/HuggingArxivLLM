# 多模态大型语言模型的推理能力：数据污染与动态评估

发布时间：2025年06月08日

`LLM理论` `多模态` `视觉-语言`

> Reasoning Multimodal Large Language Model: Data Contamination and Dynamic Evaluation

# 摘要

> 多模态大型语言模型（MLLMs）在视觉-语言任务中表现优异，但数据污染问题（训练过程中接触测试集）可能掩盖模型的真实泛化能力。这一问题同样影响到推理型 MLLMs，这些模型通常通过强化学习从潜在被污染的基础模型进行微调。我们提出了一种创新的动态评估框架，旨在更全面地评估 MLLM 的泛化能力，超越传统静态基准。我们不再通过改变输入来测试模型，而是通过改变任务本身来进行评估。使用相同的视觉输入，模型在一系列任务家族（如问答、图像描述、问题生成、验证等）中接受测试，以探究其多样化的功能。这种任务扰动揭示了模型性能是否稳健，还是仅仅依赖于浅层的任务特定线索。我们的方法类似于损失景观的陡峭度分析：针对单一任务过拟合或被污染的模型（陡峭最小值）在任务变化时表现疲软，而具有可泛化解决方案的模型（平缓最小值）则不然。我们开发了一个自动化的评估管道，通过同义句生成和数据破坏采样，由经过校准的评估器对开放生成内容（如描述、问题等）进行评分。将这一框架应用于 MME、RealWorldQA 和 CVRR-ES 等基准测试中的领先图像/视频 MLLMs，我们分析了每个模型的跨任务“能力向量”。实验结果表明，基于模拟测试数据（极端污染）进行微调会极大增强任务特定性能，但同时损害模型的整体泛化能力。我们的动态任务扰动方法为理解 MLLM 泛化提供了更深入的见解，能够有效区分模型的真正理解能力与虚假信息泄露或过拟合现象。

> Multimodal Large Language Models (MLLMs) show impressive vision-language benchmark performance, yet growing concerns about data contamination (test set exposure during training) risk masking true generalization. This concern extends to reasoning MLLMs, often fine-tuned via reinforcement learning from potentially contaminated base models. We propose a novel dynamic evaluation framework to rigorously assess MLLM generalization, moving beyond static benchmarks. Instead of perturbing inputs, we perturb the task itself. Using the same visual input, models are evaluated across a family of tasks (e.g., QA, captioning, question posing, verification) to probe diverse capabilities. This task perturbation reveals whether model performance is robust or reliant on superficial task-specific cues. Our approach is analogous to loss landscape sharpness: models overfit or contaminated for a single task (sharp minima) falter under task shifts, unlike models with generalizable solutions (flatter minima). We developed an automated pipeline with a calibrated judge scoring open-ended generations (captions, questions) using paraphrase and corruption sampling. Applying this framework to leading image/video MLLMs on benchmarks including MME, RealWorldQA, and CVRR-ES, we analyze each model's cross-task "ability vector." We demonstrate that fine-tuning on simulated test data (extreme contamination) drastically sharpens task-specific performance but harms overall generalization. Our dynamic task perturbation offers deeper insights into MLLM generalization, distinguishing genuine understanding from spurious leakage or overfitting.

[Arxiv](https://arxiv.org/abs/2506.07202)