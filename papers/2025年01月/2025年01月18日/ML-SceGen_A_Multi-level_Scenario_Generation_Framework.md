# ML-SceGen: 多层次场景生成框架

发布时间：2025年01月18日

`Agent

理由：这篇论文描述了一个三阶段框架，其中LLM代理在场景生成过程中扮演了关键角色。具体来说，LLM代理负责将预期场景描述转化为功能场景，并在最后阶段更新参数以提升场景的关键程度。这表明LLM被用作一个自主的代理，负责执行特定的任务和决策，因此应归类为Agent。` `自动驾驶` `交通管理`

> ML-SceGen: A Multi-level Scenario Generation Framework

# 摘要

> 当前科学研究中，许多尝试将大型语言模型应用于场景生成，但大多局限于全面或危险的场景。本文提出一个三阶段框架，旨在让用户重获对生成场景的控制权，并在无控制交叉路口生成包含危险因素的全面场景。第一阶段，LLM代理将预期场景描述的关键部分转化为功能场景；第二阶段，利用ASP求解器Clingo生成交叉路口的全面逻辑交通；最后阶段，通过LLM更新参数，提升具体场景的关键程度。

> Current scientific research witnesses various attempts at applying Large Language Models for scenario generation but is inclined only to comprehensive or dangerous scenarios. In this paper, we seek to build a three-stage framework that not only lets users regain controllability over the generated scenarios but also generates comprehensive scenarios containing danger factors in uncontrolled intersection settings. In the first stage, LLM agents will contribute to translating the key components of the description of the expected scenarios into Functional Scenarios. For the second stage, we use Answer Set Programming (ASP) solver Clingo to help us generate comprehensive logical traffic within intersections. During the last stage, we use LLM to update relevant parameters to increase the critical level of the concrete scenario.

[Arxiv](https://arxiv.org/abs/2501.10782)