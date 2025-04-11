# # 找到合适的专长：值得信赖的评估者，用于基于指令的图像编辑

发布时间：2025年04月09日

`LLM应用` `图像处理` `计算机视觉`

> Routing to the Right Expertise: A Trustworthy Judge for Instruction-based Image Editing

# 摘要

> 基于指令的图像编辑（IIE）模型因多模态大语言模型（MLLMs）和扩散模型的进步而实现显著提升，这些模型能够理解和推理复杂的编辑指令。在推动当前 IIE 模型发展的同时，准确评估其输出变得日益重要且具有挑战性。现有的 IIE 评估方法及其流程常难以有效契合人类判断，且缺乏可解释性。为解决这些问题，我们提出了通过专业知识路由进行判断的方法（JURE）。JURE 中的每个专家都是预选模型，具备特定的专业知识，能够提供有用的反馈来评估输出。路由器则动态分配评估任务，将给定指令及其输出路由至合适专家，整合反馈以形成最终评估结果。JURE 的优势体现在两个方面：首先，它能通过检查路由专家及其反馈，轻松提供评估结果的解释；其次，实验结果表明，JURE 与人类判断高度一致，证明了其可靠性，为自动化 IIE 评估树立了新标准。此外，JURE 的灵活设计具有前瞻性，模块化专家可无缝替换或扩展，以适应 IIE 的最新进展，同时保持高质量评估。我们的评估数据和结果可在 https://github.com/Cyyyyyrus/JURE.git 获取。

> Instruction-based Image Editing (IIE) models have made significantly improvement due to the progress of multimodal large language models (MLLMs) and diffusion models, which can understand and reason about complex editing instructions. In addition to advancing current IIE models, accurately evaluating their output has become increasingly critical and challenging. Current IIE evaluation methods and their evaluation procedures often fall short of aligning with human judgment and often lack explainability. To address these limitations, we propose JUdgement through Routing of Expertise (JURE). Each expert in JURE is a pre-selected model assumed to be equipped with an atomic expertise that can provide useful feedback to judge output, and the router dynamically routes the evaluation task of a given instruction and its output to appropriate experts, aggregating their feedback into a final judge. JURE is trustworthy in two aspects. First, it can effortlessly provide explanations about its judge by examining the routed experts and their feedback. Second, experimental results demonstrate that JURE is reliable by achieving superior alignment with human judgments, setting a new standard for automated IIE evaluation. Moreover, JURE's flexible design is future-proof - modular experts can be seamlessly replaced or expanded to accommodate advancements in IIE, maintaining consistently high evaluation quality. Our evaluation data and results are available at https://github.com/Cyyyyyrus/JURE.git.

[Arxiv](https://arxiv.org/abs/2504.07424)