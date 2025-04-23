# VeriCoder：借助功能正确性验证提升LLM驱动的RTL代码生成能力

发布时间：2025年04月22日

`LLM应用` `EDA` `硬件设计`

> VeriCoder: Enhancing LLM-Based RTL Code Generation through Functional Correctness Validation

# 摘要

> 大型语言模型（LLMs）的突破性进展激发了将其应用于电子设计自动化（EDA）任务，特别是寄存器传输级（RTL）代码生成的浓厚兴趣。虽然已有多个RTL数据集问世，但大多侧重于语法正确性，忽视了通过测试的功能验证，导致生成的RTL代码虽能编译，却未必符合预期功能。为此，我们推出了VERICODER——一个在经过功能验证的数据集上微调的RTL代码生成模型。

该数据集采用创新方法构建，结合了单元测试生成与反馈驱动优化。具体而言，给定自然语言需求和初始RTL设计，我们借助教师模型（GPT-4o-mini）生成单元测试，并利用这些测试对RTL设计进行迭代优化，确保其满足功能需求。必要时，教师模型还会更新测试以确保与自然语言需求一致。通过这一流程，我们确保了数据集中每个示例都经过严格的功能验证，包含自然语言描述、RTL实现及通过的测试。

在超过125,000个示例的高质量数据集上微调后，VERICODER在VerilogEval和RTLLM基准测试中实现了功能正确性的最新水平，分别较现有方法提升了71.7%和27.4%。消融实验进一步证实，基于我们功能验证数据集训练的模型显著优于传统数据集训练的模型，凸显了高质量数据集在RTL代码生成中的关键作用。

> Recent advances in Large Language Models (LLMs) have sparked growing interest in applying them to Electronic Design Automation (EDA) tasks, particularly Register Transfer Level (RTL) code generation. While several RTL datasets have been introduced, most focus on syntactic validity rather than functional validation with tests, leading to training examples that compile but may not implement the intended behavior. We present VERICODER, a model for RTL code generation fine-tuned on a dataset validated for functional correctness. This fine-tuning dataset is constructed using a novel methodology that combines unit test generation with feedback-directed refinement. Given a natural language specification and an initial RTL design, we prompt a teacher model (GPT-4o-mini) to generate unit tests and iteratively revise the RTL design based on its simulation results using the generated tests. If necessary, the teacher model also updates the tests to ensure they comply with the natural language specification. As a result of this process, every example in our dataset is functionally validated, consisting of a natural language description, an RTL implementation, and passing tests. Fine-tuned on this dataset of over 125,000 examples, VERICODER achieves state-of-the-art metrics in functional correctness on VerilogEval and RTLLM, with relative gains of up to 71.7% and 27.4% respectively. An ablation study further shows that models trained on our functionally validated dataset outperform those trained on functionally non-validated datasets, underscoring the importance of high-quality datasets in RTL code generation.

[Arxiv](https://arxiv.org/abs/2504.15659)