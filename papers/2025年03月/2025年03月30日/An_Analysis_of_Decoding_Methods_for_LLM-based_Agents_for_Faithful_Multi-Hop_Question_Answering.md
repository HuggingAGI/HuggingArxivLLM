# # 基于LLM的多跳问答解码方法分析：忠实答案的实现路径

发布时间：2025年03月30日

`LLM应用` `问答系统`

> An Analysis of Decoding Methods for LLM-based Agents for Faithful Multi-Hop Question Answering

# 摘要

> 大型语言模型 (LLMs) 常常因“幻觉”现象导致输出事实不准确，这限制了其在知识密集型 NLP 任务中的表现。检索增强生成与智能体框架（如 ReAct）通过引入外部知识可有效缓解此问题，但 LLMs 仍常偏离检索信息。尤其在需推理检索内容时，提升忠实度至关重要。近期研究聚焦于无训练解码策略以改善生成忠实度。我们系统研究了 ReAct 框架与解码策略（DeCoRe、DoLa、CAD）的结合对 LLM 生成答案忠实度的影响。实验结果表明，结合智能体框架与增强忠实度的解码方法，显著提升了多跳问答任务的准确性。例如，在 HotpotQA 上，使用 ReAct 和 DoLa 使 F1 值从 19.5 升至 32.6。

> Large Language Models (LLMs) frequently produce factually inaccurate outputs - a phenomenon known as hallucination - which limits their accuracy in knowledge-intensive NLP tasks. Retrieval-augmented generation and agentic frameworks such as Reasoning and Acting (ReAct) can address this issue by giving the model access to external knowledge. However, LLMs often fail to remain faithful to retrieved information. Mitigating this is critical, especially if LLMs are required to reason about the retrieved information. Recent research has explored training-free decoding strategies to improve the faithfulness of model generations. We present a systematic analysis of how the combination of the ReAct framework and decoding strategies (i.e., DeCoRe, DoLa, and CAD) can influence the faithfulness of LLM-generated answers. Our results show that combining an agentic framework for knowledge retrieval with decoding methods that enhance faithfulness can increase accuracy on the downstream Multi-Hop Question Answering tasks. For example, we observe an F1 increase from 19.5 to 32.6 on HotpotQA when using ReAct and DoLa.

[Arxiv](https://arxiv.org/abs/2503.23415)