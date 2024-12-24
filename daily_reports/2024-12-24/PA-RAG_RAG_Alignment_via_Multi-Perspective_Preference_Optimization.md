# PA-RAG：借助多视角偏好优化达成 RAG 对齐
发布时间：2024年12月18日

`RAG`
> PA-RAG: RAG Alignment via Multi-Perspective Preference Optimization
>
> 检索增强生成（RAG）的出现减轻了大型语言模型（LLMs）生成内容过时和产生幻觉等问题，不过仍存在诸多局限。当通用的 LLM 充当 RAG 生成器时，往往存在响应信息不充分、响应稳健性差以及引用质量不佳的情况。以往解决这些限制的方法，不管是在生成响应之外添加额外步骤，还是通过监督微调（SFT）优化生成器，都未能完全契合 RAG 的要求。所以，在保持端到端 LLM 形式的同时，从多个偏好角度优化 RAG 生成器仍是一项挑战。为了填补这一空缺，我们提出了用于检索增强生成的多视角偏好对齐（PA-RAG），这是一种全面优化 RAG 系统生成器以满足 RAG 要求的方法。具体而言，我们在不同的提示文档质量场景下，从生成器中采样不同质量的响应，构建高质量的指令微调数据和多视角偏好数据。接着，我们使用 SFT 和直接偏好优化（DPO）来优化生成器。在三个 LLM 的四个问答数据集上开展的大量实验表明，PA-RAG 能够显著提升 RAG 生成器的性能。我们的代码和数据集可在 https://github.com/wujwyi/PA-RAG 获取。
>
> https://arxiv.org/abs/2412.14510

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2412.14510](https://arxiv.org/abs/2412.14510)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)