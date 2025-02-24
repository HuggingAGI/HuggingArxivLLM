# 在 JSON 中思考：严格遵循 LLM 架构的强化策略

发布时间：2025年02月18日

`LLM应用` `结构化推理`

> Think Inside the JSON: Reinforcement Strategy for Strict LLM Schema Adherence

# 摘要

> 本文探讨了如何利用大型语言模型（LLM）的推理能力来解决严格遵守模式生成的挑战。我们基于DeepSeek R1强化学习框架，提出了一种结合合成推理数据集构建与自定义奖励函数的新型训练管道，采用集团相对策略优化（GRPO）来训练一个15亿参数模型的结构化推理技能。具体而言，我们首先在20,000个样本的无结构到结构数据集上执行R1强化学习，模仿原始DeepSeek R1方法，以建立核心推理能力。随后，我们在另一个10,000个推理样本数据集上进行监督微调，专注于优化下游任务中的模式遵守。尽管训练规模相对较小，仅需8xH100 GPU集群上大约20小时的GRPO训练和1xA100上3小时的SFT训练，我们的模型在确保模式一致性方面表现出了强大的能力。我们将ThinkJSON方法与原始DeepSeek R1（671B）、精简版的DeepSeek R1（Qwen-1.5B和Qwen-7B）以及Gemini 2.0 Flash（70B）进行了对比，展示了其在实际应用中的有效性。我们的结果突显了资源高效框架在模式约束文本生成中的实际效用。

> In this paper, we address the challenge of enforcing strict schema adherence in large language model (LLM) generation by leveraging LLM reasoning capabilities. Building on the DeepSeek R1 reinforcement learning framework, our approach trains structured reasoning skills of a 1.5B parameter model through a novel pipeline that combines synthetic reasoning dataset construction with custom reward functions under Group Relative Policy Optimization (GRPO). Specifically, we first perform R1 reinforcement learning on a 20K sample unstructured-to-structured dataset, mirroring the original DeepSeek R1 methods, to establish core reasoning abilities. Subsequently, we performed supervised fine-tuning on a separate 10K reasoning sample dataset, focusing on refining schema adherence for downstream tasks. Despite the relatively modest training scope, requiring approximately 20 hours on an 8xH100 GPU cluster for GRPO training and 3 hours on 1xA100 for SFT, our model demonstrates robust performance in enforcing schema consistency. We compare our ThinkJSON approach against the original DeepSeek R1 (671B), distilled versions of DeepSeek R1 (Qwen-1.5B and Qwen-7B), and Gemini 2.0 Flash (70B), showcasing its effectiveness in real-world applications. Our results underscore the practical utility of a resource-efficient framework for schema-constrained text generation.

[Arxiv](https://arxiv.org/abs/2502.14905)