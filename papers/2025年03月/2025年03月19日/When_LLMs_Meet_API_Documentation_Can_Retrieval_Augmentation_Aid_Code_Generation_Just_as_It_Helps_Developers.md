# 当大型语言模型遇到API文档：检索增强能否像帮助开发者一样助力代码生成？

发布时间：2025年03月19日

`RAG` `软件工程` `人工智能`

> When LLMs Meet API Documentation: Can Retrieval Augmentation Aid Code Generation Just as It Helps Developers?

# 摘要

> 检索增强生成（RAG）正在逐步展现其在扩展大型语言模型（LLMs）能力方面的强大实力，使其超越预训练知识的范畴。现有研究表明，RAG能够助力软件开发任务，如代码生成、代码更新和测试生成。然而，利用RAG将LLMs适应快速演变或不常见的API库的有效性仍是一个未知数。为填补这一研究空白，我们迈出第一步，探讨这一未被充分研究但具有实际意义的场景：当开发者使用不常见的库编写代码时，他们通常会参考其API文档；同样地，当允许LLMs通过RAG查阅API文档时，LLMs的能力能提升到何种程度？为了模拟这一场景，我们选取了四个不常见的开源Python库，共计1017个符合条件的API。我们研究了将不常见API库的文档作为检索和生成的附加知识时，影响其有效性的因素。我们深入研究得出了有趣的发现：（1）RAG帮助提升了LLMs的性能，提升幅度为83%-220%。（2）示例代码对提升LLMs的能力贡献最大，而非API文档中的描述性文本和参数列表。（3）LLMs有时能够通过参考其预训练知识或文档上下文，容忍轻微的噪音（如描述中的拼写错误或不正确的参数）。最后，我们建议开发者更加关注API文档中代码示例的质量和多样性。这项研究为未来的低代码软件开发工作流程提供了新的视角。


> Retrieval-augmented generation (RAG) has increasingly shown its power in extending large language models' (LLMs') capability beyond their pre-trained knowledge. Existing works have shown that RAG can help with software development tasks such as code generation, code update, and test generation. Yet, the effectiveness of adapting LLMs to fast-evolving or less common API libraries using RAG remains unknown. To bridge this gap, we take an initial step to study this unexplored yet practical setting - when developers code with a less common library, they often refer to its API documentation; likewise, when LLMs are allowed to look up API documentation via RAG, to what extent can LLMs be advanced? To mimic such a setting, we select four less common open-source Python libraries with a total of 1017 eligible APIs. We study the factors that affect the effectiveness of using the documentation of less common API libraries as additional knowledge for retrieval and generation. Our intensive study yields interesting findings: (1) RAG helps improve LLMs' performance by 83%-220%. (2) Example code contributes the most to advance LLMs, instead of the descriptive texts and parameter lists in the API documentation. (3) LLMs could sometimes tolerate mild noises (typos in description or incorrect parameters) by referencing their pre-trained knowledge or document context. Finally, we suggest that developers pay more attention to the quality and diversity of the code examples in the API documentation. The study sheds light on future low-code software development workflows.

[Arxiv](https://arxiv.org/abs/2503.15231)