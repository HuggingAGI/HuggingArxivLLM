# # 将大型语言模型应用于系统集成自动化

发布时间：2025年04月11日

`LLM应用` `企业计算` `软件工程`

> Adopting Large Language Models to Automated System Integration

# 摘要

> # 摘要
现代企业计算系统通过整合多个子系统，通过涌现行为来解决共同的任务。一种广泛采用的方法是使用基于Web技术（如REST或OpenAPI）实现的服务，分别提供交互机制和服务文档标准。每个服务代表特定的业务功能，允许封装和更轻松的维护。虽然每个服务的维护成本降低了，但整体集成的复杂性却增加了。因此，出现了自动化的服务组合方法来缓解这一问题。然而，由于这些方法依赖于复杂的正式建模，它们在实践中并未获得广泛接受。

在这篇博士论文中，我们分析了将大型语言模型（LLMs）应用于根据自然语言输入自动集成服务的方法。结果是一个可重用的服务组合，例如作为程序代码。尽管生成的结果并不总是完全正确，但它们仍然可以通过为集成工程师提供一个合适的解决方案的近似值而有所帮助，这只需要很少的努力即可投入使用。

我们的研究涉及以下内容：
1. 介绍一种基于LLMs的自动化服务组合的软件架构
2. 分析用于服务发现的检索增强生成（RAG）
3. 提出一种基于自然语言查询的服务发现基准
4. 将基准扩展到完整的服务组合场景

我们已经介绍了我们的软件架构Compositio Prompto，分析了RAG用于服务发现，并提交了服务发现基准的提案。开放的主题主要集中在将服务发现基准扩展到服务组合场景以及改进服务组合生成，例如使用微调或LLM代理。


> Modern enterprise computing systems integrate numerous subsystems to resolve a common task by yielding emergent behavior. A widespread approach is using services implemented with Web technologies like REST or OpenAPI, which offer an interaction mechanism and service documentation standard, respectively. Each service represents a specific business functionality, allowing encapsulation and easier maintenance. Despite the reduced maintenance costs on an individual service level, increased integration complexity arises. Consequently, automated service composition approaches have arisen to mitigate this issue. Nevertheless, these approaches have not achieved high acceptance in practice due to their reliance on complex formal modeling. Within this Ph.D. thesis, we analyze the application of Large Language Models (LLMs) to automatically integrate the services based on a natural language input. The result is a reusable service composition, e.g., as program code. While not always generating entirely correct results, the result can still be helpful by providing integration engineers with a close approximation of a suitable solution, which requires little effort to become operational. Our research involves (i) introducing a software architecture for automated service composition using LLMs, (ii) analyzing Retrieval Augmented Generation (RAG) for service discovery, (iii) proposing a novel natural language query-based benchmark for service discovery, and (iv) extending the benchmark to complete service composition scenarios. We have presented our software architecture as Compositio Prompto, the analysis of RAG for service discovery, and submitted a proposal for the service discovery benchmark. Open topics are primarily the extension of the service discovery benchmark to service composition scenarios and the improvements of the service composition generation, e.g., using fine-tuning or LLM agents.

[Arxiv](https://arxiv.org/abs/2504.08490)