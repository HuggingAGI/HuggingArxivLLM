# 动态链式思考：探索自适应深度推理之路

发布时间：2025年02月07日

`LLM应用` `人工智能`

> Dynamic Chain-of-Thought: Towards Adaptive Deep Reasoning

# 摘要

> 针对长链式思维（long CoT）中计算冗余和延迟奖励分配带来的资源消耗问题，本研究提出了一种动态链式思维（D-CoT），其特点在于自适应的推理时间和步骤。研究者通过Python 3.13 IDLE结合基于GPTs的Python仿真器进行了模拟实验，成功实现了D-CoT的集成。同时，以DeepSeek R1为对照组，测试了D-CoT仿真器处理麻省理工学院开放课程 Ware 线性代数考试题目的效果。实验数据显示，相较于基于长链式思维的DeepSeek R1，D-CoT在推理时间、链式思维长度（推理步骤）和令牌数量三个维度均表现更优，显著降低了计算资源的消耗。此外，这项研究在深度推理优化领域具有重要参考价值，为未来动态深度推理框架的设计提供了有益的借鉴。

> To reduce the cost and consumption of computing resources caused by computational redundancy and delayed reward assignment in long CoT, this research proposes the dynamic chain-of-thought with adaptive reasoning time and steps. The researcher used simulation experiment to simulate the integration of D-CoT through Python 3.13 IDLE combined with a Python simulator based on GPTs. At the same time, the researcher used DeepSeek R1 as a control group to test and compare the performance of the D-CoT simulator in processing MIT OpenCourseWare's linear algebra exam questions. Experimental results show that D-CoT is better than DeepSeek R1 based on long CoT in three indicators: reasoning time, CoT length (reasoning steps) and token count, which achieves a significant reduction in computing resource consumption. In addition, this research has potential value in deep reasoning optimization and can be used as a reference for future dynamic deep reasoning frameworks.

[Arxiv](https://arxiv.org/abs/2502.10428)