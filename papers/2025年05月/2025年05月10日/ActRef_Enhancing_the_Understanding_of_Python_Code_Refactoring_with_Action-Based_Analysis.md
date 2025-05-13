# ActRef：借助动作分析提升Python代码重构理解

发布时间：2025年05月10日

`其他` `软件工程` `代码分析`

> ActRef: Enhancing the Understanding of Python Code Refactoring with Action-Based Analysis

# 摘要

> 重构是改善软件系统代码结构而不改变其行为的过程，对于管理软件开发中的代码演化至关重要。识别源代码中的重构动作对于理解软件演化并指导开发人员维护和提升代码质量至关重要。本研究提出了一种名为ActRef的基于操作的重构分析框架，这是一种新型算法，旨在通过对代码更改的基于操作的分析，推动对Python重构的检测和理解。ActRef基于diff操作挖掘多种重构类型（例如移动、重命名、提取和内联操作），涵盖变量、方法、类和模块等多个粒度级别。通过专注于代码更改操作，ActRef为检测复杂的重构模式提供了Python自适应的解决方案。我们的评估基于从136个开源Python项目中手动验证的1,914个重构实例进行。评估结果表明，ActRef实现了高精度（0.80）和高召回率（0.92），能够有效识别多种重构类型。与领先的基线方法（包括PyRef、PyRef与MLRefScanner结合、DeepSeek-R1和ChatGPT-4）相比，ActRef在检测各种类型的Python重构方面始终表现出更优的性能。尽管在运行效率上与PyRef相当，但ActRef支持更广泛的重构类型和更深入的重构挖掘级别。ActRef为在动态的Python代码库中挖掘重构提供了一种有效且可扩展的方法，并为理解代码引入了新的视角。


> Refactoring, the process of improving the code structure of a software system without altering its behavior, is crucial for managing code evolution in software development. Identifying refactoring actions in source code is essential for understanding software evolution and guiding developers in maintaining and improving the code quality. This study presents an action-based Refactoring Analysis Framework named ActRef, a novel algorithm designed to advance the detection and understanding of Python refactorings through a unique code change action-based analysis of code changes. ActRef mining multiple refactoring types (e.g., move, rename, extract, and inline operations) based on diff actions, covering multiple granularity levels including variable, method, class, and module levels. By focusing on the code change actions, ActRef provides a Python-adaptive solution to detect intricate refactoring patterns. Our evaluation, conducted on 1,914 manually validated refactoring instances from 136 open-source Python projects. The evaluation results show that ActRef achieves high precision(0.80) and recall(0.92), effectively identifying multiple refactoring types. Compared with leading baselines, including PyRef, PyRef with MLRefScanner, DeepSeek-R1 and ChatGPT-4, ActRef consistently demonstrates superior performance in detecting Python refactorings across various types. While matching PyRef in runtime efficiency, ActRef supports a broader spectrum of refactoring types and more refactoring mining levels. ActRef shows an effective and scalable approach for mining refactorings in dynamic Python codebases and introduces a new perspective on understanding code.

[Arxiv](https://arxiv.org/abs/2505.06553)