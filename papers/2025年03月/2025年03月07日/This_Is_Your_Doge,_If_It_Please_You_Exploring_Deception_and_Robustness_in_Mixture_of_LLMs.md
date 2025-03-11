# 这是你的狗狗，若你愿意：探索LLM混合体中的欺骗与稳健性

发布时间：2025年03月07日

`LLM应用` `人工智能`

> This Is Your Doge, If It Please You: Exploring Deception and Robustness in Mixture of LLMs

# 摘要

> 大语言模型（LLM）代理混合架构（MoA）通过在推理阶段结合多个LLM的协作，在AlpacaEval 2.0等知名基准测试中展现了卓越性能。然而，对MoA安全性和可靠性的评估仍存在空白。我们首次全面研究了MoA在面对蓄意提供误导性回答的欺骗性LLM代理时的鲁棒性表现。通过分析欺骗信息传播、模型规模和信息可用性等因素，我们揭示了MoA在安全性方面的关键漏洞。

在AlpacaEval 2.0测试中，广受欢迎的LLaMA 3.1-70B模型与3层MoA（包含6个LLM代理）配合使用时，达到了49.2%的长度控制胜率（LC WR）。然而，我们发现只需在MoA中引入一个【数学公式】精心设计的欺骗性代理，性能就会大幅下降至37.9%，几乎完全抵消了MoA带来的所有优势。在多选理解任务QuALITY上，这种影响同样严重，准确率惊人地下跌了48.5%。

受威尼斯总督选举流程启发——该流程旨在最小化外部影响和欺骗——我们提出了一系列无监督防御机制，成功恢复了大部分损失的性能表现。这些机制为提升MoA在实际应用中的安全性提供了重要参考。

> Mixture of large language model (LLMs) Agents (MoA) architectures achieve state-of-the-art performance on prominent benchmarks like AlpacaEval 2.0 by leveraging the collaboration of multiple LLMs at inference time. Despite these successes, an evaluation of the safety and reliability of MoA is missing. We present the first comprehensive study of MoA's robustness against deceptive LLM agents that deliberately provide misleading responses. We examine factors like the propagation of deceptive information, model size, and information availability, and uncover critical vulnerabilities. On AlpacaEval 2.0, the popular LLaMA 3.1-70B model achieves a length-controlled Win Rate (LC WR) of 49.2% when coupled with 3-layer MoA (6 LLM agents). However, we demonstrate that introducing only a $\textit{single}$ carefully-instructed deceptive agent into the MoA can reduce performance to 37.9%, effectively nullifying all MoA gains. On QuALITY, a multiple-choice comprehension task, the impact is also severe, with accuracy plummeting by a staggering 48.5%. Inspired in part by the historical Doge of Venice voting process, designed to minimize influence and deception, we propose a range of unsupervised defense mechanisms that recover most of the lost performance.

[Arxiv](https://arxiv.org/abs/2503.05856)