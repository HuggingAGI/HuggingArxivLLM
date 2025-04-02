# # 基于LLM的多跳问答解码方法分析：忠实答案的实现路径
发布时间：2025年03月30日


> An Analysis of Decoding Methods for LLM-based Agents for Faithful Multi-Hop Question Answering
>
> 大型语言模型 (LLMs) 常常因“幻觉”现象导致输出事实不准确，这限制了其在知识密集型 NLP 任务中的表现。检索增强生成与智能体框架（如 ReAct）通过引入外部知识可有效缓解此问题，但 LLMs 仍常偏离检索信息。尤其在需推理检索内容时，提升忠实度至关重要。近期研究聚焦于无训练解码策略以改善生成忠实度。我们系统研究了 ReAct 框架与解码策略（DeCoRe、DoLa、CAD）的结合对 LLM 生成答案忠实度的影响。实验结果表明，结合智能体框架与增强忠实度的解码方法，显著提升了多跳问答任务的准确性。例如，在 HotpotQA 上，使用 ReAct 和 DoLa 使 F1 值从 19.5 升至 32.6。
>
> https://arxiv.org/abs/2503.23415

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.23415](https://arxiv.org/abs/2503.23415)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)