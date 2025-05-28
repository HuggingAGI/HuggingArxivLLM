# # 自动传输层：大型语言模型中的成本与精度优化
自动传输层：在大型语言模型中优化成本和精度

发布时间：2025年05月27日

`LLM应用

理由：这篇论文主要探讨了如何优化大型语言模型（LLM）的使用，特别是在多级模型选择和成本性能平衡方面。它提出了一个无需训练的框架，用于自动选择合适的模型级别，属于LLM的应用层面。` `系统优化`

> Automatic Transmission for LLM Tiers: Optimizing Cost and Accuracy in Large Language Models

# 摘要

> LLM 提供商通常会提供多个 LLM 级别，这些级别在性能和价格上有所不同。随着 NLP 任务变得越来越复杂和模块化，为每个子任务选择合适的 LLM 级别成为在成本与性能之间找到平衡的关键挑战。为了解决这一问题，我们提出了无需训练的 LLM 自动变速（LLM-AT）框架，该框架能够自动选择 LLM 级别。LLM-AT 包括 Starter、Generator 和 Judge 三个部分：Starter 选择预期能够解决给定问题的初始 LLM 级别，Generator 使用所选级别的 LLM 生成响应，而 Judge 评估响应的有效性。如果响应无效，LLM-AT 会迭代升级到更高一级的模型，生成新的响应并重新评估，直到获得有效的响应。此外，我们还提出了准确性估计器，无需训练即可实现合适的初始 LLM 级别选择。给定一个输入问题，准确性估计器通过计算过去推理记录中 top-k 相似查询的有效响应率，来估计每个 LLM 级别的预期准确性。实验结果表明，LLM-AT 在提升性能的同时降低了成本，使其成为适用于实际应用场景的实用解决方案。

> LLM providers typically offer multiple LLM tiers, varying in performance and price. As NLP tasks become more complex and modularized, selecting the suitable LLM tier for each subtask is a key challenge to balance between cost and performance. To address the problem, we introduce LLM Automatic Transmission (LLM-AT) framework that automatically selects LLM tiers without training. LLM-AT consists of Starter, Generator, and Judge. The starter selects the initial LLM tier expected to solve the given question, the generator produces a response using the LLM of the selected tier, and the judge evaluates the validity of the response. If the response is invalid, LLM-AT iteratively upgrades to a higher-tier model, generates a new response, and re-evaluates until a valid response is obtained. Additionally, we propose accuracy estimator, which enables the suitable initial LLM tier selection without training. Given an input question, accuracy estimator estimates the expected accuracy of each LLM tier by computing the valid response rate across top-k similar queries from past inference records. Experiments demonstrate that LLM-AT achieves superior performance while reducing costs, making it a practical solution for real-world applications.

[Arxiv](https://arxiv.org/abs/2505.20921)