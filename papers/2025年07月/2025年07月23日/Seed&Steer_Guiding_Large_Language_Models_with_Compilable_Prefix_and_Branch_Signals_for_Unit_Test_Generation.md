# Seed&Steer：利用可编译前缀与分支信号引导大型语言模型生成单元测试

发布时间：2025年07月23日

`LLM应用

摘要中提到，论文探讨了基于大型语言模型（LLM）的自动化测试生成技术，并提出了一种结合传统单元测试技术和LLM能力的方法。这表明论文关注的是LLM在特定应用领域的实际应用，因此归类为LLM应用。` `软件开发` `自动化测试`

> Seed&Steer: Guiding Large Language Models with Compilable Prefix and Branch Signals for Unit Test Generation

# 摘要

> 单元测试在软件开发中至关重要。近期基于大型语言模型（LLM）的自动化测试生成技术取得了显著进展，受到学术界和工业界的广泛关注。我们从全新角度重新审视基于LLM的单元测试生成，通过分离前缀生成和断言生成来解决各自的技术挑战。我们定义了初始化复杂度，并采用环形复杂度来衡量前缀和断言生成的难度，发现前者主要影响编译成功率，而后者则影响测试覆盖率。为应对这些挑战，我们提出了Seed&Steer——一种结合传统单元测试技术和LLM能力的两步方法。Seed&Steer利用传统工具（如EvoSuite）生成高成功率的方法调用作为种子，引导LLMs构建有效测试上下文。随后，它引入分支提示帮助LLMs探索多样化执行路径（如正常、边界和异常情况），并生成高覆盖率的断言。我们在五个真实Java项目上将Seed&Steer与最新基线方法进行了对比评估。结果显示，Seed&Steer将编译通过率提升了约7%，在两个LLMs上成功编译了792和887个先前失败的案例。它在各种复杂度的焦点方法上实现了高达~73%的分支和行覆盖率，覆盖率提升幅度从1.09倍到1.26倍。我们的代码、数据集和实验脚本将公开发布，以支持未来的研究和可重复性。

> Unit tests play a vital role in the software development lifecycle. Recent advances in Large Language Model (LLM)-based approaches have significantly improved automated test generation, garnering attention from both academia and industry. We revisit LLM-based unit test generation from a novel perspective by decoupling prefix generation and assertion generation. To characterize their respective challenges, we define Initialization Complexity and adopt Cyclomatic Complexity to measure the difficulty of prefix and assertion generation, revealing that the former primarily affects compilation success, while the latter influences test coverage. To address these challenges, we propose Seed&Steer, a two-step approach that combines traditional unit testing techniques with the capabilities of large language models. Seed&Steer leverages conventional unit testing tools (e.g., EvoSuite) to generate method invocations with high compilation success rates, which serve as seeds to guide LLMs in constructing effective test contexts. It then introduces branching cues to help LLMs explore diverse execution paths (e.g., normal, boundary, and exception cases) and generate assertions with high coverage. We evaluate Seed&Steer on five real-world Java projects against state-of-the-art baselines. Results show that Seed&Steer improves the compilation pass rate by approximately 7%, successfully compiling 792 and 887 previously failing cases on two LLMs. It also achieves up to ~73% branch and line coverage across focal methods of varying complexity, with coverage improvements ranging from 1.09* to 1.26*. Our code, dataset, and experimental scripts will be publicly released to support future research and reproducibility.

[Arxiv](https://arxiv.org/abs/2507.17271)