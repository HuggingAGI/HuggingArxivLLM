# Fortran2CPP: 利用LLMs通过多轮对话和双代理集成实现Fortran到C++的自动化迁移

发布时间：2024年12月27日

`LLM应用

理由：这篇论文主要讨论了如何利用大型语言模型（LLMs）来自动化 Fortran 代码迁移到 C++ 的过程，并介绍了为此设计的多轮对话数据集 Fortran2CPP。论文的核心在于应用 LLMs 来解决具体的代码迁移问题，并通过微调模型来提升迁移效果。因此，这篇论文属于 LLM 应用的范畴。` `科学计算` `代码迁移`

> Fortran2CPP: Automating Fortran-to-C++ Migration using LLMs via Multi-Turn Dialogue and Dual-Agent Integration

# 摘要

> # 摘要
将 Fortran 代码迁移到 C++ 是科学计算领域的常见需求，旨在利用现代编程范式、提升跨平台兼容性和代码可维护性。尽管使用大型语言模型（LLMs）自动化这一过程颇具潜力，但高质量、专业化数据集的匮乏限制了其效果。为此，我们推出了一个专为 Fortran 到 C++ 代码迁移设计的多轮对话数据集 Fortran2CPP。该数据集规模远超现有方案，采用独特的 LLM 驱动双代理管道生成，结合迭代编译、执行和代码修复，确保高质量与功能正确性。我们在 Fortran2CPP 上微调了多个开源 LLMs，并在两个独立基准上评估其性能。结果显示，微调后模型在 CodeBLEU 分数上提升高达 3.31 倍，编译成功率提升 92%，显著提升了翻译后 C++ 代码的语法准确性和可编译性。数据集与模型已开源，详见 GitHub 仓库ootnote{url{https://github.com/HPC-Fortran2CPP/Fortran2Cpp}}。

> Migrating Fortran code to C++ is a common task for many scientific computing teams, driven by the need to leverage modern programming paradigms, enhance cross-platform compatibility, and improve maintainability. Automating this translation process using large language models (LLMs) has shown promise, but the lack of high-quality, specialized datasets has hindered their effectiveness. In this paper, we address this challenge by introducing a novel multi-turn dialogue dataset, Fortran2CPP, specifically designed for Fortran-to-C++ code migration. Our dataset, significantly larger than existing alternatives, is generated using a unique LLM-driven, dual-agent pipeline incorporating iterative compilation, execution, and code repair to ensure high quality and functional correctness. To demonstrate the effectiveness of our dataset, we fine-tuned several open-weight LLMs on Fortran2CPP and evaluated their performance on two independent benchmarks. Fine-tuning on our dataset led to remarkable gains, with models achieving up to a 3.31x increase in CodeBLEU score and a 92\% improvement in compilation success rate. This highlights the dataset's ability to enhance both the syntactic accuracy and compilability of the translated C++ code. Our dataset and model have been open-sourced and are available on our public GitHub repository\footnote{\url{https://github.com/HPC-Fortran2CPP/Fortran2Cpp}}.

[Arxiv](https://arxiv.org/abs/2412.19770)