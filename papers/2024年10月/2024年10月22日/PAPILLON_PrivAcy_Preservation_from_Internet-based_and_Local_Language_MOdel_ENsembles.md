# PAPILLON: 互联网与本地语言模型集成的隐私保护方案

发布时间：2024年10月22日

`LLM应用

理由：这篇论文讨论了如何通过结合API模型和本地模型来保护用户隐私，同时保持高质量的输出。这涉及到LLM在实际应用中的使用和优化，特别是隐私保护和任务简化方面的应用。因此，它属于LLM应用的范畴。` `隐私保护`

> PAPILLON: PrivAcy Preservation from Internet-based and Local Language MOdel ENsembles

# 摘要

> 用户向专有LLM提供商泄露敏感信息可能引发严重的隐私问题。虽然本地托管的开源模型缓解了部分担忧，但其能力通常不及前沿专有模型。为在保护隐私的同时保持高质量，我们提出了隐私意识委托（Privacy-Conscious Delegation），通过链接API模型与本地模型来实现。我们利用公开的用户-LLM交互数据构建了包含个人身份信息（PII）的PUPA基准。为探索解决方案，我们设计了多阶段LLM管道PAPILLON，通过提示优化简化任务。最佳管道在85.5%的用户查询中保持了高质量响应，隐私泄露率仅为7.5%。未来工作将继续提升生成质量，数据和代码可在https://github.com/siyan-sylvia-li/PAPILLON获取。

> Users can divulge sensitive information to proprietary LLM providers, raising significant privacy concerns. While open-source models, hosted locally on the user's machine, alleviate some concerns, models that users can host locally are often less capable than proprietary frontier models. Toward preserving user privacy while retaining the best quality, we propose Privacy-Conscious Delegation, a novel task for chaining API-based and local models. We utilize recent public collections of user-LLM interactions to construct a natural benchmark called PUPA, which contains personally identifiable information (PII). To study potential approaches, we devise PAPILLON, a multi-stage LLM pipeline that uses prompt optimization to address a simpler version of our task. Our best pipeline maintains high response quality for 85.5% of user queries while restricting privacy leakage to only 7.5%. We still leave a large margin to the generation quality of proprietary LLMs for future work. Our data and code will be available at https://github.com/siyan-sylvia-li/PAPILLON.

[Arxiv](https://arxiv.org/abs/2410.17127)