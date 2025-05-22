# Self-GIVE：基于有限结构化知识的联想思维，提升大型语言模型推理能力

发布时间：2025年05月20日

`LLM应用` `生物医学` `问答系统`

> Self-GIVE: Associative Thinking from Limited Structured Knowledge for Enhanced Large Language Model Reasoning

# 摘要

> 面对需要新信息的复杂问题，人们通常会将问题与现有知识关联，从而得出合理答案。例如，评估褪黑激素是否能缓解失眠时，人们可能会将“帮助精神疾病的激素”与“褪黑激素是一种激素，而失眠是一种精神疾病”联系起来，完成推理。大型语言模型（LLMs）同样需要这种关联性思考，特别是在检索到的知识不足以直接回答科学问题时。

基于图的真值外推（Graph Inspired Veracity Extrapolation, GIVE）通过知识图谱（KG）外推结构化知识来解决这一问题。然而，GIVE涉及构建和剪枝大量假设三元组，这限制了其效率和通用性。为此，我们提出了Self-GIVE，这是一个基于检索-强化学习（retrieve-RL）的框架，通过强化学习为LLMs增强自动化的关联性思考。Self-GIVE提取结构化信息和实体集，帮助模型与查询的概念建立联系。

Self-GIVE解决了GIVE的三个关键限制：（1）知识外推过程中的大量LLM调用和令牌开销，（2）由于复杂指令难以在较小规模的LLMs（如3B或7B参数量）上部署，（3）LLM剪枝导致的知识不准确。具体来说，在使用包含135个节点的UMLS知识图谱进行微调后，Self-GIVE在具有挑战性的生物医学问答任务中，将Qwen2.5 3B和7B模型在未见过的样本上的性能分别提升了$	extbf{28.5%$ightarrow$71.4%}$和$	extbf{78.6$ightarrow$90.5%}$。特别地，Self-GIVE使7B模型能够与配备GIVE的GPT-3.5 Turbo相媲美甚至超越，同时将令牌使用量减少了90%以上。Self-GIVE增强了结构化检索和推理与关联性思考的可扩展集成。

> When addressing complex questions that require new information, people often associate the question with existing knowledge to derive a sensible answer. For instance, when evaluating whether melatonin aids insomnia, one might associate "hormones helping mental disorders" with "melatonin being a hormone and insomnia a mental disorder" to complete the reasoning. Large Language Models (LLMs) also require such associative thinking, particularly in resolving scientific inquiries when retrieved knowledge is insufficient and does not directly answer the question. Graph Inspired Veracity Extrapolation (GIVE) addresses this by using a knowledge graph (KG) to extrapolate structured knowledge. However, it involves the construction and pruning of many hypothetical triplets, which limits efficiency and generalizability. We propose Self-GIVE, a retrieve-RL framework that enhances LLMs with automatic associative thinking through reinforcement learning. Self-GIVE extracts structured information and entity sets to assist the model in linking to the queried concepts. We address GIVE's key limitations: (1) extensive LLM calls and token overhead for knowledge extrapolation, (2) difficulty in deploying on smaller LLMs (3B or 7B) due to complex instructions, and (3) inaccurate knowledge from LLM pruning. Specifically, after fine-tuning using self-GIVE with a 135 node UMLS KG, it improves the performance of the Qwen2.5 3B and 7B models by up to $\textbf{28.5%$\rightarrow$71.4%}$ and $\textbf{78.6$\rightarrow$90.5%}$ in samples $\textbf{unseen}$ in challenging biomedical QA tasks. In particular, Self-GIVE allows the 7B model to match or outperform GPT3.5 turbo with GIVE, while cutting token usage by over 90\%. Self-GIVE enhances the scalable integration of structured retrieval and reasoning with associative thinking.

[Arxiv](https://arxiv.org/abs/2505.15062)