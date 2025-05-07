# UCSC在SemEval-2025任务3中的研究：上下文、模型与提示优化，实现LLM输出中的自动幻觉检测

发布时间：2025年05月05日

`LLM应用

理由：这篇论文主要探讨了如何检测和定位大型语言模型中的幻觉问题，属于模型的应用层面，旨在解决实际任务中的问题。` `多语言处理`

> UCSC at SemEval-2025 Task 3: Context, Models and Prompt Optimization for Automated Hallucination Detection in LLM Output

# 摘要

> 幻觉问题是大型语言模型在处理知识密集型查询时面临的一大挑战。随着LLMs应用日益广泛，我们不仅要能够检测到幻觉的存在，更要精准定位其在LLM输出中的具体位置。SemEval 2025任务3——Mu-SHROOM：多语言幻觉及相关可观察过度生成错误共享任务，正是为了解决这一问题而设立的。本文介绍了我们提交给Mu-SHROOM共享任务的UCSC系统。我们的框架通过三步实现：首先检索相关上下文，接着从答案中识别虚假内容，最后将它们定位到LLM输出的具体片段。通过自动优化提示语，这一流程得到了进一步增强。我们的系统在所有语言中均表现优异，平均位置排名第一。我们已公开发布代码和实验结果。


> Hallucinations pose a significant challenge for large language models when answering knowledge-intensive queries. As LLMs become more widely adopted, it is crucial not only to detect if hallucinations occur but also to pinpoint exactly where in the LLM output they occur. SemEval 2025 Task 3, Mu-SHROOM: Multilingual Shared-task on Hallucinations and Related Observable Overgeneration Mistakes, is a recent effort in this direction. This paper describes the UCSC system submission to the shared Mu-SHROOM task. We introduce a framework that first retrieves relevant context, next identifies false content from the answer, and finally maps them back to spans in the LLM output. The process is further enhanced by automatically optimizing prompts. Our system achieves the highest overall performance, ranking #1 in average position across all languages. We release our code and experiment results.

[Arxiv](https://arxiv.org/abs/2505.03030)