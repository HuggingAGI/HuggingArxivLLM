# 有限状态机引导的基于LLM智能合约生成

发布时间：2025年05月13日

`LLM应用` `区块链` `智能合约`

> Guiding LLM-based Smart Contract Generation with Finite State Machine

# 摘要

> 智能合约是一种基于区块链技术的自动执行代码，拥有广泛的应用场景。然而，传统的生成方法依赖手动编码和专家审核，存在高门槛和低效率的问题。尽管大型语言模型（LLMs）在编程任务中展现出巨大潜力，但在智能合约生成方面，它们仍面临有效性和安全性的挑战。为解决这些问题，我们提出了FSM-SCG——一个基于有限状态机（FSM）和LLMs的智能合约生成框架。通过将用户需求抽象为FSM，指导LLMs生成智能合约，并利用编译和安全检查的反馈进行迭代优化，FSM-SCG显著提升了生成代码的质量。实验结果表明，FSM-SCG大幅提高了智能合约生成的质量。与最佳基线相比，FSM-SCG将生成智能合约代码的编译成功率提高了最多48%，并将平均漏洞风险评分降低了约68%。

> Smart contract is a kind of self-executing code based on blockchain technology with a wide range of application scenarios, but the traditional generation method relies on manual coding and expert auditing, which has a high threshold and low efficiency. Although Large Language Models (LLMs) show great potential in programming tasks, they still face challenges in smart contract generation w.r.t. effectiveness and security. To solve these problems, we propose FSM-SCG, a smart contract generation framework based on finite state machine (FSM) and LLMs, which significantly improves the quality of the generated code by abstracting user requirements to generate FSM, guiding LLMs to generate smart contracts, and iteratively optimizing the code with the feedback of compilation and security checks. The experimental results show that FSM-SCG significantly improves the quality of smart contract generation. Compared to the best baseline, FSM-SCG improves the compilation success rate of generated smart contract code by at most 48%, and reduces the average vulnerability risk score by approximately 68%.

[Arxiv](https://arxiv.org/abs/2505.08542)