# MOTIF：大型语言模型中通过强化微调实现模块化思维

发布时间：2025年07月03日

`LLM理论` `人工智能`

> MOTIF: Modular Thinking via Reinforcement Fine-tuning in LLMs

# 摘要

> 近期研究显示，采用组相对策略优化（GRPO）算法进行强化学习（RL）训练，可使大型语言模型在生成更优质回复时使用更多思考/推理token。然而，LLMs在生成有限数量的token时，必须持续关注之前生成的内容，这一限制也称为LLM的上下文大小，是其处理大量token时推理能力的瓶颈。为突破上下文大小限制，LLMs需采用模块化思考策略，在多轮推理中进行推理。本研究提出$	extbf{MOTIF: Modular Thinking via Reinforcement Finetuning}$——一种用于多轮生成思考token的RL训练方法，使模型能够利用额外上下文大小进行思考。我们通过参数高效微调在GSM8K数据集上训练开源模型Qwen2.5-3B-Instruct，并在MATH500和AIME2024基准测试中评估其准确性。实验结果显示，与基于原始GRPO的训练相比，MOTIF在相应基准测试中分别提升了3.8%和3.3%。此外，这一改进仅使用了15%的样本，充分展现了MOTIF的样本效率。我们的代码和模型可在https://github.com/purbeshmitra/MOTIF和https://huggingface.co/purbeshmitra/MOTIF上获取。

> Recent advancements in the reasoning capabilities of large language models (LLMs) show that employing group relative policy optimization (GRPO) algorithm for reinforcement learning (RL) training allows the models to use more thinking/reasoning tokens for generating better responses. However, LLMs can generate only a finite amount of tokens while maintaining attention to the previously generated tokens. This limit, also known as the context size of an LLM, is a bottleneck in LLM reasoning with arbitrarily large number of tokens. To think beyond the limit of context size, an LLM must employ a modular thinking strategy to reason over multiple rounds. In this work, we propose $\textbf{MOTIF: Modular Thinking via Reinforcement Finetuning}$ -- an RL training method for generating thinking tokens in multiple rounds, effectively allowing the model to think with additional context size. We trained the open-source model Qwen2.5-3B-Instruct on GSM8K dataset via parameter efficient fine-tuning and tested its accuracy on MATH500 and AIME2024 benchmarks. Our experiments show 3.8\% and 3.3\% improvements over vanilla GRPO based training in the respective benchmarks. Furthermore, this improvement was achieved with only 15\% of samples, thus demonstrating sample efficiency of MOTIF. Our code and models are available at https://github.com/purbeshmitra/MOTIF and https://huggingface.co/purbeshmitra/MOTIF, respectively.

[Arxiv](https://arxiv.org/abs/2507.02851)