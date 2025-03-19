# 为动态类型程序生成单元测试的基于LLM的方法

发布时间：2025年03月18日

`RAG` `软件测试` `测试生成`

> LLM-based Unit Test Generation for Dynamically-Typed Programs

# 摘要

> 自动单元测试生成一直是研究热点，但为动态类型程序生成有效测试用例仍是重大挑战。现有方法，包括基于搜索的软件测试（SBST）及近期的基于大语言模型（LLM）的方法，常常因类型错误导致无效输入和断言失败，最终降低测试效果。为解决这一问题，我们提出TypeTest，一个通过基于向量的检索增强生成（RAG）系统提升测试生成类型准确性的新框架。TypeTest利用调用实例检索和特征检索准确推断参数类型，并构建有效测试输入。此外，它通过调用图提取更丰富的上下文信息，实现更精准的断言生成。TypeTest还引入修复机制和迭代测试生成，逐步优化测试用例以提升覆盖率。在对125个真实Python模块的评估中，TypeTest实现了86.6%的平均语句覆盖率和76.8%的分支覆盖率，分别领先现有最优工具5.4%和9.3%。

> Automated unit test generation has been widely studied, but generating effective tests for dynamically typed programs remains a significant challenge. Existing approaches, including search-based software testing (SBST) and recent LLM-based methods, often suffer from type errors, leading to invalid inputs and assertion failures, ultimately reducing testing effectiveness. To address this, we propose TypeTest, a novel framework that enhances type correctness in test generation through a vector-based Retrieval-Augmented Generation (RAG) system. TypeTest employs call instance retrieval and feature-based retrieval to infer parameter types accurately and construct valid test inputs. Furthermore, it utilizes the call graph to extract richer contextual information, enabling more accurate assertion generation. In addition, TypeTest incorporates a repair mechanism and iterative test generation, progressively refining test cases to improve coverage. In an evaluation on 125 real-world Python modules, TypeTest achieved an average statement coverage of 86.6% and branch coverage of 76.8%, outperforming state-of-theart tools by 5.4% and 9.3%, respectively.

[Arxiv](https://arxiv.org/abs/2503.14000)