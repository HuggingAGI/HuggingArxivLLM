# GUI 测试竞技场：促进自主 GUI 测试代理发展的统一基准

发布时间：2024年12月24日

`Agent` `GUI 测试`

> GUI Testing Arena: A Unified Benchmark for Advancing Autonomous GUI Testing Agent

# 摘要

> 如今，GUI 代理的研究在 AI 领域是热门话题。不过，当下的研究侧重于 GUI 任务自动化，这限制了其在各类 GUI 场景中的应用范围。本文中，我们提出了一个形式化且全面的环境来评估自动化 GUI 测试（GTArena）的整个流程，为不同的多模态大型语言模型的稳定运行提供了公平、标准化的环境。我们把测试过程划分为三个关键子任务：测试意图生成、测试任务执行和 GUI 缺陷检测，并基于此构建了基准数据集以展开全面评估。它通过三种数据类型来评估不同模型的性能：真实的移动应用程序、有人工注入缺陷的移动应用程序以及合成数据，从而全面考量它们在相关任务中的能力。另外，我们还提出了一种方法，助力研究人员探究多模态语言大型模型在特定场景中的表现与其在标准基准测试中的一般能力之间的关联。实验结果显示，即便是最先进的模型，在自动化 GUI 测试的所有子任务中也难以有出色表现，凸显出自主 GUI 测试的当前能力与实际应用之间存在显著差距。这一差距为 GUI 代理的未来发展指明了方向。我们的代码可在 https://github.com/ZJU-ACES-ISE/ChatUITest 获取。

> Nowadays, research on GUI agents is a hot topic in the AI community. However, current research focuses on GUI task automation, limiting the scope of applications in various GUI scenarios. In this paper, we propose a formalized and comprehensive environment to evaluate the entire process of automated GUI Testing (GTArena), offering a fair, standardized environment for consistent operation of diverse multimodal large language models. We divide the testing process into three key subtasks: test intention generation, test task execution, and GUI defect detection, and construct a benchmark dataset based on these to conduct a comprehensive evaluation. It evaluates the performance of different models using three data types: real mobile applications, mobile applications with artificially injected defects, and synthetic data, thoroughly assessing their capabilities in this relevant task. Additionally, we propose a method that helps researchers explore the correlation between the performance of multimodal language large models in specific scenarios and their general capabilities in standard benchmark tests. Experimental results indicate that even the most advanced models struggle to perform well across all sub-tasks of automated GUI Testing, highlighting a significant gap between the current capabilities of Autonomous GUI Testing and its practical, real-world applicability. This gap provides guidance for the future direction of GUI Agent development. Our code is available at https://github.com/ZJU-ACES-ISE/ChatUITest.

[Arxiv](https://arxiv.org/abs/2412.18426)