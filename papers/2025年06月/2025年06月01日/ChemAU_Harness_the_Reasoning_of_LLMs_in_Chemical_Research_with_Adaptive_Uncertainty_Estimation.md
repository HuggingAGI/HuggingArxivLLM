# # ChemAU: 驾驭大型语言模型在化学研究中的推理能力，融入自适应不确定性估计

发布时间：2025年06月01日

`LLM应用`

> ChemAU: Harness the Reasoning of LLMs in Chemical Research with Adaptive Uncertainty Estimation

# 摘要

> 大型语言模型（LLMs）凭借其强大的推理能力和自然语言理解，在众多领域中得到了广泛应用。然而，尽管LLMs在数学和编码任务中表现出色，但在化学相关问题上的效果却不尽如人意。化学问题通常涉及长而复杂的推理过程，其中包含大量专业术语、符号系统和复杂的命名法惯例。这些特点使得通用LLMs在缺乏特定领域知识的情况下，常常在推理过程中产生幻觉。目前，现有方法在有效利用化学专业知识和公式方面仍存在困难。此外，尽管现有的不确定性估计方法旨在缓解推理错误，但它们无法精确识别具体步骤或关键知识。针对这一问题，我们提出了一种名为ChemAU的新框架。该框架采用了我们的自适应不确定性估计方法，能够根据推理步骤在整个推理链中的位置，灵活调整不确定性值。通过这种方法，ChemAU能够识别化学知识中的空白，并借助专用领域模型，精准补充化学专业知识，从而纠正并更新先前有缺陷的推理链。我们在三个化学数据集上对三个流行的LLMs进行了实验，结果表明，ChemAU显著提升了推理准确性和不确定性估计效果。

> Large Language Models (LLMs) are widely used across various scenarios due to their exceptional reasoning capabilities and natural language understanding. While LLMs demonstrate strong performance in tasks involving mathematics and coding, their effectiveness diminishes significantly when applied to chemistry-related problems. Chemistry problems typically involve long and complex reasoning steps, which contain specific terminology, including specialized symbol systems and complex nomenclature conventions. These characteristics often cause general LLMs to experience hallucinations during the reasoning process due to their lack of specific knowledge. However, existing methods are struggling to effectively leverage chemical expertise and formulas. Moreover, current uncertainty estimation methods, designed to mitigate potential reasoning errors, are unable to precisely identify specific steps or key knowledge. In this work, we propose a novel framework called ChemAU, which incorporates our adaptive uncertainty estimation method that applies different uncertainty values based on the position of reasoning steps within the whole reasoning chain. Leveraging this method, ChemAU identifies gaps in chemistry knowledge and precisely supplements chemical expertise with the specialized domain model, thereby correcting and updating the previously flawed reasoning chain. Our experiments with three popular LLMs across three chemistry datasets demonstrate that ChemAU significantly enhances both reasoning accuracy and uncertainty estimation.

[Arxiv](https://arxiv.org/abs/2506.01116)