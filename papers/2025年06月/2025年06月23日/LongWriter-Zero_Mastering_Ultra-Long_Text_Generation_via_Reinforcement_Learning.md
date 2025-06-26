# LongWriter-Zero：借助强化学习，精通超长文本创作

发布时间：2025年06月23日

`LLM应用` `文本生成`

> LongWriter-Zero: Mastering Ultra-Long Text Generation via Reinforcement Learning

# 摘要

> # 摘要
大型语言模型（LLMs）的超长文本生成需求旺盛，但受限于最大生成长度限制和序列增长带来的质量下降，这仍是重大挑战。传统方法如LongWriter依赖于监督微调（SFT）的''教学''方式，但这类方法严重依赖难以构建且成本高昂的合成数据，常缺乏连贯性和一致性，往往过于人工化且结构单调。我们提出了一种无需标注或合成数据的基于激励的方法，从零开始利用强化学习（RL）促进LLMs生成超长、高质量文本的能力。我们从类似R1-Zero的基础模型开始进行RL训练，引导模型在写作过程中进行规划和完善的推理。通过专门的奖励模型，我们引导LLM在长度控制、写作质量和结构格式方面得到提升。实验表明，从Qwen2.5-32B训练得到的LongWriter-Zero模型在长文本写作任务中超越传统SFT方法，在WritingBench和Arena-Write上达到最先进水平，甚至超越了DeepSeek R1和Qwen3-235B等1000亿参数模型。我们已在https://huggingface.co/THU-KEG/LongWriter-Zero-32B开源了数据和模型检查点。


> Ultra-long generation by large language models (LLMs) is a widely demanded scenario, yet it remains a significant challenge due to their maximum generation length limit and overall quality degradation as sequence length increases. Previous approaches, exemplified by LongWriter, typically rely on ''teaching'', which involves supervised fine-tuning (SFT) on synthetic long-form outputs. However, this strategy heavily depends on synthetic SFT data, which is difficult and costly to construct, often lacks coherence and consistency, and tends to be overly artificial and structurally monotonous. In this work, we propose an incentivization-based approach that, starting entirely from scratch and without relying on any annotated or synthetic data, leverages reinforcement learning (RL) to foster the emergence of ultra-long, high-quality text generation capabilities in LLMs. We perform RL training starting from a base model, similar to R1-Zero, guiding it to engage in reasoning that facilitates planning and refinement during the writing process. To support this, we employ specialized reward models that steer the LLM towards improved length control, writing quality, and structural formatting. Experimental evaluations show that our LongWriter-Zero model, trained from Qwen2.5-32B, consistently outperforms traditional SFT methods on long-form writing tasks, achieving state-of-the-art results across all metrics on WritingBench and Arena-Write, and even surpassing 100B+ models such as DeepSeek R1 and Qwen3-235B. We open-source our data and model checkpoints under https://huggingface.co/THU-KEG/LongWriter-Zero-32B

[Arxiv](https://arxiv.org/abs/2506.18841)