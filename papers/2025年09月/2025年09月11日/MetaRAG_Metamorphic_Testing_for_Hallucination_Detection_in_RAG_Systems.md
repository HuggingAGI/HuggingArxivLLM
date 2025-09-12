# MetaRAG：RAG系统幻觉检测的蜕变测试

发布时间：2025年09月11日

`RAG` `法律科技`

> MetaRAG: Metamorphic Testing for Hallucination Detection in RAG Systems

# 摘要

> 大型语言模型（LLMs）在企业应用中的部署日益广泛，但幻觉问题（即生成自信却与事实不符的信息）仍限制着其可靠性。现有的检测方法（如SelfCheckGPT和MetaQA）主要针对独立LLM，却未能应对检索增强生成（RAG）系统的特殊挑战——RAG的响应需与检索到的证据保持一致。为此，我们提出MetaRAG——一个用于RAG系统幻觉检测的变形测试框架。

MetaRAG在实时、无监督的黑盒环境中运行，无需真实参考或模型内部访问权限，因此适用于专有及高风险领域。该框架分为四个阶段：（1）将答案分解为原子事实单元；（2）通过同义词和反义词替换，为每个事实单元生成受控变体；（3）根据检索到的上下文验证每个变体（同义词应被上下文包含，反义词应被上下文矛盾）；（4）将不一致的惩罚汇总为响应级别的幻觉分数。

对于身份感知AI而言，MetaRAG的关键价值在于能定位到不支持声明所在的事实单元跨度（例如怀孕相关注意事项、LGBTQ+难民权利或劳动资格），让用户可查看标记的跨度，并让系统设计者能为身份敏感查询配置阈值和防护措施。在专有企业数据集上的实验表明，MetaRAG能有效检测幻觉，助力基于RAG的对话代理实现可信部署。我们还提出了一种基于主题的部署方案，可将MetaRAG的跨度级分数转化为身份感知防护措施；该方案已进行讨论，但未在实验中评估。

> Large Language Models (LLMs) are increasingly deployed in enterprise applications, yet their reliability remains limited by hallucinations, i.e., confident but factually incorrect information. Existing detection approaches, such as SelfCheckGPT and MetaQA, primarily target standalone LLMs and do not address the unique challenges of Retrieval-Augmented Generation (RAG) systems, where responses must be consistent with retrieved evidence. We therefore present MetaRAG, a metamorphic testing framework for hallucination detection in Retrieval-Augmented Generation (RAG) systems. MetaRAG operates in a real-time, unsupervised, black-box setting, requiring neither ground-truth references nor access to model internals, making it suitable for proprietary and high-stakes domains. The framework proceeds in four stages: (1) decompose answers into atomic factoids, (2) generate controlled mutations of each factoid using synonym and antonym substitutions, (3) verify each variant against the retrieved context (synonyms are expected to be entailed and antonyms contradicted), and (4) aggregate penalties for inconsistencies into a response-level hallucination score. Crucially for identity-aware AI, MetaRAG localizes unsupported claims at the factoid span where they occur (e.g., pregnancy-specific precautions, LGBTQ+ refugee rights, or labor eligibility), allowing users to see flagged spans and enabling system designers to configure thresholds and guardrails for identity-sensitive queries. Experiments on a proprietary enterprise dataset illustrate the effectiveness of MetaRAG for detecting hallucinations and enabling trustworthy deployment of RAG-based conversational agents. We also outline a topic-based deployment design that translates MetaRAG's span-level scores into identity-aware safeguards; this design is discussed but not evaluated in our experiments.

[Arxiv](https://arxiv.org/abs/2509.09360)