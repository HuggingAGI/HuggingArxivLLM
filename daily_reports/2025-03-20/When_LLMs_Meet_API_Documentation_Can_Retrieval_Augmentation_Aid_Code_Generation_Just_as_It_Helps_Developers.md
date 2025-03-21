# 当大型语言模型遇到API文档：检索增强能否像帮助开发者一样助力代码生成？
发布时间：2025年03月19日

`代码编写`
> When LLMs Meet API Documentation: Can Retrieval Augmentation Aid Code Generation Just as It Helps Developers?
>
> 检索增强生成（RAG）正在逐步展现其在扩展大型语言模型（LLMs）能力方面的强大实力，使其超越预训练知识的范畴。现有研究表明，RAG能够助力软件开发任务，如代码生成、代码更新和测试生成。然而，利用RAG将LLMs适应快速演变或不常见的API库的有效性仍是一个未知数。为填补这一研究空白，我们迈出第一步，探讨这一未被充分研究但具有实际意义的场景：当开发者使用不常见的库编写代码时，他们通常会参考其API文档；同样地，当允许LLMs通过RAG查阅API文档时，LLMs的能力能提升到何种程度？为了模拟这一场景，我们选取了四个不常见的开源Python库，共计1017个符合条件的API。我们研究了将不常见API库的文档作为检索和生成的附加知识时，影响其有效性的因素。我们深入研究得出了有趣的发现：（1）RAG帮助提升了LLMs的性能，提升幅度为83%-220%。（2）示例代码对提升LLMs的能力贡献最大，而非API文档中的描述性文本和参数列表。（3）LLMs有时能够通过参考其预训练知识或文档上下文，容忍轻微的噪音（如描述中的拼写错误或不正确的参数）。最后，我们建议开发者更加关注API文档中代码示例的质量和多样性。这项研究为未来的低代码软件开发工作流程提供了新的视角。
>
> https://arxiv.org/abs/2503.15231

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2503.15231](https://arxiv.org/abs/2503.15231)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)