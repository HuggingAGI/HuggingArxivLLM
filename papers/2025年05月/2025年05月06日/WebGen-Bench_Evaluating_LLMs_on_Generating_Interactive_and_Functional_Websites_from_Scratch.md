# 从零开始构建交互式网站，评估LLMs的网站生成能力——WebGen-Bench

发布时间：2025年05月06日

`LLM应用

摘要中讨论了基于LLM的智能体在生成和管理代码库中的应用，介绍了基准测试、评估方法和实际性能，重点在于LLM的应用场景和效果，因此归类为LLM应用。` `网站开发` `代码生成`

> WebGen-Bench: Evaluating LLMs on Generating Interactive and Functional Websites from Scratch

# 摘要

> 基于LLM的智能体在生成和管理复杂代码库方面展现了巨大潜力。本文介绍了WebGen-Bench，这是一个旨在衡量LLM智能体从零创建多文件网站代码库能力的新基准。该基准包含由人工标注员与GPT-4o协作生成的多样化网站生成指令，涵盖三大主要类别和十三个次要类别，几乎囊括了所有重要的网络应用类型。为了评估生成网站的质量，我们使用GPT-4o针对每个指令中描述的功能生成测试用例，随后手动筛选、调整和整理这些用例以确保准确性，最终得到647个测试用例。每个测试用例都规定了要在网站上执行的操作以及操作后的预期结果。为了实现自动化测试并提高可重复性，我们采用了一个强大的网络导航智能体来执行测试，并判断观察到的响应是否与预期结果一致。我们使用多种专有和开源LLM作为引擎，评估了三个高性能代码智能体框架：Bolt.diy、OpenHands 和Aider。其中表现最佳的组合，由DeepSeek-R1驱动的Bolt.diy，仅在测试用例中达到了27.8%的准确率，凸显了我们基准的挑战性。此外，我们构建了WebGen-Instruct，这是一个包含6,667个网站生成指令的训练集。在Bolt.diy轨迹的基础上，使用该训练集的一个子集对Qwen2.5-Coder-32B-Instruct进行训练，达到了38.2%的准确率，超过了最佳专有模型的性能。

> LLM-based agents have demonstrated great potential in generating and managing code within complex codebases. In this paper, we introduce WebGen-Bench, a novel benchmark designed to measure an LLM-based agent's ability to create multi-file website codebases from scratch. It contains diverse instructions for website generation, created through the combined efforts of human annotators and GPT-4o. These instructions span three major categories and thirteen minor categories, encompassing nearly all important types of web applications. To assess the quality of the generated websites, we use GPT-4o to generate test cases targeting each functionality described in the instructions, and then manually filter, adjust, and organize them to ensure accuracy, resulting in 647 test cases. Each test case specifies an operation to be performed on the website and the expected result after the operation. To automate testing and improve reproducibility, we employ a powerful web-navigation agent to execute tests on the generated websites and determine whether the observed responses align with the expected results. We evaluate three high-performance code-agent frameworks, Bolt.diy, OpenHands, and Aider, using multiple proprietary and open-source LLMs as engines. The best-performing combination, Bolt.diy powered by DeepSeek-R1, achieves only 27.8\% accuracy on the test cases, highlighting the challenging nature of our benchmark. Additionally, we construct WebGen-Instruct, a training set consisting of 6,667 website-generation instructions. Training Qwen2.5-Coder-32B-Instruct on Bolt.diy trajectories generated from a subset of this training set achieves an accuracy of 38.2\%, surpassing the performance of the best proprietary model.

[Arxiv](https://arxiv.org/abs/2505.03733)