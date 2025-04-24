# Harden和Catch：即时确信的基于LLM的软件测试中的开放研究挑战

发布时间：2025年04月23日

`LLM应用

理由：论文探讨了大型语言模型（LLMs）在软件测试生成中的应用，特别是强化测试和捕获测试的概念，以及如何利用LLMs来解决“及时捕获”（JiTTest）挑战。这些内容属于LLM在特定领域（软件测试）的应用研究，因此归类为LLM应用。` `软件测试` `自动化`

> Harden and Catch for Just-in-Time Assured LLM-Based Software Testing: Open Research Challenges

# 摘要

> 尽管自动化软件测试领域已有数十年的研究积累，但仍有多个关键概念尚未得到充分探索，这些概念却具有巨大的实际应用潜力。本文展示了这些概念在大型语言模型（LLMs）用于软件测试生成的背景下所带来的全新挑战。我们正式定义并深入研究了强化测试和捕获测试的特性。强化测试旨在预防未来的回归错误，而捕获测试则是用于识别因代码更改而引入的新功能中的回归错误或缺陷。强化测试可以在任何时间生成，并可能在捕获未来的回归错误时转化为捕获测试。我们还提出了“及时捕获”（JiTTest）挑战，强调在缺陷进入生产环境之前“及时”生成测试以捕获这些缺陷。我们证明，任何解决JiTTest生成的方法同样适用于捕获遗留代码中的潜在缺陷。本文列举了强化测试、捕获测试和JiTTest的可能结果，并探讨了开放的研究问题、部署选项以及我们在Meta进行的基于LLM的自动化强化测试工作的初步成果。本文ootnote{作者按字母顺序排列。通讯作者是Mark Harman。}是为配合作者在2025年ACM国际软件工程基础会议上发表的主题演讲而撰写。

> Despite decades of research and practice in automated software testing, several fundamental concepts remain ill-defined and under-explored, yet offer enormous potential real-world impact. We show that these concepts raise exciting new challenges in the context of Large Language Models for software test generation. More specifically, we formally define and investigate the properties of hardening and catching tests. A hardening test is one that seeks to protect against future regressions, while a catching test is one that catches such a regression or a fault in new functionality introduced by a code change. Hardening tests can be generated at any time and may become catching tests when a future regression is caught. We also define and motivate the Catching `Just-in-Time' (JiTTest) Challenge, in which tests are generated `just-in-time' to catch new faults before they land into production. We show that any solution to Catching JiTTest generation can also be repurposed to catch latent faults in legacy code. We enumerate possible outcomes for hardening and catching tests and JiTTests, and discuss open research problems, deployment options, and initial results from our work on automated LLM-based hardening at Meta. This paper\footnote{Author order is alphabetical. The corresponding author is Mark Harman.} was written to accompany the keynote by the authors at the ACM International Conference on the Foundations of Software Engineering (FSE) 2025.

[Arxiv](https://arxiv.org/abs/2504.16472)