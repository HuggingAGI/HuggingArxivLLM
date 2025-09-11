# AutoVeriFix：自动纠错并提升LLM生成的Verilog代码功能正确性

发布时间：2025年09月10日

`LLM应用` `工业与制造`

> AutoVeriFix: Automatically Correcting Errors and Enhancing Functional Correctness in LLM-Generated Verilog Code

# 摘要

> 大型语言模型（LLMs）在生成Python、C++等高级编程语言代码时表现出惊人的能力，但若要应用于Verilog这类硬件描述语言，却因高质量训练数据匮乏而举步维艰。现有基于LLMs的Verilog代码生成方法常执着于语法正确，结果产出大量功能失效的代码。为此，我们提出AutoVeriFix：一种创新的Python辅助两阶段框架，专门用于提升LLM生成Verilog代码的功能正确性。第一阶段，借助LLMs生成高级Python参考模型，精准定义电路的预期行为；第二阶段，这些Python模型驱动自动化测试的构建，进而指导Verilog RTL实现的生成。通过迭代分析参考模型与Verilog代码的模拟差异来定位并修复错误，最终大幅提升LLM生成Verilog代码的功能准确性与可靠性。实验结果证实，该方法在提升生成Verilog代码功能正确性上，性能远超当前最先进的技术。

> Large language models (LLMs) have demonstrated impressive capabilities in generating software code for high-level programming languages such as Python and C++. However, their application to hardware description languages, such as Verilog, is challenging due to the scarcity of high-quality training data. Current approaches to Verilog code generation using LLMs often focus on syntactic correctness, resulting in code with functional errors. To address these challenges, we present AutoVeriFix, a novel Python-assisted two-stage framework designed to enhance the functional correctness of LLM-generated Verilog code. In the first stage, LLMs are employed to generate high-level Python reference models that define the intended circuit behavior. In the second stage, these Python models facilitate the creation of automated tests that guide the generation of Verilog RTL implementations. Simulation discrepancies between the reference model and the Verilog code are iteratively used to identify and correct errors, thereby improving the functional accuracy and reliability of the LLM-generated Verilog code. Experimental results demonstrate that our approach significantly outperforms existing state-of-the-art methods in improving the functional correctness of generated Verilog code.

[Arxiv](https://arxiv.org/abs/2509.08416)