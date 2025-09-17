# 利用大型语言模型驱动的符号执行与具体执行验证Solidity代码缺陷

发布时间：2025年09月16日

`LLM应用` `金融科技`

> Validating Solidity Code Defects using Symbolic and Concrete Execution powered by Large Language Models

# 摘要

> 静态分析工具与大型语言模型（LLMs）的高误报率给Solidity智能合约的漏洞检测带来了挑战，因此亟需能够形式化或实证证明缺陷存在的方法。本文提出了一种新颖的检测流程，整合了基于Slither的自定义检测器、LLMs、Kontrol和Forge工具。该方法旨在可靠检测缺陷并生成证明，目前已针对七种关键缺陷类型开展实验，结果令人鼓舞。为验证流程的有效性，我们重点展示了三种漏洞的研究发现——重入漏洞（Reentrancy）、复杂回退漏洞（Complex Fallback）和错误访问控制策略漏洞（Faulty Access Control Policies），这些漏洞是当前验证方案的难点，常导致误报或漏检。我们还指出，符号执行或具体执行在正确分类此类代码故障方面具有巨大潜力。通过将这些工具链结合，我们的方法能有效验证真阳性，大幅减轻人工验证负担。尽管存在LLM的不一致性和成本等潜在限制，但研究结果仍构建了一个强大框架，将启发式分析与形式化验证相结合，实现了更可靠的自动化智能合约审计。

> The high rate of false alarms from static analysis tools and Large Language Models (LLMs) complicates vulnerability detection in Solidity Smart Contracts, demanding methods that can formally or empirically prove the presence of defects. This paper introduces a novel detection pipeline that integrates custom Slither-based detectors, LLMs, Kontrol, and Forge. Our approach is designed to reliably detect defects and generate proofs.  We currently perform experiments with promising results for seven types of critical defects. We demonstrate the pipeline's efficacy by presenting our findings for three vulnerabilities -- Reentrancy, Complex Fallback, and Faulty Access Control Policies -- that are challenging for current verification solutions, which often generate false alarms or fail to detect them entirely. We highlight the potential of either symbolic or concrete execution in correctly classifying such code faults. By chaining these instruments, our method effectively validates true positives, significantly reducing the manual verification burden. Although we identify potential limitations, such as the inconsistency and the cost of LLMs, our findings establish a robust framework for combining heuristic analysis with formal verification to achieve more reliable and automated smart contract auditing.

[Arxiv](https://arxiv.org/abs/2509.13023)