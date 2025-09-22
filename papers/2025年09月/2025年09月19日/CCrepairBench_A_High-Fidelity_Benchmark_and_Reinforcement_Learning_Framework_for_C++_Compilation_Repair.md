# CCrepairBench：面向C++编译修复的高保真基准与强化学习框架

发布时间：2025年09月19日

`强化学习` `基础理论`

> CCrepairBench: A High-Fidelity Benchmark and Reinforcement Learning Framework for C++ Compilation Repair

# 摘要

> 自动修复C++编译错误是一大难题，解决它对提升开发者效率至关重要。该领域的发展主要受两大因素制约：一是缺乏大规模、高保真的数据集，二是传统监督学习方法存在局限，常常无法生成语义正确的修复补丁。本文提出了一个综合框架，通过三大核心贡献填补了这些空白。首先，我们构建了CCrepair——一个新型大规模C++编译错误数据集，它通过精密的“生成-验证”流程生成。其次，我们提出了一种基于混合奖励信号的强化学习（RL）范式，将目标从单纯的“可编译”转向修复的语义质量。最后，我们构建了一个稳健的两阶段评估系统来提供这一信号，核心是“LLM评判者”，其可靠性已通过与人类专家小组的集体判断进行严格验证。这种集成方法让训练目标聚焦于生成高质量、有实际意义的补丁，确保它们既语法正确又语义准确。实验结果验证了我们方法的有效性：经RL训练的Qwen2.5-1.5B-Instruct模型性能可媲美Qwen2.5-14B-Instruct模型，证明了该训练范式的高效性。这项研究为学术界提供了宝贵的新数据集，以及一套更有效的训练和评估稳健编译修复模型的范式，有望推动更实用、更可靠的自动化编程助手的发展。

> The automated repair of C++ compilation errors presents a significant challenge, the resolution of which is critical for developer productivity. Progress in this domain is constrained by two primary factors: the scarcity of large-scale, high-fidelity datasets and the limitations of conventional supervised methods, which often fail to generate semantically correct patches.This paper addresses these gaps by introducing a comprehensive framework with three core contributions. First, we present CCrepair, a novel, large-scale C++ compilation error dataset constructed through a sophisticated generate-and-verify pipeline. Second, we propose a Reinforcement Learning (RL) paradigm guided by a hybrid reward signal, shifting the focus from mere compilability to the semantic quality of the fix. Finally, we establish the robust, two-stage evaluation system providing this signal, centered on an LLM-as-a-Judge whose reliability has been rigorously validated against the collective judgments of a panel of human experts. This integrated approach aligns the training objective with generating high-quality, non-trivial patches that are both syntactically and semantically correct. The effectiveness of our approach was demonstrated experimentally. Our RL-trained Qwen2.5-1.5B-Instruct model achieved performance comparable to a Qwen2.5-14B-Instruct model, validating the efficiency of our training paradigm. Our work provides the research community with a valuable new dataset and a more effective paradigm for training and evaluating robust compilation repair models, paving the way for more practical and reliable automated programming assistants.

[Arxiv](https://arxiv.org/abs/2509.15690)