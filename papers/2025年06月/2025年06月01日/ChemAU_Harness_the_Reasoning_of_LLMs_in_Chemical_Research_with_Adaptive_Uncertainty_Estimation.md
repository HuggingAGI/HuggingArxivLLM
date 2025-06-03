# ChemAU：驾驭LLMs在化学研究中的推理能力，结合自适应不确定性评估

发布时间：2025年06月01日

`LLM应用` `人工智能`

> ChemAU: Harness the Reasoning of LLMs in Chemical Research with Adaptive Uncertainty Estimation

# 摘要

> 大型语言模型（LLMs）凭借其卓越的推理能力和自然语言理解能力，在多个场景中得到了广泛应用。尽管LLMs在数学和编码任务中表现出色，但在化学相关问题上却力不从心。化学问题通常涉及长而复杂的推理过程，包含大量专业术语、符号系统和命名规则。这些特点使得通用LLMs在推理过程中容易产生知识空白，因为它们缺乏特定领域的专业知识。现有方法难以有效整合化学专业知识和公式，而现有的不确定性估计方法虽旨在缓解推理错误，却无法精准定位具体步骤或关键知识点。为此，我们提出了名为ChemAU的新框架，其中集成了自适应不确定性估计方法。该方法根据推理步骤在整个推理链中的位置，动态调整不确定性值。借助这一方法，ChemAU能够精准识别化学知识中的空白，并通过专用领域模型补充专业知识，从而修复和更新有缺陷的推理链。我们在三个化学数据集上对三个流行LLMs进行了实验，结果表明，ChemAU显著提升了推理准确性和不确定性估计的精度。

> Large Language Models (LLMs) are widely used across various scenarios due to their exceptional reasoning capabilities and natural language understanding. While LLMs demonstrate strong performance in tasks involving mathematics and coding, their effectiveness diminishes significantly when applied to chemistry-related problems. Chemistry problems typically involve long and complex reasoning steps, which contain specific terminology, including specialized symbol systems and complex nomenclature conventions. These characteristics often cause general LLMs to experience hallucinations during the reasoning process due to their lack of specific knowledge. However, existing methods are struggling to effectively leverage chemical expertise and formulas. Moreover, current uncertainty estimation methods, designed to mitigate potential reasoning errors, are unable to precisely identify specific steps or key knowledge. In this work, we propose a novel framework called ChemAU, which incorporates our adaptive uncertainty estimation method that applies different uncertainty values based on the position of reasoning steps within the whole reasoning chain. Leveraging this method, ChemAU identifies gaps in chemistry knowledge and precisely supplements chemical expertise with the specialized domain model, thereby correcting and updating the previously flawed reasoning chain. Our experiments with three popular LLMs across three chemistry datasets demonstrate that ChemAU significantly enhances both reasoning accuracy and uncertainty estimation.

[Arxiv](https://arxiv.org/abs/2506.01116)