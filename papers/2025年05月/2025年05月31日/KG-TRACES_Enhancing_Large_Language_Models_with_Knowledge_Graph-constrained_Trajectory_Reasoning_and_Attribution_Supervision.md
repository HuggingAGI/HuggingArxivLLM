# KG-TRACES：通过知识图谱约束的轨迹推理和归属监督提升大型语言模型性能

发布时间：2025年05月31日

`LLM理论` `知识图谱`

> KG-TRACES: Enhancing Large Language Models with Knowledge Graph-constrained Trajectory Reasoning and Attribution Supervision

# 摘要

> 大型语言模型（LLMs）在自然语言处理领域取得了显著进展，但在复杂推理任务中仍面临可解释性和可信度的挑战。为解决这一问题，我们提出了一种名为知识图谱约束的轨迹推理归因与链式解释监督框架（KG-TRACES）。该框架通过显式监督推理路径和过程，显著增强了LLMs的推理能力。具体而言，KG-TRACES从三方面对模型进行监督：（1）预测符号关系路径，（2）预测完整的三元组级推理路径，（3）生成基于推理路径的可归因推理过程。推理阶段，模型能灵活适应知识图谱可用或不可用的场景，从知识图谱中检索推理路径，或基于内在知识预测合理路径。这种设计使模型能够以可解释且可追溯来源的方式进行推理。实验结果表明，KG-TRACES显著超越现有最优方法：在WebQSP数据集上，Hits@1提升了1.6%，F1提升了4.7%；在CWQ数据集上，Hits@1提高了4.8%，F1提高了2.1%。此外，我们展示了其在医学等专业领域的迁移能力。通过可视化推理过程的中间步骤，我们进一步证明，KG-TRACES引入的显式监督使推理过程更加稳定且目标导向，与正确答案高度一致。代码已开源，地址为https://github.com/Edaizi/KG-TRACES。


> Large language models (LLMs) have made remarkable strides in various natural language processing tasks, but their performance on complex reasoning problems remains hindered by a lack of explainability and trustworthiness. This issue, often manifesting as hallucinations or unattributable reasoning processes, limits their applicability in complex reasoning scenarios. To address this, we propose Knowledge Graph-constrained Trajectory Reasoning Attribution and Chain Explanation Supervision (KG-TRACES), a novel framework that enhances the reasoning ability of LLMs through explicit supervision over reasoning paths and processes. KG-TRACES jointly supervises the model to: (1) predict symbolic relation paths, (2) predict full triple-level reasoning paths, and (3) generate attribution-aware reasoning processes grounded in the reasoning paths. At inference phase, the model adapts to both KG-available and KG-unavailable scenarios, retrieving reasoning paths from a KG when possible or predicting plausible reasoning paths with only intrinsic knowledge when not. This design enables the model to reason in an explainable and source-attributable pattern. Through extensive experiments on complex reasoning tasks, we demonstrate that KG-TRACES significantly outperforms existing SOTA: it improves Hits@1 by 1.6% and F1 by 4.7% on WebQSP, and achieves improvements of 4.8% in Hits@1 and 2.1% in F1 on CWQ. Moreover, we show its transferability to specialized domains such as medicine. By visualizing the intermediate steps of reasoning processes, we further show that the explicit supervision introduced by KG-TRACES leads to more stable and goal-directed reasoning processes, aligning closely with correct answers. Code is available at https://github.com/Edaizi/KG-TRACES.

[Arxiv](https://arxiv.org/abs/2506.00783)