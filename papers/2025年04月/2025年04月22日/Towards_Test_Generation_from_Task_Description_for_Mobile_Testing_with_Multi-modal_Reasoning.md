# 提出了一种基于任务描述的多模态推理驱动的移动测试生成方法，迈向智能化测试的新方向。

发布时间：2025年04月22日

`LLM应用` `软件工程` `移动应用测试`

> Towards Test Generation from Task Description for Mobile Testing with Multi-modal Reasoning

# 摘要

> 在 Android GUI 测试中，生成可回放的测试脚本以验证任务执行是常见需求。通过自然语言描述的任务目标自动生成操作序列和测试脚本，可以显著减少手动编写脚本的工作量。然而，现有的基于 LLM 的方法往往难以准确识别最终操作，导致测试要么提前终止，要么超出预期范围。本文介绍的 VisiDroid 是一个基于 LLM 的多模态多代理框架，通过迭代推理确定下一步操作，并结合屏幕视觉图像来判断任务完成状态。多模态方法在两个关键方面提升了模型性能：首先，它避免了仅依赖文本内容可能带来的误导性任务完成信号，从而防止任务过早终止；其次，视觉输入帮助工具在 GUI 变化不影响任务完成（如字体大小或颜色调整）时避免错误。此外，多模态方法确保工具不会在最终屏幕后继续执行，因为这些屏幕可能缺乏明确的文本完成指示，但可能会通过视觉元素表示任务完成，这在 GUI 应用中很常见。实验结果表明，VisiDroid 达到了 87.3% 的准确率，较最佳基线提升了 23.5%。我们的研究表明，结合图像和文本的多模态框架显著提升了 LLM 在任务完成判断方面的性能。

> In Android GUI testing, generating an action sequence for a task that can be replayed as a test script is common. Generating sequences of actions and respective test scripts from task goals described in natural language can eliminate the need for manually writing test scripts. However, existing approaches based on large language models (LLM) often struggle with identifying the final action, and either end prematurely or continue past the final screen. In this paper, we introduce VisiDroid, a multi-modal, LLM-based, multi-agent framework that iteratively determines the next action and leverages visual images of screens to detect the task's completeness. The multi-modal approach enhances our model in two significant ways. First, this approach enables it to avoid prematurely terminating a task when textual content alone provides misleading indications of task completion. Additionally, visual input helps the tool avoid errors when changes in the GUI do not directly affect functionality toward task completion, such as adjustments to font sizes or colors. Second, the multi-modal approach also ensures the tool not progress beyond the final screen, which might lack explicit textual indicators of task completion but could display a visual element indicating task completion, which is common in GUI apps. Our evaluation shows that VisiDroid achieves an accuracy of 87.3%, outperforming the best baseline relatively by 23.5%. We also demonstrate that our multi-modal framework with images and texts enables the LLM to better determine when a task is completed.

[Arxiv](https://arxiv.org/abs/2504.15917)