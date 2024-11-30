# 为实现高效库导向的代码生成，我们提出了一种组合式API推荐方法。该方法旨在探索和推荐适用于此类任务的恰当API组合，以提升编程效率及代码质量。

发布时间：2024年02月29日

`LLM应用`

> Compositional API Recommendation for Library-Oriented Code Generation

# 摘要

> 尽管LLMs在代码生成领域表现出色，但面对未在训练数据中出现过的库时，生成面向库的代码能力仍有欠缺。过去的研究尝试借助API推荐技术引导LLMs使用库，即找出符合用户需求的API作为输入提示。然而，由于实际开发需求往往涉及多条细粒度API的综合应用，粒度匹配难题使API推荐成为一项棘手工作。因此，我们创新性地提出了CAPIR方案，采用“化整为零”的策略解决粗略需求下的API推荐问题。CAPIR首先利用基于LLM的分解器将大块任务细化为一系列小任务，再通过嵌入式检索器找到与各小任务相匹配的API。同时，CAPIR依靠LLM优化后的重排序机制筛选掉冗余API，确保最终推荐的精准性。为了更准确评估针对粗粒度需求的API推荐效果，我们构建了两个难度较高的基准测试——RAPID（基于文档推荐API）和LOCG（面向库的代码生成）。实验证明，在这两个基准上，CAPIR相比于现有基准方法表现出了显著优势。以RAPID中的Torchdata-AR数据集为例，CAPIR相对于当前最先进API推荐方法，成功将召回率@5提升了约24.5个百分点至43.2%，并将精确率@5提高了约21.6个百分点达到37.1%；而在LOCG的Torchdata-Code数据集中，相较于没有采用API推荐的代码生成方式，CAPIR将pass@100指标提高了大约12个百分点，达到了28.0%。

> Large language models (LLMs) have achieved exceptional performance in code generation. However, the performance remains unsatisfactory in generating library-oriented code, especially for the libraries not present in the training data of LLMs. Previous work utilizes API recommendation technology to help LLMs use libraries: it retrieves APIs related to the user requirements, then leverages them as context to prompt LLMs. However, developmental requirements can be coarse-grained, requiring a combination of multiple fine-grained APIs. This granularity inconsistency makes API recommendation a challenging task. To address this, we propose CAPIR (Compositional API Recommendation), which adopts a "divide-and-conquer" strategy to recommend APIs for coarse-grained requirements. Specifically, CAPIR employs an LLM-based Decomposer to break down a coarse-grained task description into several detailed subtasks. Then, CAPIR applies an embedding-based Retriever to identify relevant APIs corresponding to each subtask. Moreover, CAPIR leverages an LLM-based Reranker to filter out redundant APIs and provides the final recommendation. To facilitate the evaluation of API recommendation methods on coarse-grained requirements, we present two challenging benchmarks, RAPID (Recommend APIs based on Documentation) and LOCG (Library-Oriented Code Generation). Experimental results on these benchmarks, demonstrate the effectiveness of CAPIR in comparison to existing baselines. Specifically, on RAPID's Torchdata-AR dataset, compared to the state-of-the-art API recommendation approach, CAPIR improves recall@5 from 18.7% to 43.2% and precision@5 from 15.5% to 37.1%. On LOCG's Torchdata-Code dataset, compared to code generation without API recommendation, CAPIR improves pass@100 from 16.0% to 28.0%.

[Arxiv](https://arxiv.org/abs/2402.19431)