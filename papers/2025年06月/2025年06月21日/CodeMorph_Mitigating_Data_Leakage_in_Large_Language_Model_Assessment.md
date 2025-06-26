# CodeMorph：解决大型语言模型评估中的数据泄露问题

发布时间：2025年06月21日

`LLM应用` `代码生成` `数据安全`

> CodeMorph: Mitigating Data Leakage in Large Language Model Assessment

# 摘要

> 代码大型语言模型（Code LLMs）中的基准测试数据泄漏问题引发了数据污染和评估指标虚高的争议。由于训练数据集的多样性和难以获取的特点，即使采用时间滞后策略，也难以完全避免数据泄漏。因此，通过代码扰动生成新的数据集变得至关重要。然而，现有方法在生成复杂多样变体、处理复杂跨文件依赖以及支持多种编程语言方面存在局限性，这限制了它们在提升LLM代码任务评估效果方面的有效性。

为了解决这一问题，我们提出了CodeMorph，一种支持多种编程语言并保留跨文件依赖关系以缓解数据泄漏问题的方法。CodeMorph包含两个主要组件，它们协同工作以增强扰动过程。第一个组件采用26种语义保留的代码变换方法，通过迭代扰动代码，生成多样化变体，同时确保修改后的代码仍可编译。第二个组件引入了一种基于遗传算法的PESO选择算法，通过降低扰动代码与原始代码之间的相似性得分，为每次迭代识别出更有效的扰动方法，从而提升整体扰动效果。

实验结果表明，应用CodeMorph后，LLM在五种编程语言的代码补全任务中的准确率平均下降了24.67%，其中Python的下降幅度最大，达到45%。经过PESO优化的代码相似性得分平均比随机扰动的代码低7.01%，最高下降幅度为42.86%。

> Concerns about benchmark leakage in large language models for code (Code LLMs) have raised issues of data contamination and inflated evaluation metrics. The diversity and inaccessibility of many training datasets make it difficult to prevent data leakage entirely, even with time lag strategies. Consequently, generating new datasets through code perturbation has become essential. However, existing methods often fail to produce complex and diverse variations, struggle with complex cross-file dependencies, and lack support for multiple programming languages, which limits their effectiveness in enhancing LLM evaluations for coding tasks. To fill this gap, we propose CodeMorph, an approach designed to support multiple programming languages while preserving cross-file dependencies to mitigate data leakage. CodeMorph consists of two main components that work together to enhance the perturbation process. The first component employs 26 semantic-preserving transformation methods to iteratively perturb code, generating diverse variations while ensuring that the modified code remains compilable. The second component introduces a genetic algorithm-based selection algorithm, PESO, to identify the more effective perturbation method for each iteration by targeting lower similarity scores between the perturbed and original code, thereby enhancing overall perturbation effectiveness. Experimental results demonstrate that after applying CodeMorph, the accuracy of the LLM on code completion tasks across five programming languages decreased by an average of 24.67%, with Python showing the most significant reduction at 45%. The similarity score of code optimized by PESO is, on average, 7.01% lower than that of randomly perturbed code, peaking at a reduction of 42.86%.

[Arxiv](https://arxiv.org/abs/2506.17627)