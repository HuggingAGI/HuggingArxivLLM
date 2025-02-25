# 缓解检索增强多跳问答中的检索迷失问题
发布时间：2025年02月19日

`RAG`
> Mitigating Lost-in-Retrieval Problems in Retrieval Augmented Multi-Hop Question Answering
>
> 本文发现了一个关键问题——"检索丢失"，在检索增强的多跳问答（QA）中，关键实体常被LLMs的子问题分解所遗漏。这种"检索丢失"显著降低了检索性能，破坏了推理链，最终导致错误答案。为了解决这一问题，我们提出了一种名为ChainRAG的渐进式检索和重写方法。该方法通过逐步完成缺失的关键实体，并从句子图中检索相关句子来处理每个子问题，从而生成答案。我们的检索和重写过程环环相扣，形成了一个无缝连接的链条，最终实现了准确的检索和答案。最后，所有检索到的句子和子问题答案都被整合起来，以生成对原始问题的全面回答。我们在三个多跳QA数据集——MuSiQue、2Wiki和HotpotQA上，使用GPT4o-mini、Qwen2.5-72B和GLM-4-Plus三个大型语言模型对ChainRAG进行了评估。实证结果表明，ChainRAG在有效性和效率方面均显著优于现有基线方法。
>
> https://arxiv.org/abs/2502.14245

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2502.14245](https://arxiv.org/abs/2502.14245)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)