# QualityFlow: 基于LLM质量检查的程序合成智能工作流

发布时间：2025年01月20日

`Agent

理由：这篇论文介绍了QualityFlow，一个由多个LLM代理组成的动态智能工作流，用于程序合成。这些代理模拟软件开发团队，涵盖代码生成、测试和自我调试等功能。论文的核心在于LLM质量检查器，它动态控制工作流，确保程序合成的质量和准确性。因此，这篇论文主要涉及多个LLM代理的协作和动态工作流管理，属于Agent分类。` `软件开发` `程序合成`

> QualityFlow: An Agentic Workflow for Program Synthesis Controlled by LLM Quality Checks

# 摘要

> 我们推出了QualityFlow，一个用于程序合成的动态智能工作流。给定编程问题的英文描述和一组单元测试，模型的目标是合成一个能够解决问题并通过测试的正确程序。QualityFlow由多个LLM代理组成，这些代理模拟软件开发团队，涵盖代码生成、测试和自我调试。现有程序合成方法面临三大挑战：单元测试可见性假设、合成测试质量瓶颈以及自我调试轨迹偏差。为此，我们提出了LLM质量检查器，它能够“想象”合成程序的执行是否符合单元测试。质量检查器动态控制工作流，包括提交最终答案、澄清问题陈述和回滚先前步骤等操作。因此，质量检查器能够精确接受正确程序，减少错误测试，并防止工作流偏差。质量检查器的成功还推动了多样化提示，鼓励LLM响应的多样性，以最大化正确程序出现并通过质量检查的可能性。在实验中，QualityFlow在MBPP、HumanEval以及EvalPlus对MBPP和HumanEval的更严格评估中取得了最先进的结果。我们的系统分析表明，由LLM质量检查控制的动态工作流优于静态工作流和单次尝试的零-shot合成。质量检查器是我们研究的核心，我们详细分析了它的个体性能和对工作流准确性的影响，并通过消融实验验证了工作流设计的合理性。

> We introduce QualityFlow, a dynamic agentic workflow for program synthesis. Given the English description of a programming problem and a set of unit tests, the model's goal is to synthesize the correct program that solves the problem and passes the tests. QualityFlow consists of multiple large language model (LLM) agents that resemble a software development team, including code generation, testing, and self-debugging. Existing program synthesis methods face three major limitations: assumption of visible unit test conformity, bottleneck of synthesized test quality, and deviation of self-debugging trajectory. To address them, we propose the LLM Quality Checker, which explicitly "imagines" whether the synthesized programs' execution would conform to the unit tests. The Quality Checks dynamically control the workflow, including actions to submit the final answer, clarify the problem statement, and revert previous workflow steps. As a result, our Quality Checker can precisely accept any correct program, mitigate faulty synthesized tests, and prevent potential workflow deviation. The success of the Quality Checker further enables Diversified Prompting, which encourages variations in LLM responses to maximize the possibility that a correct program appears and passes the quality check. In experiments, QualityFlow establishes the state-of-the-art results on four program synthesis benchmarks: MBPP, HumanEval, and the stricter evaluations of both MBPP and HumanEval from EvalPlus. Our systematic analysis shows that the dynamic workflow controlled by LLM quality checks can outperform static workflows and single-attempt zero-shot synthesis. The Quality Checker is the center of our investigation, and we dissect its individual performance and integrated impact on the workflow accuracy, as well as other ablations experiments to justify our workflow design.

[Arxiv](https://arxiv.org/abs/2501.17167)