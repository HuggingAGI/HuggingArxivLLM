# 开放世界中的机器人程序创建与修复

发布时间：2024年10月24日

`Agent

理由：这篇论文描述了一个名为RoboRepair的系统，该系统利用大型语言模型（LLMs）生成机器人程序，并在程序执行过程中跟踪错误并生成恢复程序。这涉及到智能体（Agent）的概念，即系统能够自主地执行任务、检测错误并进行恢复。因此，这篇论文应归类为Agent。` `机器人` `自动化`

> Creating and Repairing Robot Programs in Open-World Domains

# 摘要

> 利用大型语言模型（LLMs）从自然语言生成机器人程序，使得机器人系统能够执行更多样化的任务。然而，LLM生成的程序可能存在错误，原因可能是指令模糊、任务误解或世界状态信息缺失。随着程序运行，世界状态变化，系统会收集新信息。当发生故障时，系统需从当前状态恢复，并避免重复已成功完成的步骤。我们提出了RoboRepair系统，该系统跟踪程序执行至错误发生，然后运行LLM生成的恢复程序，以最小化重复操作。
    为评估系统效果，我们创建了一个包含十一个任务的基准测试，这些任务具有各种错误条件，需生成恢复程序。我们将恢复程序的效率与具有未来错误预知的oracle构建的计划进行比较。

> Using Large Language Models (LLMs) to produce robot programs from natural language has allowed for robot systems that can complete a higher diversity of tasks. However, LLM-generated programs may be faulty, either due to ambiguity in instructions, misinterpretation of the desired task, or missing information about the world state. As these programs run, the state of the world changes and they gather new information. When a failure occurs, it is important that they recover from the current world state and avoid repeating steps that they they previously completed successfully. We propose RoboRepair, a system which traces the execution of a program up until error, and then runs an LLM-produced recovery program that minimizes repeated actions.
  To evaluate the efficacy of our system, we create a benchmark consisting of eleven tasks with various error conditions that require the generation of a recovery program. We compare the efficiency of the recovery program to a plan built with an oracle that has foreknowledge of future errors.

[Arxiv](https://arxiv.org/abs/2410.18893)