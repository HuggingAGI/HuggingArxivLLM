# CP-Bench：评估大型语言模型在约束建模中的表现

发布时间：2025年06月06日

`LLM应用` `组合优化` `约束编程`

> CP-Bench: Evaluating Large Language Models for Constraint Modelling

# 摘要

> 组合问题广泛存在于众多行业中，而约束编程（CP）是解决这类问题的理想范式。然而，其核心过程——约束建模——一直是制约更广泛应用的瓶颈。为了突破这一限制，近期研究尝试将大型语言模型（LLMs）作为建模助手，类似于编码助手，将组合问题描述转化为可执行的约束模型。然而，现有的约束建模评估数据集往往规模小、同质化或局限于特定领域，无法覆盖现实场景的多样性。针对这一问题，本研究推出了CP-Bench，一个全新的基准数据集，汇集了来自CP社区的多种知名组合问题类别，专为评估基于LLM的CP建模效果而设计。借助这一数据集，并考虑到多种约束建模框架的存在，我们比较并评估了LLMs在三种不同约束建模系统中的建模能力。这些系统在抽象层次和底层语法上各有特色：包括高级的MiniZinc语言、基于Python的CPMpy库，以及基于Python的OR-Tools CP-SAT求解器的低级接口。为了提升LLMs生成有效约束模型的能力，我们系统性地评估了从现有LLM代码生成研究中借鉴的提示词方法和推理时计算方法。我们的研究结果凸显了基于Python的框架在建模方面的便利性，以及富含文档的系统提示的有效性。通过结合重复采样和自我验证，这些提示进一步提升了性能，在这个极具挑战性的新基准上达到了高达70%的准确率。

> Combinatorial problems are present in a wide range of industries. Constraint Programming (CP) is a well-suited problem-solving paradigm, but its core process, namely constraint modelling, is a bottleneck for wider adoption. Aiming to alleviate this bottleneck, recent studies have explored using Large Language Models (LLMs) as modelling assistants, transforming combinatorial problem descriptions to executable constraint models, similar to coding assistants. However, the existing evaluation datasets for constraint modelling are often limited to small, homogeneous, or domain-specific instances, which do not capture the diversity of real-world scenarios. This work addresses this gap by introducing CP-Bench, a novel benchmark dataset that includes a diverse set of well-known combinatorial problem classes sourced from the CP community, structured explicitly for evaluating LLM-driven CP modelling. With this dataset, and given the variety of constraint modelling frameworks, we compare and evaluate the modelling capabilities of LLMs for three distinct constraint modelling systems, which vary in abstraction level and underlying syntax: the high-level MiniZinc language and Python-based CPMpy library, and the lower-level Python interface of the OR-Tools CP-SAT solver. In order to enhance the ability of LLMs to produce valid constraint models, we systematically evaluate the use of prompt-based and inference-time compute methods adapted from existing LLM-based code generation research. Our results underscore the modelling convenience provided by Python-based frameworks, as well as the effectiveness of documentation-rich system prompts, which, augmented with repeated sampling and self-verification, achieve further improvements, reaching up to 70\% accuracy on this new, highly challenging benchmark.

[Arxiv](https://arxiv.org/abs/2506.06052)