# 评估大型语言模型在真实临床案例中的推理能力

发布时间：2025年03月06日

`LLM应用`

> Quantifying the Reasoning Abilities of LLMs on Real-world Clinical Cases

# 摘要

> 最新推理增强型大型语言模型（如 DeepSeek-R1 和 OpenAI-o3）取得了显著成功，但其在专业医疗领域的应用效果尚未得到充分评估，尤其是在推理过程质量方面。我们提出了一项名为 MedR-Bench 的医疗推理评估基准，包含 1,453 个结构化患者案例及推理参考，覆盖 13 个身体系统和 10 种专科疾病。通过评估框架，我们从评估建议、诊断决策和治疗规划三个临床阶段，全面考察了 LLMs 在医疗场景中的表现。我们还开发了一种名为推理评估器的智能系统，从效率、事实性和完整性三个维度，通过动态搜索和交叉引用，自动量化推理响应质量。实验结果显示，当前 LLMs 在简单诊断任务中表现优异，准确率超 85%，但在复杂任务中仍显不足。其推理过程总体可靠，事实性得分超 90%，但常遗漏关键步骤。本研究为临床 LLMs 的未来发展指明了方向。

> The latest reasoning-enhanced large language models (reasoning LLMs), such as DeepSeek-R1 and OpenAI-o3, have demonstrated remarkable success. However, the application of such reasoning enhancements to the highly professional medical domain has not been clearly evaluated, particularly regarding with not only assessing the final generation but also examining the quality of their reasoning processes. In this study, we present MedR-Bench, a reasoning-focused medical evaluation benchmark comprising 1,453 structured patient cases with reasoning references mined from case reports. Our benchmark spans 13 body systems and 10 specialty disorders, encompassing both common and rare diseases. In our evaluation, we introduce a versatile framework consisting of three critical clinical stages: assessment recommendation, diagnostic decision-making, and treatment planning, comprehensively capturing the LLMs' performance across the entire patient journey in healthcare. For metrics, we propose a novel agentic system, Reasoning Evaluator, designed to automate and objectively quantify free-text reasoning responses in a scalable manner from the perspectives of efficiency, factuality, and completeness by dynamically searching and performing cross-referencing checks. As a result, we assess five state-of-the-art reasoning LLMs, including DeepSeek-R1, OpenAI-o3-mini, and others. Our results reveal that current LLMs can handle relatively simple diagnostic tasks with sufficient critical assessment results, achieving accuracy generally over 85%. However, they still struggle with more complex tasks, such as assessment recommendation and treatment planning. In reasoning, their reasoning processes are generally reliable, with factuality scores exceeding 90%, though they often omit critical reasoning steps. Our study clearly reveals further development directions for current clinical LLMs.

[Arxiv](https://arxiv.org/abs/2503.04691)