# 打破探索瓶颈：量规引导式强化学习助力通用LLM推理

发布时间：2025年08月26日

`强化学习` `医疗健康`

> Breaking the Exploration Bottleneck: Rubric-Scaffolded Reinforcement Learning for General LLM Reasoning

# 摘要

> 大型语言模型（LLMs）的最新进展表明，强化学习（RL）在催生推理能力方面潜力巨大。尽管成果喜人，但一个核心难题始终未解：RL的改进依赖于高质量样本的学习，可此类样本的探索却受限于LLMs的固有局限。这实则形成了一个不良循环——无法探索的内容，就无法学习。为此，本研究提出评分标准脚手架强化学习（RuscaRL），一种新型指导性脚手架框架，旨在攻克通用LLM推理的探索瓶颈。具体而言，RuscaRL将清单式评分标准作为双重工具：（1）生成阶段的显式探索脚手架，在任务指令中嵌入不同评分标准作为外部引导，以生成多样化高质量响应；这种引导会随时间逐渐减弱，促使模型内化底层推理模式；（2）训练阶段的可验证利用奖励，以评分标准为参照获得稳健的LLM裁判评分，为通用推理任务的强化学习提供有效支持。大量实验证实，RuscaRL在多个基准测试中表现卓越，在最佳N选评估中有效拓宽了推理边界。值得关注的是，在HealthBench-500数据集上，RuscaRL将Qwen2.5-7B-Instruct的得分从23.6大幅提升至50.3，超越GPT-4.1；此外，我们对Qwen3-30B-A3B-Instruct进行微调后，其在HealthBench-500上的得分达61.1，超越了包括OpenAI-o3在内的主流LLMs。本研究仍在进行中，相关代码、模型及数据集即将发布。

> Recent advances in Large Language Models (LLMs) have underscored the potential of Reinforcement Learning (RL) to facilitate the emergence of reasoning capabilities. Despite the encouraging results, a fundamental dilemma persists as RL improvement relies on learning from high-quality samples, yet the exploration for such samples remains bounded by the inherent limitations of LLMs. This, in effect, creates an undesirable cycle in which what cannot be explored cannot be learned. In this work, we propose Rubric-Scaffolded Reinforcement Learning (RuscaRL), a novel instructional scaffolding framework designed to break the exploration bottleneck for general LLM reasoning. Specifically, RuscaRL introduces checklist-style rubrics as (1) explicit scaffolding for exploration during rollout generation, where different rubrics are provided as external guidance within task instructions to steer diverse high-quality responses. This guidance is gradually decayed over time, encouraging the model to internalize the underlying reasoning patterns; (2) verifiable rewards for exploitation during model training, where we can obtain robust LLM-as-a-Judge scores using rubrics as references, enabling effective RL on general reasoning tasks. Extensive experiments demonstrate the superiority of the proposed RuscaRL across various benchmarks, effectively expanding reasoning boundaries under the best-of-N evaluation. Notably, RuscaRL significantly boosts Qwen2.5-7B-Instruct from 23.6 to 50.3 on HealthBench-500, surpassing GPT-4.1. Furthermore, our fine-tuned variant on Qwen3-30B-A3B-Instruct achieves 61.1 on HealthBench-500, outperforming leading LLMs including OpenAI-o3. This work is still in progress, and we will release the code, the models, and the datasets soon.

[Arxiv](https://arxiv.org/abs/2508.16949)