# 大型语言模型助力的混合模糊测试

发布时间：2024年12月20日

`LLM应用` `软件测试` `程序漏洞检测`

> Large Language Model assisted Hybrid Fuzzing

# 摘要

> Greybox 模糊测试是检测软件漏洞的热门方法之一，它会在程序输入空间内进行有偏向的随机搜索。为增强其实现程序行为深度覆盖的效果，Greybox 模糊测试常与具体执行相结合，后者会在程序输入域进行路径敏感搜索。在混合模糊测试中，传统的 Greybox 模糊测试之后是迭代循环中的具体执行，Greybox 模糊测试遇到的可达性障碍由具体执行来解决。不过，这种混合模糊测试仍存在符号执行常面临的难题，比如需要环境建模和系统调用支持。在本研究中，我们展示了如何在无需计算和求解符号路径约束的情况下达成具体执行的效果。当基于覆盖的 Greybox 模糊测试在抵达某些分支时遇阻，我们会对执行跟踪进行切片，并建议修改输入以抵达相关分支。一个大型语言模型（LLM）被用作求解器，生成用于抵达所需分支的修改输入。与普通的 Greybox 模糊测试器 AFL 以及混合模糊测试器 Intriguer 和 Qsym 相比，我们基于 LLM 的混合模糊测试器 HyLLfuzz（读音为“hill fuzz”）展现出更优的覆盖率。此外，HyLLfuzz 中基于 LLM 的具体执行所用时间比现有混合模糊测试工具中的具体执行快 4 至 19 倍。这一经验表明，LLM 能够有效地嵌入混合模糊测试器的迭代循环，从而高效地揭示更多程序行为。

> Greybox fuzzing is one of the most popular methods for detecting software vulnerabilities, which conducts a biased random search within the program input space. To enhance its effectiveness in achieving deep coverage of program behaviors, greybox fuzzing is often combined with concolic execution, which performs a path-sensitive search over the domain of program inputs. In hybrid fuzzing, conventional greybox fuzzing is followed by concolic execution in an iterative loop, where reachability roadblocks encountered by greybox fuzzing are tackled by concolic execution. However, such hybrid fuzzing still suffers from difficulties conventionally faced by symbolic execution, such as the need for environment modeling and system call support. In this work, we show how to achieve the effect of concolic execution without having to compute and solve symbolic path constraints. When coverage-based greybox fuzzing reaches a roadblock in terms of reaching certain branches, we conduct a slicing on the execution trace and suggest modifications of the input to reach the relevant branches. A Large Language Model (LLM) is used as a solver to generate the modified input for reaching the desired branches. Compared with both the vanilla greybox fuzzer AFL and hybrid fuzzers Intriguer and Qsym, our LLM-based hybrid fuzzer HyLLfuzz (pronounced "hill fuzz") demonstrates superior coverage. Furthermore, the LLM-based concolic execution in HyLLfuzz takes a time that is 4-19 times faster than the concolic execution running in existing hybrid fuzzing tools. This experience shows that LLMs can be effectively inserted into the iterative loop of hybrid fuzzers, to efficiently expose more program behaviors.

[Arxiv](https://arxiv.org/abs/2412.15931)