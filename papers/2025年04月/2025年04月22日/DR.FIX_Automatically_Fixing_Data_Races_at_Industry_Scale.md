# DR.FIX：在工业级规模下自动修复数据竞争问题

发布时间：2025年04月22日

`LLM应用` `软件工程`

> DR.FIX: Automatically Fixing Data Races at Industry Scale

# 摘要

> 数据竞争是共享内存并行程序中一类常见的并发错误，对软件可靠性和可重复性构成重大挑战。尽管检测数据竞争的研究和工具层出不穷，但针对工业规模的自动修复却鲜有投入。在大型代码库中，数据竞争不断被引入，并呈现出多种多样的模式，这使得自动修复变得尤为困难。

在本文中，我们提出了Dr.Fix，一款结合大型语言模型（LLMs）与程序分析的工具，旨在为现实场景中的数据竞争生成修复方案。Dr.Fix针对Go编程语言实现，该语言在现代微服务架构中广泛应用，其中并发无处不在且数据竞争常见。Dr.Fix无缝集成到现有的开发工作流程中。我们详细介绍了Dr.Fix的设计，并探讨了各设计选择如何影响生成修复的质量。

在过去18个月中，Dr.Fix已集成到优步的开发者工作流中，证明了其实际效用。在此期间，Dr.Fix为涵盖各类别的404个数据竞争案例中的224个（占比55%）生成了补丁；其中193个补丁（占比86%）通过了超过百名开发者的代码审查并集成到代码库中。


> Data races are a prevalent class of concurrency bugs in shared-memory parallel programs, posing significant challenges to software reliability and reproducibility. While there is an extensive body of research on detecting data races and a wealth of practical detection tools across various programming languages, considerably less effort has been directed toward automatically fixing data races at an industrial scale. In large codebases, data races are continuously introduced and exhibit myriad patterns, making automated fixing particularly challenging.
  In this paper, we tackle the problem of automatically fixing data races at an industrial scale. We present Dr.Fix, a tool that combines large language models (LLMs) with program analysis to generate fixes for data races in real-world settings, effectively addressing a broad spectrum of racy patterns in complex code contexts. Implemented for Go--the programming language widely used in modern microservice architectures where concurrency is pervasive and data races are common--Dr.Fix seamlessly integrates into existing development workflows. We detail the design of Dr.Fix and examine how individual design choices influence the quality of the fixes produced. Over the past 18 months, Dr.Fix has been integrated into developer workflows at Uber demonstrating its practical utility. During this period, Dr.Fix produced patches for 224 (55%) from a corpus of 404 data races spanning various categories; 193 of these patches (86%) were accepted by more than a hundred developers via code reviews and integrated into the codebase.

[Arxiv](https://arxiv.org/abs/2504.15637)