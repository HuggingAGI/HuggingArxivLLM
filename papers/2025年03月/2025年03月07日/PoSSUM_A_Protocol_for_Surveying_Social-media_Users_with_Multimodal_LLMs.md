# PoSSUM：一种基于多模态大语言模型的社交媒体用户调研协议

发布时间：2025年03月07日

`LLM应用` `社交媒体`

> PoSSUM: A Protocol for Surveying Social-media Users with Multimodal LLMs

# 摘要

> 本文介绍了一款名为 PoSSUM 的开源协议，它通过多模态大型语言模型 (LLMs) 实现了对社交媒体用户的无干扰调查。PoSSUM 利用用户的实时帖子、图片及其他数字痕迹，生成能够反映 LLM 训练数据之外信息的硅样本。为了确保调查结果的代表性，PoSSUM 采用了多级回归与后分层 (MrP) 方法，并结合结构化先验，有效抵消了社交媒体平台的可观察选择偏差。该协议在 2024 年美国总统选举期间得到了实际验证，期间共进行了五次 PoSSUM 调查，并在 GitHub 和 X 平台公开发布。在 10 月 17 日至 26 日进行的最终调查中，PoSSUM 基于 1,054 名 X 用户的合成样本，准确预测了 51 个州中的 50 个州的选举结果，并为共和党候选人分配了 0.65 的胜选概率。值得一提的是，PoSSUM 在州级层面上的偏差也低于大多数 established pollsters。这些结果充分展示了 PoSSUM 作为传统调查方法的全自动、无干扰替代方案的巨大潜力。

> This paper introduces PoSSUM, an open-source protocol for unobtrusive polling of social-media users via multimodal Large Language Models (LLMs). PoSSUM leverages users' real-time posts, images, and other digital traces to create silicon samples that capture information not present in the LLM's training data. To obtain representative estimates, PoSSUM employs Multilevel Regression and Post-Stratification (MrP) with structured priors to counteract the observable selection biases of social-media platforms. The protocol is validated during the 2024 U.S. Presidential Election, for which five PoSSUM polls were conducted and published on GitHub and X. In the final poll, fielded October 17-26 with a synthetic sample of 1,054 X users, PoSSUM accurately predicted the outcomes in 50 of 51 states and assigned the Republican candidate a win probability of 0.65. Notably, it also exhibited lower state-level bias than most established pollsters. These results demonstrate PoSSUM's potential as a fully automated, unobtrusive alternative to traditional survey methods.

[Arxiv](https://arxiv.org/abs/2503.05529)