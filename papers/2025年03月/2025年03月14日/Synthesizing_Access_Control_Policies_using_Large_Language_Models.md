# *基于大型语言模型生成访问控制策略*

发布时间：2025年03月14日

`LLM应用` `云计算`

> Synthesizing Access Control Policies using Large Language Models

# 摘要

> 云计算系统支持管理员编写访问控制策略，以规范对私有数据的访问权限。尽管这些策略可以借助方便的语言（如AWS身份和访问管理策略语言）进行编写，但手动编写的策略往往会变得复杂且容易出错。本文探讨了大型语言模型（LLMs）在合成访问控制策略方面的潜力及其效果。我们的研究专注于将访问控制请求规范与零样本提示相结合，以生成结构严谨且符合请求规范的访问控制策略。我们分析了两种场景：一种是将请求规范具体化为允许或拒绝的请求列表，另一种是通过自然语言描述来指定允许或拒绝的请求集合。我们进一步论证了在零样本提示中，采用基于语法的精确且结构化的提示是必要的，并通过实验初步验证了我们的方法的有效性。

> Cloud compute systems allow administrators to write access control policies that govern access to private data. While policies are written in convenient languages, such as AWS Identity and Access Management Policy Language, manually written policies often become complex and error prone. In this paper, we investigate whether and how well Large Language Models (LLMs) can be used to synthesize access control policies. Our investigation focuses on the task of taking an access control request specification and zero-shot prompting LLMs to synthesize a well-formed access control policy which correctly adheres to the request specification. We consider two scenarios, one which the request specification is given as a concrete list of requests to be allowed or denied, and another in which a natural language description is used to specify sets of requests to be allowed or denied. We then argue that for zero-shot prompting, more precise and structured prompts using a syntax based approach are necessary and experimentally show preliminary results validating our approach.

[Arxiv](https://arxiv.org/abs/2503.11573)