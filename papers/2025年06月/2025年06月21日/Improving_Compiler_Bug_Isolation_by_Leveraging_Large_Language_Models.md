# 提升编译器错误定位效率：借助大型语言模型的研究

发布时间：2025年06月21日

`LLM应用` `软件工程` `缺陷定位`

> Improving Compiler Bug Isolation by Leveraging Large Language Models

# 摘要

> 编译器是构建可靠软件系统的核心，其中的缺陷可能引发严重后果。由于编译过程涉及数百个文件，传统自动化缺陷隔离技术难以应对。现有编译器缺陷定位技术在测试程序变异和资源消耗方面存在局限。基于大型语言模型（LLMs）的最新进展，我们提出了名为AutoCBI的创新方法，通过（1）利用LLMs总结编译器文件功能，（2）借助专用提示重新排序可疑文件，实现更高效的缺陷定位。该方法整合了失败测试程序、功能摘要、可疑文件列表和编译配置等信息，生成优化后的可疑文件排名。在GCC和LLVM编译器上的120个真实缺陷测试中，AutoCBI的表现显著优于现有方法：在Top-1结果中，其缺陷隔离数量分别比RecBi、DiWi和FuseFL高出66.67%/69.23%、300%/340%和100%/57.14%。消融实验进一步证实了各组件的重要性。

> Compilers play a foundational role in building reliable software systems, and bugs within them can lead to catastrophic consequences. The compilation process typically involves hundreds of files, making traditional automated bug isolation techniques inapplicable due to scalability or effectiveness issues. Current mainstream compiler bug localization techniques have limitations in test program mutation and resource consumption. Inspired by the recent advances of pre-trained Large Language Models (LLMs), we propose an innovative approach named AutoCBI, which (1) uses LLMs to summarize compiler file functions and (2) employs specialized prompts to guide LLM in reordering suspicious file rankings. This approach leverages four types of information: the failing test program, source file function summaries, lists of suspicious files identified through analyzing test coverage, as well as compilation configurations with related output messages, resulting in a refined ranking of suspicious files. Our evaluation of AutoCBI against state-of-the-art approaches (DiWi, RecBi and FuseFL) on 120 real-world bugs from the widely-used GCC and LLVM compilers demonstrates its effectiveness. Specifically, AutoCBI isolates 66.67%/69.23%, 300%/340%, and 100%/57.14% more bugs than RecBi, DiWi, and FuseFL, respectively, in the Top-1 ranked results for GCC/LLVM. Additionally, the ablation study underscores the significance of each component in our approach.

[Arxiv](https://arxiv.org/abs/2506.17647)