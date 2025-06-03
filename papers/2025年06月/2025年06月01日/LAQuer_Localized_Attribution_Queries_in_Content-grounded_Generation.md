# LAQuer: 内容导向生成中的局部归因查询

发布时间：2025年06月01日

`LLM应用

理由：这篇论文主要探讨了如何通过大型语言模型（LLMs）来改进内容归因任务，特别是在局部归因查询（LAQuer）任务中的应用。它提出了新的方法和框架，并在具体任务中进行了评估，属于LLM的应用层面。` `多文档摘要` `长形式问答`

> LAQuer: Localized Attribution Queries in Content-grounded Generation

# 摘要

> 基于文本生成模型常会产生与源材料偏离的内容，需要用户验证以确保准确性。现有归因方法将整个句子与源文档关联，这对希望验证特定声明的用户来说过于繁琐。相比之下，现有子句子归因方法虽更精确，但未能与用户兴趣对齐。为解决这些限制，我们提出局部归因查询（LAQuer）任务，旨在将生成输出片段定位到其对应源片段，实现细致且用户导向的归因。我们比较了LAQuer任务的两种方法：提示大型语言模型（LLMs）和利用LLM内部表示。随后，我们探讨了一个建模框架，将现有带归因文本生成方法扩展到LAQuer。我们在多文档摘要（MDS）和长形式问答（LFQA）两个任务上评估了该框架。研究发现，LAQuer方法显著减少了归因文本长度。我们的贡献包括：（1）提出LAQuer任务以增强归因实用性，（2）提出建模框架并基准测试多个基线，（3）提出新评估设置以促进未来在内容归因生成中的局部归因研究。

> Grounded text generation models often produce content that deviates from their source material, requiring user verification to ensure accuracy. Existing attribution methods associate entire sentences with source documents, which can be overwhelming for users seeking to fact-check specific claims. In contrast, existing sub-sentence attribution methods may be more precise but fail to align with users' interests. In light of these limitations, we introduce Localized Attribution Queries (LAQuer), a new task that localizes selected spans of generated output to their corresponding source spans, allowing fine-grained and user-directed attribution. We compare two approaches for the LAQuer task, including prompting large language models (LLMs) and leveraging LLM internal representations. We then explore a modeling framework that extends existing attributed text generation methods to LAQuer. We evaluate this framework across two grounded text generation tasks: Multi-document Summarization (MDS) and Long-form Question Answering (LFQA). Our findings show that LAQuer methods significantly reduce the length of the attributed text. Our contributions include: (1) proposing the LAQuer task to enhance attribution usability, (2) suggesting a modeling framework and benchmarking multiple baselines, and (3) proposing a new evaluation setting to promote future research on localized attribution in content-grounded generation.

[Arxiv](https://arxiv.org/abs/2506.01187)