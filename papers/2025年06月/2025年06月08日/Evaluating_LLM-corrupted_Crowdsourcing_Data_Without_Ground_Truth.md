# 在没有真实数据的情况下评估被大型语言模型损坏的众包数据

发布时间：2025年06月08日

`LLM应用` `人工智能` `数据标注`

> Evaluating LLM-corrupted Crowdsourcing Data Without Ground Truth

# 摘要

> 生成式 AI 的成功凸显了高质量人类反馈在构建可信 AI 系统中的重要性。然而，随着大型语言模型 (LLMs) 在众包工作者中的广泛应用，一个重大挑战浮现：旨在反映人类输入的数据集可能被 LLM 生成的响应所破坏。现有的 LLM 检测方法通常依赖于文本等高维训练数据，这使得它们不适合用于标注任务，例如多选分类。在这项研究中，我们探讨了“同侪预测”（一种无需真实标签即可评估工作者响应中信息的机制）在缓解众包中 LLM 协助作弊方面的能力，特别是针对标注任务。我们的方法量化了工人答案之间的相关性，同时基于请求者可获得的 (部分) LLM 生成标签进行条件分析。基于先前的研究，我们提出了一种无训练评分机制，并在考虑 LLM 合谋的众包模型下提供了理论保证。我们明确了该方法有效性的条件，并通过实证验证了其在真实世界众包数据集上检测低效作弊行为的鲁棒性。

> The recent success of generative AI highlights the crucial role of high-quality human feedback in building trustworthy AI systems. However, the increasing use of large language models (LLMs) by crowdsourcing workers poses a significant challenge: datasets intended to reflect human input may be compromised by LLM-generated responses. Existing LLM detection approaches often rely on high-dimension training data such as text, making them unsuitable for annotation tasks like multiple-choice labeling. In this work, we investigate the potential of peer prediction -- a mechanism that evaluates the information within workers' responses without using ground truth -- to mitigate LLM-assisted cheating in crowdsourcing with a focus on annotation tasks. Our approach quantifies the correlations between worker answers while conditioning on (a subset of) LLM-generated labels available to the requester. Building on prior research, we propose a training-free scoring mechanism with theoretical guarantees under a crowdsourcing model that accounts for LLM collusion. We establish conditions under which our method is effective and empirically demonstrate its robustness in detecting low-effort cheating on real-world crowdsourcing datasets.

[Arxiv](https://arxiv.org/abs/2506.06991)