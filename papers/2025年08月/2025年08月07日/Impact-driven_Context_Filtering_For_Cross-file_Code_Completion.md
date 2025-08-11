# 影响驱动型跨文件代码补全上下文过滤方法

发布时间：2025年08月07日

`RAG` `软件开发` `代码补全`

> Impact-driven Context Filtering For Cross-file Code Completion

# 摘要

> 检索增强生成（RAG）在代码库级别的代码补全中展现出巨大潜力，通过整合跨文件知识与文件内部代码，提供全面生成上下文。为深入理解跨文件上下文的作用，我们引入基于似然度的指标评估每个检索代码块对补全的影响。分析发现，尽管检索了大量代码块，但仅少数对补全有积极贡献，部分甚至损害性能。为解决此问题，我们利用该指标构建了一个代码库级别的数据集，根据相关性将代码块标记为正面、中性或负面。随后，我们提出了自适应检索上下文过滤框架CODEFILTER，通过训练该数据集，有效缓解负面上下文对代码补全的负面影响。在RepoEval和CrossCodeLongEval基准测试中，CODEFILTER在各类任务中均显著提升补全准确性，同时大幅减少输入提示长度，提高计算效率，并在不同模型间展现出强大泛化能力。这些结果凸显了CODEFILTER在提升代码库级别代码补全准确性、效率和可归因性方面的潜力。

> Retrieval-augmented generation (RAG) has recently demonstrated considerable potential for repository-level code completion, as it integrates cross-file knowledge with in-file preceding code to provide comprehensive contexts for generation. To better understand the contribution of the retrieved cross-file contexts, we introduce a likelihood-based metric to evaluate the impact of each retrieved code chunk on the completion. Our analysis reveals that, despite retrieving numerous chunks, only a small subset positively contributes to the completion, while some chunks even degrade performance. To address this issue, we leverage this metric to construct a repository-level dataset where each retrieved chunk is labeled as positive, neutral, or negative based on its relevance to the target completion. We then propose an adaptive retrieval context filtering framework, CODEFILTER, trained on this dataset to mitigate the harmful effects of negative retrieved contexts in code completion. Extensive evaluation on the RepoEval and CrossCodeLongEval benchmarks demonstrates that CODEFILTER consistently improves completion accuracy compared to approaches without filtering operations across various tasks. Additionally, CODEFILTER significantly reduces the length of the input prompt, enhancing computational efficiency while exhibiting strong generalizability across different models. These results underscore the potential of CODEFILTER to enhance the accuracy, efficiency, and attributability of repository-level code completion.

[Arxiv](https://arxiv.org/abs/2508.05970)