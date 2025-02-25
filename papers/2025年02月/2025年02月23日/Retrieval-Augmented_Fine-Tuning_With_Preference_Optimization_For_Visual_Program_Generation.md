# 检索增强微调与偏好优化融合的视觉程序生成方法

发布时间：2025年02月23日

`LLM应用` `工业自动化` `编程语言`

> Retrieval-Augmented Fine-Tuning With Preference Optimization For Visual Program Generation

# 摘要

> 视觉编程语言（VPLs）让用户通过图形界面轻松编写程序，因其易用性而被广泛应用在多个领域。为了进一步提升这种易用性，最近的研究致力于利用大型语言模型（LLMs）根据用户指令生成VPL代码。特别是通过采用基于提示的方法，这些研究已经取得了令人鼓舞的结果。然而，此类方法在工业VPL（如梯形图（LD））中可能效果不佳。作为工业自动化中的核心语言，LD涉及大量特定于领域的配置，这些配置难以通过单一提示捕获。在本研究中，我们证明了即使使用较小规模的基础模型，基于训练的方法在LD生成准确性上也优于基于提示的方法。在此基础上，我们提出了一种两阶段训练策略，以进一步提升VPL生成效果。首先，我们采用检索增强微调，利用工业VPL中常见子例程的重复使用。其次，我们通过系统生成的偏好对，运用图编辑操作，实施直接偏好优化（DPO），以进一步引导模型输出准确结果。在真实世界LD数据上的广泛实验表明，与监督微调相比，我们的方法在程序级准确率上提高了10%以上，这凸显了其在推动工业自动化方面的重要潜力。

> Visual programming languages (VPLs) allow users to create programs through graphical interfaces, which results in easier accessibility and their widespread usage in various domains. To further enhance this accessibility, recent research has focused on generating VPL code from user instructions using large language models (LLMs). Specifically, by employing prompting-based methods, these studies have shown promising results. Nevertheless, such approaches can be less effective for industrial VPLs such as Ladder Diagram (LD). LD is a pivotal language used in industrial automation processes and involves extensive domain-specific configurations, which are difficult to capture in a single prompt. In this work, we demonstrate that training-based methods outperform prompting-based methods for LD generation accuracy, even with smaller backbone models. Building on these findings, we propose a two-stage training strategy to further enhance VPL generation. First, we employ retrieval-augmented fine-tuning to leverage the repetitive use of subroutines commonly seen in industrial VPLs. Second, we apply direct preference optimization (DPO) to further guide the model toward accurate outputs, using systematically generated preference pairs through graph editing operations. Extensive experiments on real-world LD data demonstrate that our approach improves program-level accuracy by over 10% compared to supervised fine-tuning, which highlights its potential to advance industrial automation.

[Arxiv](https://arxiv.org/abs/2502.16529)