# LRASGen：基于大型语言模型的RESTful API规范生成
发布时间：2025年04月23日


> LRASGen: LLM-based RESTful API Specification Generation
>
> # 表述性状态转移 (REST) 架构风格
REST 是一种用于设计 web 应用程序的架构风格，它通过常见的 HTTP 技术实现了客户端和服务器之间的可扩展、无状态通信。采用 REST 风格的 Web API 被称为 RESTful（或 REST）API。在使用或测试 RESTful API 时，开发者通常需要参考其规范，这些规范通常由开源标准（如 OpenAPI Specification，OAS）定义。然而，编写和更新这些规范既耗时又容易出错，这可能对 RESTful API 的使用产生负面影响，尤其是在软件需求发生变化时。为了解决这个问题，人们提出了许多工具和方法，例如 Respector 和 Swagger Core。OAS 生成可以被视为一种常见的文本生成任务，其目标是根据源代码创建 API 端点的正式描述。一个潜在的解决方案可能涉及使用大型语言模型（LLMs），因为它们在代码理解和文本生成方面都具有强大的能力。受到这一启发，我们提出了一种基于 LLM 生成 RESTful API 的 OAS 的新方法：基于 LLM 的 RESTful API 规范生成（LRASGen）。据我们所知，这是首次利用 LLM 和 API 源代码为 RESTful API 生成 OAS。与现有工具和方法相比，LRASGen 的优势在于，即使在实现不完整（例如部分代码，和/或缺少注释/注释等）的情况下，它仍然可以生成 OAS。为了评估 LRASGen 的性能，我们在 20 个真实世界的 RESTful API 上进行了一系列实证研究。结果表明，两种 LLM（GPT-4o mini 和 DeepSeek V3）都可以支持 LARSGen 生成准确的规范，且 LRASGen 生成的规范比开发者提供的规范平均多覆盖了 48.85% 的缺失实体。
>
> https://arxiv.org/abs/2504.16833

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2504.16833](https://arxiv.org/abs/2504.16833)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)