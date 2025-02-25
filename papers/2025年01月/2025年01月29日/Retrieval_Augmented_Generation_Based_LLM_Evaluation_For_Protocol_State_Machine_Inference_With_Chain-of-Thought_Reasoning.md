# 基于检索增强生成的大语言模型评估：结合链式思维推理的协议状态机推理。

发布时间：2025年01月29日

`LLM应用` `网络安全`

> Retrieval Augmented Generation Based LLM Evaluation For Protocol State Machine Inference With Chain-of-Thought Reasoning

# 摘要

> 本文提出了一种创新的方法，用于评估基于检索增强生成（RAG）的智能体式大型语言模型（LLM）架构在网络协议模糊测试中的效率，特别是在网络数据包种子生成方面。通过结合链式思维（COT）提示技术，该方法专注于提升种子的结构质量，从而引导协议模糊测试框架对协议状态空间进行更广泛的探索。我们的方法采用两阶段策略，结合RAG和文本嵌入技术。第一阶段，智能体动态参考请求评论（RFC）文档知识库，回答有关协议有限状态机（FSM）的问题，并通过迭代推理对检索到的知识进行优化，以实现输出精炼和合适的种子放置。第二阶段，我们基于BLEU、ROUGE和词错误率（WER）等指标，通过将生成的数据包与真实数据包进行对比，评估智能体输出的结构质量。实验结果表明，与基线模型相比，我们的方法在BLEU、ROUGE和WER方面分别提高了18.19%、14.81%和23.45%。这些结果证实了该方法的潜力，能够显著提升基于LLM的协议模糊测试框架，帮助发现隐藏的漏洞。

> This paper presents a novel approach to evaluate the efficiency of a RAG-based agentic Large Language Model (LLM) architecture in network packet seed generation for network protocol fuzzing. Enhanced by chain-of-thought (COT) prompting techniques, the proposed approach focuses on the improvement of the seeds structural quality in order to guide protocol fuzzing frameworks through a wide exploration of the protocol state space. Our method leverages RAG and text embeddings in a two-stages. In the first stage, the agent dynamically refers to the Request For Comments (RFC) documents knowledge base for answering queries regarding the protocol Finite State Machine (FSM), then it iteratively reasons through the retrieved knowledge, for output refinement and proper seed placement. In the second stage, we evaluate the response structure quality of the agent's output, based on metrics as BLEU, ROUGE, and Word Error Rate (WER) by comparing the generated packets against the ground truth packets. Our experiments demonstrate significant improvements of up to 18.19%, 14.81%, and 23.45% in BLEU, ROUGE, and WER, respectively, over baseline models. These results confirm the potential of such approach, improving LLM-based protocol fuzzing frameworks for the identification of hidden vulnerabilities.

[Arxiv](https://arxiv.org/abs/2502.15727)