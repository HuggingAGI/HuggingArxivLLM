# 探究大型语言模型如何应对多语言场景

发布时间：2024年02月28日

`LLM理论`

> How do Large Language Models Handle Multilingualism?

# 摘要

> LLMs在各类语言任务上表现出色，而本研究聚焦于其如何巧妙应对多语言输入这一问题。我们构建了一个生动的框架，揭示了LLMs内部运作机制：初期阶段，模型将多语言信息转化为英语便于后续理解和解答；中间层次，则通过英语思维模式融合多语言知识，在自注意力与前馈结构的支持下解决问题；最终阶段，模型生成与查询语种匹配的回答。此外，我们创新性地设计了名为$\texttt{PLND}$的并行语言特异性神经元检测技术，无需依赖标签即可发现针对不同语言激活的关键神经元。经过系统化的逐层、逐结构神经元关闭实验，我们证实了提出的框架的有效性。进一步的研究显示，依据此框架，我们能够更高效地强化LLMs的多语言处理能力，同时显著减少训练成本。

> Large language models (LLMs) demonstrate remarkable performance across a spectrum of languages. In this work, we delve into the question: How do LLMs handle multilingualism? We introduce a framework that depicts LLMs' processing of multilingual inputs: In the first several layers, LLMs understand the question, converting multilingual inputs into English to facilitate the task-solving phase. In the intermediate layers, LLMs engage in problem-solving by thinking in English and incorporating multilingual knowledge to obtain factual content, leveraging the self-attention and feed-forward structures, respectively. In the last several layers, LLMs generate responses that align with the original language of the query. In addition, we investigate the existence of language-specific neurons when processing a certain language. To detect neurons activated by the input language, even without labels, we innovatively design a Parallel Language specific Neuron Detection ($\texttt{PLND}$) method that effectively measures the significance of neurons when handling multilingual inputs. By comprehensive ablation analysis through deactivating neurons of different layers and structures, we verify the framework that we propose. Additionally, we demonstrate that we can utilize such a framework to effectively enhance the multilingual ability with much less training effort.

[Arxiv](https://arxiv.org/abs/2402.18815)