# SABER：借助跨层残差连接揭示安全对齐漏洞

发布时间：2025年09月19日

`LLM应用` `基础理论`

> SABER: Uncovering Vulnerabilities in Safety Alignment via Cross-Layer Residual Connection

# 摘要

> 经过安全对齐训练的大型语言模型（LLMs）是具备强大语言理解能力的得力工具。这类模型通常需经过结合人类反馈的精细对齐流程，确保接收安全输入的同时拒绝有害或不安全内容。然而，尽管规模庞大且对齐工作投入巨大，LLMs仍难逃越狱攻击——恶意用户借此操纵模型，生成其本应规避的有害输出。本研究发现，LLMs的安全机制主要嵌入在中后层网络中。基于此发现，我们提出一种全新的白盒越狱方法SABER（全称Safety Alignment Bypass via Extra Residuals，即通过额外残差绕过安全对齐），其通过残差连接将两个中间层【数学公式】与【数学公式】相连（满足【数学公式】）。在HarmBench测试集上，该方法较现有最优基线提升了51%的性能。此外，在HarmBench验证集上的评估显示，SABER对困惑度的影响微乎其微。源代码已公开，地址为https://github.com/PalGitts/SABER。

> Large Language Models (LLMs) with safe-alignment training are powerful instruments with robust language comprehension capabilities. These models typically undergo meticulous alignment procedures involving human feedback to ensure the acceptance of safe inputs while rejecting harmful or unsafe ones. However, despite their massive scale and alignment efforts, LLMs remain vulnerable to jailbreak attacks, where malicious users manipulate the model to produce harmful outputs that it was explicitly trained to avoid. In this study, we find that the safety mechanisms in LLMs are predominantly embedded in the middle-to-late layers. Building on this insight, we introduce a novel white-box jailbreak method, SABER (Safety Alignment Bypass via Extra Residuals), which connects two intermediate layers $s$ and $e$ such that $s < e$, through a residual connection. Our approach achieves a 51% improvement over the best-performing baseline on the HarmBench test set. Furthermore, SABER induces only a marginal shift in perplexity when evaluated on the HarmBench validation set. The source code is publicly available at https://github.com/PalGitts/SABER.

[Arxiv](https://arxiv.org/abs/2509.16060)