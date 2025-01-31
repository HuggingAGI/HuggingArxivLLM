# 基于突变生成堆栈跟踪的微调大型语言模型实现故障定位

发布时间：2025年01月29日

`LLM应用

**理由**：这篇论文主要讨论了如何通过微调大型语言模型（LLMs）来定位软件崩溃的根本原因。虽然涉及到LLM的微调，但其核心应用场景是解决软件崩溃分析的问题，属于LLM在实际问题中的应用，因此归类为LLM应用。` `软件工程` `故障诊断`

> Fault Localization via Fine-tuning Large Language Models with Mutation Generated Stack Traces

# 摘要

> # 摘要
软件崩溃指的是软件的突然和意外终止，分析起来颇具挑战。要找到根本原因，通常需要大量手动工作和专业知识，以整合堆栈跟踪、源代码和日志等信息源。传统的故障定位方法依赖于测试失败或源代码，而像SAP HANA这样的生产环境崩溃仅提供崩溃日志和堆栈跟踪。我们提出了一种创新方法，仅基于堆栈跟踪信息，通过微调大型语言模型（LLMs）来定位故障，无需额外的运行时信息。我们解决了复杂情况，即崩溃的根本原因与技术原因不同，且不位于堆栈跟踪的最内层帧。由于历史崩溃数据不足以微调LLMs，我们利用代码变异器将合成崩溃注入代码库，扩充了数据集。通过对HANA代码库的410万次变异产生的64,369次崩溃进行微调，我们能够以66.9%的准确率预测崩溃的根本原因位置，而基线方法仅达到12.6%和10.6%。我们还在两个开源数据库SQLite和DuckDB上进行了评估，分别取得了63%和74%的准确率，验证了该方法的通用性。在所有实验中，微调LLMs在定位数据集中的故障方面始终优于未微调的LLMs。

> Abrupt and unexpected terminations of software are termed as software crashes. They can be challenging to analyze. Finding the root cause requires extensive manual effort and expertise to connect information sources like stack traces, source code, and logs. Typical approaches to fault localization require either test failures or source code. Crashes occurring in production environments, such as that of SAP HANA, provide solely crash logs and stack traces. We present a novel approach to localize faults based only on the stack trace information and no additional runtime information, by fine-tuning large language models (LLMs). We address complex cases where the root cause of a crash differs from the technical cause, and is not located in the innermost frame of the stack trace. As the number of historic crashes is insufficient to fine-tune LLMs, we augment our dataset by leveraging code mutators to inject synthetic crashes into the code base. By fine-tuning on 64,369 crashes resulting from 4.1 million mutations of the HANA code base, we can correctly predict the root cause location of a crash with an accuracy of 66.9\% while baselines only achieve 12.6% and 10.6%. We substantiate the generalizability of our approach by evaluating on two additional open-source databases, SQLite and DuckDB, achieving accuracies of 63% and 74%, respectively. Across all our experiments, fine-tuning consistently outperformed prompting non-finetuned LLMs for localizing faults in our datasets.

[Arxiv](https://arxiv.org/abs/2501.18005)