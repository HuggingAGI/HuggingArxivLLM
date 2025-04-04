# 借助工具化和程序状态对齐提升 LLM 在长代码翻译中的性能

发布时间：2025年04月02日

`LLM应用

论文摘要：代码翻译的目标是在不同编程语言间转换代码，同时确保功能一致，这在跨平台开发和软件迁移中非常有用。尽管大型语言模型（LLMs）在代码翻译方面取得了进展，但仍存在挑战，特别是在推断程序功能方面。随着代码长度和复杂度的增加，LLMs在处理长度和复杂语义时显得力不从心。

为了评估LLMs在长代码翻译中的表现，我们推出了LongTrans，这是一个基于执行的大规模基准测试，包含C++、Java和Python程序，代码长度从几百到几千个token不等。通过对12个LLMs的实证研究，我们发现，随着代码长度的增加，性能急剧下降，即使是最优秀的模型GPT-4o也只有57.51%的计算准确率。这凸显了对长代码翻译进一步研究的必要性。

我们认为，代码翻译应保持功能不变，同时转换语法和关键字。尽管外观不同，程序状态在整个执行过程中应保持一致。为了解决这个问题，我们提出了PAST（程序状态对齐增强翻译），它集成了工具来捕获和对齐翻译过程中的程序状态。这种方法首次利用LLMs在原始代码和翻译代码中插入工具，跟踪运行时的程序状态。通过提示LLM根据输出跟踪结果纠正错误，我们缓解了不一致并提高了翻译准确性。

实验结果显示了显著的提升，GPT-4o的计算准确率从57.51%提高到84.70%，Mistral-Large-2从50.68%提高到69.97%，DeepSeek-Coder-V2从52.45%提高到76.43%。这些改进在不同模型和数据集中都是一致的，消融研究证实了工具和状态对齐带来的好处。` `软件开发`

> Enhancing LLMs in Long Code Translation through Instrumentation and Program State Alignment

# 摘要

> 代码翻译的目标是在不同编程语言间转换代码，同时确保功能一致，这在跨平台开发和软件迁移中非常有用。尽管大型语言模型（LLMs）在代码翻译方面取得了进展，但仍存在挑战，特别是在推断程序功能方面。随着代码长度和复杂度的增加，LLMs在处理长度和复杂语义时显得力不从心。

为了评估LLMs在长代码翻译中的表现，我们推出了LongTrans，这是一个基于执行的大规模基准测试，包含C++、Java和Python程序，代码长度从几百到几千个token不等。通过对12个LLMs的实证研究，我们发现，随着代码长度的增加，性能急剧下降，即使是最优秀的模型GPT-4o也只有57.51%的计算准确率。这凸显了对长代码翻译进一步研究的必要性。

我们认为，代码翻译应保持功能不变，同时转换语法和关键字。尽管外观不同，程序状态在整个执行过程中应保持一致。为了解决这个问题，我们提出了PAST（程序状态对齐增强翻译），它集成了工具来捕获和对齐翻译过程中的程序状态。这种方法首次利用LLMs在原始代码和翻译代码中插入工具，跟踪运行时的程序状态。通过提示LLM根据输出跟踪结果纠正错误，我们缓解了不一致并提高了翻译准确性。

实验结果显示了显著的提升，GPT-4o的计算准确率从57.51%提高到84.70%，Mistral-Large-2从50.68%提高到69.97%，DeepSeek-Coder-V2从52.45%提高到76.43%。这些改进在不同模型和数据集中都是一致的，消融研究证实了工具和状态对齐带来的好处。

> Code translation aims to transform code between programming languages while preserving functionality, with applications in cross-platform development and software migration. Recent advances in Large Language Models (LLMs) have improved code translation, but challenges remain, particularly in inferring program functionality. These issues worsen with longer and more complex code, where current LLMs struggle to handle length and intricate semantics. To evaluate LLMs on long code translation, we introduce LongTrans, a large-scale execution-based benchmark with C++, Java, and Python programs, ranging from hundreds to thousands of tokens. Our empirical study of 12 LLMs reveals a sharp performance decline as code length increases, with even the best-performing model, GPT-4o, achieving only 57.51% computational accuracy. This highlights the need for further research in long code translation. We argue that code translation should maintain invariant functionality while transforming syntax and keywords across languages. Despite differences in appearance, program states should remain consistent throughout execution. To address this, we propose PAST (Program State Alignment augmented Translation), which integrates instrumentation to capture and align program states during translation. This approach is the first to leverage LLMs to insert instrumentation in both original and translated code, tracing program states at runtime. By prompting the LLM to correct errors based on output traces, we mitigate inconsistencies and enhance translation accuracy. Experimental results show significant improvements, with computational accuracy rising from 57.51% to 84.70% for GPT-4o, 50.68% to 69.97% for Mistral-Large-2, and 52.45% to 76.43% for DeepSeek-Coder-V2. These improvements are consistent across models and datasets, with ablation studies confirming the benefits of instrumentation and state alignment.

[Arxiv](https://arxiv.org/abs/2504.02017)