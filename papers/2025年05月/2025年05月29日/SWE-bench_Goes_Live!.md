# SWE-bench 正式发布啦！

发布时间：2025年05月29日

`LLM应用` `软件工程` `基准测试`

> SWE-bench Goes Live!

# 摘要

> 修复真实世界漏洞的任务，已成为评估大型语言模型（LLMs）能力的关键基准。尽管SWE-bench及其变体在此领域已成为标准，但它们存在关键局限性：自初始发布以来从未更新，涵盖的存储库范围狭窄，且在实例构建和环境设置上严重依赖手动工作。这些因素阻碍了扩展性，并引入了过拟合和数据污染的风险。在此工作中，我们介绍了	extbf{SWE-bench-Live}，一个	extit{实时可更新}的基准测试，旨在克服这些挑战。我们的初始版本包含1,319项任务，这些任务源自2024年以来在GitHub上创建的真实问题，涵盖93个存储库。每个任务都附带一个专用的Docker镜像，以确保可重复执行。我们的基准测试的核心是\method，一个自动化的整理管道，从实例创建到环境设置，整个流程都得到了简化，消除了手动瓶颈，从而实现了扩展性和持续更新。我们在SWE-bench-Live上评估了一系列最先进的代理框架和LLMs，发现与静态基准如SWE-bench相比，即使在受控的评估条件下，性能差距仍然显著。为了更好地理解这种差异，我们从存储库来源、问题的时效性和任务难度等多个方面进行了详细分析。通过提供一个基于实时存储库活动的新颖、多样且可执行的基准测试，SWE-bench-Live促进了在动态真实世界软件开发环境中对LLMs和代理的严格、抗污染的评估。

> The issue-resolving task, where a model generates patches to fix real-world bugs, has emerged as a critical benchmark for evaluating the capabilities of large language models (LLMs). While SWE-bench and its variants have become standard in this domain, they suffer from key limitations: they have not been updated since their initial releases, cover a narrow set of repositories, and depend heavily on manual effort for instance construction and environment setup. These factors hinder scalability and introduce risks of overfitting and data contamination. In this work, we present \textbf{SWE-bench-Live}, a \textit{live-updatable} benchmark designed to overcome these challenges. Our initial release consists of 1,319 tasks derived from real GitHub issues created since 2024, spanning 93 repositories. Each task is accompanied by a dedicated Docker image to ensure reproducible execution. Central to our benchmark is \method, an automated curation pipeline that streamlines the entire process from instance creation to environment setup, removing manual bottlenecks and enabling scalability and continuous updates. We evaluate a range of state-of-the-art agent frameworks and LLMs on SWE-bench-Live, revealing a substantial performance gap compared to static benchmarks like SWE-bench, even under controlled evaluation conditions. To better understand this discrepancy, we perform detailed analyses across repository origin, issue recency, and task difficulty. By providing a fresh, diverse, and executable benchmark grounded in live repository activity, SWE-bench-Live facilitates rigorous, contamination-resistant evaluation of LLMs and agents in dynamic, real-world software development settings.

[Arxiv](https://arxiv.org/abs/2505.23419)