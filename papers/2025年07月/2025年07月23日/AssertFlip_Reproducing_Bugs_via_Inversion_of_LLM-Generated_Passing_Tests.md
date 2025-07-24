# AssertFlip：利用LLM生成的通过测试的逆过程来复现错误

发布时间：2025年07月23日

`LLM应用` `软件工程`

> AssertFlip: Reproducing Bugs via Inversion of LLM-Generated Passing Tests

# 摘要

> Bug复现是软件调试和修复过程中的关键环节，但大多数开源和工业环境中的Bug在报告时缺乏可执行测试，这使得诊断和解决更加困难和耗时。为了解决这一挑战，我们引入了AssertFlip，这是一种利用大型语言模型（LLMs）自动生成Bug复现测试（BRTs）的新技术。与现有方法试图直接生成失败测试不同，AssertFlip首先生成通过的测试，用于描述存在缺陷的行为，然后将这些测试反转，使其在缺陷存在时失败。我们假设LLMs更擅长编写通过的测试，而不是那些故意崩溃或失败的测试。我们的结果显示，AssertFlip在BRT基准测试SWT-Bench的排行榜上优于所有已知技术。具体而言，AssertFlip在SWT-Bench-Verified子集上实现了43.6%的失败到通过的成功率。

> Bug reproduction is critical in the software debugging and repair process, yet the majority of bugs in open-source and industrial settings lack executable tests to reproduce them at the time they are reported, making diagnosis and resolution more difficult and time-consuming. To address this challenge, we introduce AssertFlip, a novel technique for automatically generating Bug Reproducible Tests (BRTs) using large language models (LLMs). Unlike existing methods that attempt direct generation of failing tests, AssertFlip first generates passing tests on the buggy behaviour and then inverts these tests to fail when the bug is present. We hypothesize that LLMs are better at writing passing tests than ones that crash or fail on purpose. Our results show that AssertFlip outperforms all known techniques in the leaderboard of SWT-Bench, a benchmark curated for BRTs. Specifically, AssertFlip achieves a fail-to-pass success rate of 43.6% on the SWT-Bench-Verified subset.

[Arxiv](https://arxiv.org/abs/2507.17542)