# 高效编译算法为紧凑线性程序

发布时间：2025年09月16日

`其他` `工业与制造`

> Efficient Compilation of Algorithms into Compact Linear Programs

# 摘要

> 线性规划（LP）在工业领域应用广泛，也是多种数学问题求解技术的核心组成部分。近期研究提出了一种LP编译器，能够利用直观的高级编程语言，将多项式时间、多项式空间算法转化为多项式规模的LP，为通过代数建模语言（AMLs）手动定义每组约束提供了极具潜力的替代方案。然而，尽管生成的LP规模为多项式级别，但其尺寸往往异常庞大，给现有LP求解器带来了难题。本文提出了一种从算法生成更小LP的创新方法。我们的目标是为P类问题构建最小尺寸的紧凑LP模型——这类问题的自然模型具有指数级扩展复杂度。我们更宏大的愿景是：针对具有指数规模整数规划（IP）且存在多项式时间分离预言机的问题，实现紧凑整数规划（CIP）模型的系统化构建。为此，我们提出了分层线性流水线技术，该技术能将嵌套程序结构分解为同步区域，每个区域都配有明确定义的执行转换——即编译时参数的函数。这种分解可将LP约束与变量限定在各区域内，在保证通用性的同时大幅缩减LP规模，确保生成的LP对所有规模为【数学公式】的输入均有效。我们在两个基准问题上验证了该方法的有效性：一是具有指数扩展复杂度的完工时间问题，二是加权最小生成树问题，这两个问题的自然LP模型均为指数规模。结果表明，LP规模缩减高达【数学公式】倍，且商业与非商业LP求解器的性能均得到显著改善。

> Linear Programming (LP) is widely applied in industry and is a key component of various other mathematical problem-solving techniques. Recent work introduced an LP compiler translating polynomial-time, polynomial-space algorithms into polynomial-size LPs using intuitive high-level programming languages, offering a promising alternative to manually specifying each set of constraints through Algebraic Modeling Languages (AMLs). However, the resulting LPs, while polynomial in size, are often extremely large, posing challenges for existing LP solvers. In this paper, we propose a novel approach for generating substantially smaller LPs from algorithms. Our goal is to establish minimum-size compact LP formulations for problems in P having natural formulations with exponential extension complexities. Our broader vision is to enable the systematic generation of Compact Integer Programming (CIP) formulations for problems with exponential-size IPs having polynomial-time separation oracles. To this end, we introduce a hierarchical linear pipelining technique that decomposes nested program structures into synchronized regions with well-defined execution transitions -- functions of compile-time parameters. This decomposition allows us to localize LP constraints and variables within each region, significantly reducing LP size without the loss of generality, ensuring the resulting LP remains valid for all inputs of size $n$. We demonstrate the effectiveness of our method on two benchmark problems -- the makespan problem, which has exponential extension complexity, and the weighted minimum spanning tree problem -- both of which have exponential-size natural LPs. Our results show up to a $25$-fold reduction in LP size and substantial improvements in solver performance across both commercial and non-commercial LP solvers.

[Arxiv](https://arxiv.org/abs/2509.13006)