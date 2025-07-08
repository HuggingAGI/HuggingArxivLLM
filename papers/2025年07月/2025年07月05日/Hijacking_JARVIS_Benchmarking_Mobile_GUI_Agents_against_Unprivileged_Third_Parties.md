# 劫持JARVIS：基准测试移动GUI代理对抗无特权第三方

发布时间：2025年07月05日

`Agent` `移动端安全` `人机交互`

> Hijacking JARVIS: Benchmarking Mobile GUI Agents against Unprivileged Third Parties

# 摘要

> 移动端GUI代理通过解析和交互移动屏幕，自主执行多样化的设备控制任务。尽管取得了显著进展，但它们在现实场景中的鲁棒性仍存在重大挑战，尤其是在屏幕内容可能被不可信第三方部分操纵的情况下。由于其黑箱特性和自主性，这些代理容易受到可能危害用户设备的操控。在本研究中，我们首次系统性地探索了移动端GUI代理的漏洞问题。我们引入了一个可扩展的攻击模拟框架AgentHazard，它能够在现有应用中灵活、有针对性地修改屏幕内容。借助这一框架，我们构建了一个全面的基准测试套件，包含动态任务执行环境和静态视觉-语言-动作元组数据集，总计涵盖超过3,000种攻击场景。动态环境包含了在模拟器中可复现的58项任务，涉及多种危险UI内容，而静态数据集则由从14款热门商业应用中收集的210张截图构成。特别值得注意的是，我们的内容修改方案是可行的，即便对于无特权的第三方也是如此。我们使用这一基准测试套件评估了7款广泛使用的移动端GUI代理和5种常见的基础模型。研究结果表明，所有被测代理均显著受制于第三方误导内容（在人工设计的攻击场景中，平均误导率达到28.8%），且其漏洞与所采用的感知模态和基础LLM密切相关。此外，我们还评估了基于训练的缓解策略，揭示了提升移动端GUI代理稳健性的挑战与机遇。我们的代码和数据将在https://agenthazard.github.io上公开发布。

> Mobile GUI agents are designed to autonomously execute diverse device-control tasks by interpreting and interacting with mobile screens. Despite notable advancements, their resilience in real-world scenarios where screen content may be partially manipulated by untrustworthy third parties remains largely unexplored. Owing to their black-box and autonomous nature, these agents are vulnerable to manipulations that could compromise user devices. In this work, we present the first systematic investigation into the vulnerabilities of mobile GUI agents. We introduce a scalable attack simulation framework AgentHazard, which enables flexible and targeted modifications of screen content within existing applications. Leveraging this framework, we develop a comprehensive benchmark suite comprising both a dynamic task execution environment and a static dataset of vision-language-action tuples, totaling over 3,000 attack scenarios. The dynamic environment encompasses 58 reproducible tasks in an emulator with various types of hazardous UI content, while the static dataset is constructed from 210 screenshots collected from 14 popular commercial apps. Importantly, our content modifications are designed to be feasible for unprivileged third parties. We evaluate 7 widely-used mobile GUI agents and 5 common backbone models using our benchmark. Our findings reveal that all examined agents are significantly influenced by misleading third-party content (with an average misleading rate of 28.8% in human-crafted attack scenarios) and that their vulnerabilities are closely linked to the employed perception modalities and backbone LLMs. Furthermore, we assess training-based mitigation strategies, highlighting both the challenges and opportunities for enhancing the robustness of mobile GUI agents. Our code and data will be released at https://agenthazard.github.io.

[Arxiv](https://arxiv.org/abs/2507.04227)