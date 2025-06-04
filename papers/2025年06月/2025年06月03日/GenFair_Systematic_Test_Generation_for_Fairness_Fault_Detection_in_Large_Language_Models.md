# GenFair：大型语言模型中公平性缺陷检测的系统性测试生成方法

发布时间：2025年06月03日

`LLM应用

理由：这篇论文专注于大型语言模型（LLMs）在公平性检测中的应用，提出了一种新的测试框架GenFair来解决公平性违规问题。它探讨了如何在实际应用中提高LLMs的公平性，属于LLM应用的范畴。` `人工智能` `公平性测试`

> GenFair: Systematic Test Generation for Fairness Fault Detection in Large Language Models

# 摘要

> 大型语言模型（LLMs）在关键领域的应用日益广泛，但其训练数据中的偏见往往会导致公平性问题。本研究致力于有效检测公平性违规，尤其是现有方法常忽视的交叉偏见。尽管CheckList和ASTRAEA等现有方法提供了结构化或基于语法规则的测试生成能力，但它们在测试多样性及对复杂人口统计学交互作用的敏感性方面仍有不足。为此，我们提出了GenFair——一个基于等价划分、变异算子和边界值分析系统生成源测试用例的元形公平性测试框架。通过生成语言多样化、现实且具有交叉性质的测试用例，GenFair显著提升了公平性测试的效果。它利用元形关系（MR）推导后续案例，并通过源响应与后续响应之间的语气比较精准识别公平性违规。在对GPT-4.0和LLaMA-3.0的实验中，GenFair的表现优于两种基线方法。其故障检测率（FDR）分别为0.73（GPT-4.0）和0.69（LLaMA-3.0），而基于模板的方法为0.54/0.51，ASTRAEA为0.39/0.36。此外，GenFair在测试用例多样性（语法：10.06，语义：76.68）和连贯性（语法：291.32，语义：0.7043）方面均优于两种基线方法。这些结果充分证明了GenFair在揭示细微公平性违规方面的有效性。这种方法不仅为公平性测试提供了一种可扩展且自动化的解决方案，还为构建更加公平的LLMs做出了重要贡献。

> Large Language Models (LLMs) are increasingly deployed in critical domains, yet they often exhibit biases inherited from training data, leading to fairness concerns. This work focuses on the problem of effectively detecting fairness violations, especially intersectional biases that are often missed by existing template-based and grammar-based testing methods. Previous approaches, such as CheckList and ASTRAEA, provide structured or grammar-driven test generation but struggle with low test diversity and limited sensitivity to complex demographic interactions. To address these limitations, we propose GenFair, a metamorphic fairness testing framework that systematically generates source test cases using equivalence partitioning, mutation operators, and boundary value analysis. GenFair improves fairness testing by generating linguistically diverse, realistic, and intersectional test cases. It applies metamorphic relations (MR) to derive follow-up cases and detects fairness violations via tone-based comparisons between source and follow-up responses. In experiments with GPT-4.0 and LLaMA-3.0, GenFair outperformed two baseline methods. It achieved a fault detection rate (FDR) of 0.73 (GPT-4.0) and 0.69 (LLaMA-3.0), compared to 0.54/0.51 for template-based and 0.39/0.36 for ASTRAEA. GenFair also showed the highest test case diversity (syntactic:10.06, semantic: 76.68) and strong coherence (syntactic: 291.32, semantic: 0.7043), outperforming both baselines. These results demonstrate the effectiveness of GenFair in uncovering nuanced fairness violations. The proposed method offers a scalable and automated solution for fairness testing and contributes to building more equitable LLMs.

[Arxiv](https://arxiv.org/abs/2506.03024)