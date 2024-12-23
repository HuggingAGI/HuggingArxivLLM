# CAD-Assistant：工具增强型 VLLMs 能成为通用的 CAD 任务求解器吗？

发布时间：2024年12月18日

`Agent` `CAD 设计` `AI 辅助设计`

> CAD-Assistant: Tool-Augmented VLLMs as Generic CAD Task Solvers?

# 摘要

> 我们推出了 CAD-Assistant，这是一款用于 AI 辅助设计的通用 CAD 代理。我们的方法以强大的视觉和大型语言模型（VLLM）作为规划器，并采用了借助 CAD 特定模块的工具增强范式。CAD-Assistant 能处理多模态用户的查询，通过生成操作并在配备 FreeCAD 软件的 Python 解释器上迭代执行，该解释器通过其 Python API 访问。我们的框架能够评估生成的 CAD 命令对几何形状的影响，并依据 CAD 设计的演变状态调整后续操作。我们考虑了众多 CAD 专用工具，涵盖 Python 库、FreeCAD Python API 的模块、实用例程、渲染函数及其他专门模块。我们在多个 CAD 基准上对我们的方法进行评估，定性地展现了工具增强型 VLLM 作为不同 CAD 工作流程中通用 CAD 任务求解器的潜力。

> We propose CAD-Assistant, a general-purpose CAD agent for AI-assisted design. Our approach is based on a powerful Vision and Large Language Model (VLLM) as a planner and a tool-augmentation paradigm using CAD-specific modules. CAD-Assistant addresses multimodal user queries by generating actions that are iteratively executed on a Python interpreter equipped with the FreeCAD software, accessed via its Python API. Our framework is able to assess the impact of generated CAD commands on geometry and adapts subsequent actions based on the evolving state of the CAD design. We consider a wide range of CAD-specific tools including Python libraries, modules of the FreeCAD Python API, helpful routines, rendering functions and other specialized modules. We evaluate our method on multiple CAD benchmarks and qualitatively demonstrate the potential of tool-augmented VLLMs as generic CAD task solvers across diverse CAD workflows.

[Arxiv](https://arxiv.org/abs/2412.13810)