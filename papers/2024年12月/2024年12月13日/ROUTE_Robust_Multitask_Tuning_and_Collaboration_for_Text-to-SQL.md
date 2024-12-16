# ROUTE：针对文本到 SQL 的稳健多任务调优与协作

发布时间：2024年12月13日

`LLM应用` `数据库`

> ROUTE: Robust Multitask Tuning and Collaboration for Text-to-SQL

# 摘要

> 尽管大型语言模型（LLMs）推动了 Text-to-SQL（Text2SQL）的巨大进步，然而最新的顶尖技术仍受困于闭源 LLMs（如 GPT-4）的上下文学习，这限制了其在开放场景中的应用。为应对此挑战，我们提出了一种新颖的鲁棒多任务调整与协作方法（ROUTE），以提升开源 LLMs 在 Text2SQL 上的综合能力，进而提供更实用的解决方案。我们的方法始于使用与 SQL 生成相关的各类合成训练数据进行多任务监督微调（SFT）。与现有的基于 SFT 的 Text2SQL 方法不同，我们新增了若干 SFT 任务，如模式链接、噪声校正和续写。参与多种 SQL 生成任务增强了模型对 SQL 语法的理解，提升了其生成高质量 SQL 查询的能力。此外，受 LLM 代理协作模式的启发，我们引入了多任务协作提示（MCP）策略。该策略借助多个与 SQL 相关任务的协作来减少 SQL 生成时的幻觉，从而通过明确的多任务能力最大程度地挖掘提升 Text2SQL 性能的潜力。我们在八个开源 LLMs 和五个广泛使用的基准上开展了大量实验和深入分析。结果显示，我们的方案优于最新的 Text2SQL 方法，取得了领先的性能。

> Despite the significant advancements in Text-to-SQL (Text2SQL) facilitated by large language models (LLMs), the latest state-of-the-art techniques are still trapped in the in-context learning of closed-source LLMs (e.g., GPT-4), which limits their applicability in open scenarios. To address this challenge, we propose a novel RObust mUltitask Tuning and collaboration mEthod (ROUTE) to improve the comprehensive capabilities of open-source LLMs for Text2SQL, thereby providing a more practical solution. Our approach begins with multi-task supervised fine-tuning (SFT) using various synthetic training data related to SQL generation. Unlike existing SFT-based Text2SQL methods, we introduced several additional SFT tasks, including schema linking, noise correction, and continuation writing. Engaging in a variety of SQL generation tasks enhances the model's understanding of SQL syntax and improves its ability to generate high-quality SQL queries. Additionally, inspired by the collaborative modes of LLM agents, we introduce a Multitask Collaboration Prompting (MCP) strategy. This strategy leverages collaboration across several SQL-related tasks to reduce hallucinations during SQL generation, thereby maximizing the potential of enhancing Text2SQL performance through explicit multitask capabilities. Extensive experiments and in-depth analyses have been performed on eight open-source LLMs and five widely-used benchmarks. The results demonstrate that our proposal outperforms the latest Text2SQL methods and yields leading performance.

[Arxiv](https://arxiv.org/abs/2412.10138)