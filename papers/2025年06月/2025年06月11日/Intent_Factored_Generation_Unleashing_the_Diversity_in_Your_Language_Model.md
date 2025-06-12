# 意图分解生成：释放语言模型的无限可能

发布时间：2025年06月11日

`LLM应用` `对话生成`

> Intent Factored Generation: Unleashing the Diversity in Your Language Model

# 摘要

> 从大型语言模型中获取多样化且高质量的样本仍然是一个开放的难题。现有的多样化方法大多仅限于对相同响应进行词级别改写，这不仅限制了推理能力，还导致对话单调乏味。为解决这一问题，我们提出了一种名为意图分解生成（IFG）的新方法，将采样过程分为两个阶段：首先生成语义密集的意图（如摘要或关键词），然后基于原始提示和意图生成最终响应。通过在意图生成阶段采用较高温度以激发概念多样性，同时在最终生成阶段采用较低温度以确保输出连贯，我们成功实现了多样化与质量的平衡。实验表明，IFG 在数学、代码推理、对话生成等任务中均表现出色，不仅提升了 pass@k 和强化学习效果，还通过与直接偏好优化结合实现了更自然的对话交互。我们还开源了一个全新数据集，证明了该方法在通用语言建模任务中的有效性。总之，IFG 是一个简单而有效的多样化生成方案，仅需调整提示和温度即可轻松集成到各类应用中。

> Obtaining multiple meaningfully diverse, high quality samples from Large Language Models for a fixed prompt remains an open challenge. Current methods for increasing diversity often only operate at the token-level, paraphrasing the same response. This is problematic because it leads to poor exploration on reasoning problems and to unengaging, repetitive conversational agents. To address this we propose Intent Factored Generation (IFG), factorising the sampling process into two stages. First, we sample a semantically dense intent, e.g., a summary or keywords. Second, we sample the final response conditioning on both the original prompt and the intent from the first stage. This allows us to use a higher temperature during the intent step to promote conceptual diversity, and a lower temperature during the final generation to ensure the outputs are coherent and self-consistent. Additionally, we find that prompting the model to explicitly state its intent for each step of the chain-of-thought before generating the step is beneficial for reasoning tasks. We demonstrate our method's effectiveness across a diverse set of tasks. We show this method improves both pass@k and Reinforcement Learning from Verifier Feedback on maths and code tasks. For instruction-tuning, we combine IFG with Direct Preference Optimisation to increase conversational diversity without sacrificing reward. Finally, we achieve higher diversity while maintaining the quality of generations on a general language modelling task, using a new dataset of reader comments and news articles that we collect and open-source. In summary, we present a simple method of increasing the sample diversity of LLMs while maintaining performance. This method can be implemented by changing the prompt and varying the temperature during generation, making it easy to integrate into many algorithms for gains across various applications.

[Arxiv](https://arxiv.org/abs/2506.09659)