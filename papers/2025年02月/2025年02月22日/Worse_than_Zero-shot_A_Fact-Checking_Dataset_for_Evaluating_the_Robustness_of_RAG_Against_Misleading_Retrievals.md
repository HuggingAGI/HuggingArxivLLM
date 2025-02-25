# 比零-shot更糟糕？用于评估RAG在误导性检索下鲁棒性的事实核查数据集

发布时间：2025年02月22日

`RAG` `事实核查`

> Worse than Zero-shot? A Fact-Checking Dataset for Evaluating the Robustness of RAG Against Misleading Retrievals

# 摘要

> 检索增强生成（RAG）在缓解大型语言模型（LLMs）幻觉问题上表现突出，但LLMs在处理误导性检索时仍存在明显短板。尤其是在面对矛盾或有选择性框架的证据时，LLMs往往难以保持自身推理能力，容易受到现实世界中错误信息的干扰。在现实世界中，误导性和矛盾性信息泛滥，尤其是在政治领域，证据常被有选择性地构建、不完整或带有明显倾向性。然而，现有RAG基准测试大多基于理想化的"干净"检索环境，模型只需从高质量文档中准确检索并生成答案即可成功。这种假设与现实条件严重脱节，导致对RAG系统性能的过高评估。为解决这一问题，我们推出RAGuard——首个专注于评估RAG系统在误导性检索环境下稳健性的事实核查数据集。与以往依赖合成噪声的基准测试不同，RAGuard从Reddit讨论中获取真实数据，捕捉自然发生的错误信息。它将检索证据分为支持性、误导性和不相关性三类，为评估RAG系统应对复杂检索信息的能力提供了现实且具有挑战性的测试环境。实验结果表明，面对误导性检索时，所有基于LLM的RAG系统的表现均劣于零-shot基线（即完全不进行检索），凸显了其在噪声环境中的脆弱性。我们相信，RAGuard将推动未来研究，使RAG系统在理想化数据集之外得到改进，从而在现实应用中更加可靠。

> Retrieval-augmented generation (RAG) has shown impressive capabilities in mitigating hallucinations in large language models (LLMs). However, LLMs struggle to handle misleading retrievals and often fail to maintain their own reasoning when exposed to conflicting or selectively-framed evidence, making them vulnerable to real-world misinformation. In such real-world retrieval scenarios, misleading and conflicting information is rampant, particularly in the political domain, where evidence is often selectively framed, incomplete, or polarized. However, existing RAG benchmarks largely assume a clean retrieval setting, where models succeed by accurately retrieving and generating answers from gold-standard documents. This assumption fails to align with real-world conditions, leading to an overestimation of RAG system performance. To bridge this gap, we introduce RAGuard, a fact-checking dataset designed to evaluate the robustness of RAG systems against misleading retrievals. Unlike prior benchmarks that rely on synthetic noise, our dataset constructs its retrieval corpus from Reddit discussions, capturing naturally occurring misinformation. It categorizes retrieved evidence into three types: supporting, misleading, and irrelevant, providing a realistic and challenging testbed for assessing how well RAG systems navigate different retrieval information. Our benchmark experiments reveal that when exposed to misleading retrievals, all tested LLM-powered RAG systems perform worse than their zero-shot baselines (i.e., no retrieval at all), highlighting their susceptibility to noisy environments. To the best of our knowledge, RAGuard is the first benchmark to systematically assess RAG robustness against misleading evidence. We expect this benchmark will drive future research toward improving RAG systems beyond idealized datasets, making them more reliable for real-world applications.

[Arxiv](https://arxiv.org/abs/2502.16101)