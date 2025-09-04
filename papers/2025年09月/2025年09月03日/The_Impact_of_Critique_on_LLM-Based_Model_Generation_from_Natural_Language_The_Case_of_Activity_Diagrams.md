# 批判对基于LLM从自然语言生成模型的影响：以活动图为例

发布时间：2025年09月03日

`LLM应用` `基础理论`

> The Impact of Critique on LLM-Based Model Generation from Natural Language: The Case of Activity Diagrams

# 摘要

> 大型语言模型（LLMs）在从自然语言描述自动生成模型方面展现出巨大潜力。常用方法是迭代式的生成-批判-改进循环：先生成候选模型，再评估并根据发现的问题进行更新。此过程需解决两大核心问题：（1）结构正确性——符合格式规范；（2）语义对齐——准确反映源文本的真实意图。为此，我们提出LADEX（基于LLM的活动图提取器）——一个借助LLM驱动的批判-改进过程，从自然语言流程描述中提取活动图的管道。LADEX的结构检查可通过算法或LLM完成，而对齐检查则始终由LLM执行。我们设计了LADEX的五个消融变体，旨在研究：（i）批判-改进循环本身的影响；（ii）基于LLM的语义检查的作用；（iii）算法结构检查与LLM结构检查的效果对比。
  为评估LADEX，我们利用基于跟踪的操作语义，将生成的活动图与专家构建的真值进行对比，从而实现正确性和完整性的自动化度量。两个数据集上的实验结果表明：（1）相比单次生成，批判-改进循环能提升结构有效性、正确性和完整性；（2）算法结构检查可消除LLM检查无法发现的不一致性，较纯LLM检查平均提升17.81%的正确性和13.24%的完整性；（3）将算法结构检查与基于LLM的语义检查相结合（通过注重推理的O4 Mini实现），可达到最佳整体性能——平均正确性高达86.37%、完整性达88.56%，且平均仅需不到五次LLM调用。

> Large Language Models (LLMs) show strong potential for automating the generation of models from natural-language descriptions. A common approach is an iterative generate-critique-refine loop, where candidate models are produced, evaluated, and updated based on detected issues. This process needs to address: (1) structural correctness - compliance with well-formedness rules - and (2) semantic alignment - accurate reflection of the intended meaning in the source text. We present LADEX (LLM-based Activity Diagram Extractor), a pipeline for deriving activity diagrams from natural-language process descriptions using an LLM-driven critique-refine process. Structural checks in LADEX can be performed either algorithmically or by an LLM, while alignment checks are always performed by an LLM. We design five ablated variants of LADEX to study: (i) the impact of the critique-refine loop itself, (ii) the role of LLM-based semantic checks, and (iii) the comparative effectiveness of algorithmic versus LLM-based structural checks.
  To evaluate LADEX, we compare the generated activity diagrams with expert-created ground truths using trace-based operational semantics. This enables automated measurement of correctness and completeness. Experiments on two datasets indicate that: (1) the critique-refine loop improves structural validity, correctness, and completeness compared to single-pass generation; (2) algorithmic structural checks eliminate inconsistencies that LLM-based checks fail to detect, improving correctness by an average of 17.81% and completeness by 13.24% over LLM-only checks; and (3) combining algorithmic structural checks with LLM-based semantic checks, implemented using the reasoning-focused O4 Mini, achieves the best overall performance - yielding average correctness of up to 86.37% and average completeness of up to 88.56% - while requiring fewer than five LLM calls on average.

[Arxiv](https://arxiv.org/abs/2509.03463)