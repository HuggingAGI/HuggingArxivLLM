# LibLMFuzz：LLM增强型黑盒库模糊测试目标生成工具

发布时间：2025年07月20日

`LLM应用` `网络安全` `软件工程`

> LibLMFuzz: LLM-Augmented Fuzz Target Generation for Black-box Libraries

# 摘要

> 在网络安全和计算机科学领域，一个核心问题是判断程序是否无漏洞和错误。模糊测试（fuzzing）作为一种流行的漏洞发现方法，相比其他策略具有显著优势，尽管需要投入初始设置和持续维护的成本。当面对仅提供二进制库的闭源或专有软件时，模糊测试的选择变得更加复杂。为此，我们推出LibLMFuzz框架，通过结合智能体大型语言模型（LLM）与轻量级工具链（反编译器/编译器/模糊测试器），实现对已剥离二进制文件的自主分析、模糊测试策略规划、驱动程序生成以及迭代式自我修复构建或运行时错误，从而显著降低对闭源库进行模糊测试的成本。在四个常用Linux库的测试中，LibLMFuzz成功为全部558个可模糊测试的API函数生成了语法正确的驱动程序，无需人工干预即可实现100%的API覆盖率。在1601个合成驱动程序中，75.52%在首次执行时表现良好。实验结果表明，LLM增强的中间件在降低黑盒组件模糊测试成本方面潜力巨大，并为未来研究奠定了基础。未来研究可进一步探索分支覆盖领域的机遇。

> A fundamental problem in cybersecurity and computer science is determining whether a program is free of bugs and vulnerabilities. Fuzzing, a popular approach to discovering vulnerabilities in programs, has several advantages over alternative strategies, although it has investment costs in the form of initial setup and continuous maintenance. The choice of fuzzing is further complicated when only a binary library is available, such as the case of closed-source and proprietary software. In response, we introduce LibLMFuzz, a framework that reduces costs associated with fuzzing closed-source libraries by pairing an agentic Large Language Model (LLM) with a lightweight tool-chain (disassembler/compiler/fuzzer) to autonomously analyze stripped binaries, plan fuzz strategies, generate drivers, and iteratively self-repair build or runtime errors. Tested on four widely-used Linux libraries, LibLMFuzz produced syntactically correct drivers for all 558 fuzz-able API functions, achieving 100% API coverage with no human intervention. Across the 1601 synthesized drivers, 75.52% were nominally correct on first execution. The results show that LLM-augmented middleware holds promise in reducing the costs of fuzzing black box components and provides a foundation for future research efforts. Future opportunities exist for research in branch coverage.

[Arxiv](https://arxiv.org/abs/2507.15058)