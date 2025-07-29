# MMBench-GUI: 一个层次化多平台的图形用户界面智能体评估框架

发布时间：2025年07月25日

`Agent` `软件工程` `自动化测试`

> MMBench-GUI: Hierarchical Multi-Platform Evaluation Framework for GUI Agents

# 摘要

> 我们推出MMBench-GUI，这是一个跨平台的GUI自动化代理评估工具，覆盖Windows、macOS、Linux、iOS、Android和Web六大平台。该基准测试分为四个层级：内容理解、元素定位、任务执行和协作能力，全面考察GUI代理的核心技能。我们还创新性地提出了效率-质量区域（EQA）指标，用于量化在线自动化场景下的执行效率。通过MMBench-GUI的研究发现，准确的视觉定位是任务成功的关键，模块化架构与专用定位模块的结合能显著提升性能。此外，可靠的GUI自动化需要代理具备强大的任务规划和跨平台适应能力，长上下文记忆、广泛的操作空间以及长期推理能力是实现这一目标的核心要素。特别值得注意的是，任务效率这一维度仍有待深入探索，现有模型普遍面临执行低效问题，即使完成任务也会产生大量冗余步骤。精准定位、智能规划与提前终止策略的协同应用是实现高效且可扩展GUI自动化的关键所在。我们的基准测试代码、数据集及运行环境即将在https://github.com/open-compass/MMBench-GUI开源。

> We introduce MMBench-GUI, a hierarchical benchmark for evaluating GUI automation agents across Windows, macOS, Linux, iOS, Android, and Web platforms. It comprises four levels: GUI Content Understanding, Element Grounding, Task Automation, and Task Collaboration, covering essential skills for GUI agents. In addition, we propose a novel Efficiency-Quality Area (EQA) metric to assess GUI agent execution efficiency in online automation scenarios. Through MMBench-GUI, we identify accurate visual grounding as a critical determinant of overall task success, emphasizing the substantial benefits of modular frameworks that integrate specialized grounding modules. Furthermore, to achieve reliable GUI automation, an agent requires strong task planning and cross-platform generalization abilities, with long-context memory, a broad action space, and long-term reasoning playing a critical role. More important, task efficiency remains a critically underexplored dimension, and all models suffer from substantial inefficiencies, with excessive redundant steps even when tasks are ultimately completed. The integration of precise localization, effective planning, and early stopping strategies is indispensable to enable truly efficient and scalable GUI automation. Our benchmark code, evaluation data, and running environment will be publicly available at https://github.com/open-compass/MMBench-GUI.

[Arxiv](https://arxiv.org/abs/2507.19478)