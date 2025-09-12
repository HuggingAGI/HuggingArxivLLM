# 探究预训练语言模型在代码变更上的表现：ReDef高置信度即时缺陷预测数据集的启示

发布时间：2025年09月11日

`LLM应用` `工业与制造`

> Probing Pre-trained Language Models on Code Changes: Insights from ReDef, a High-Confidence Just-in-Time Defect Prediction Dataset

# 摘要

> 即时软件缺陷预测（JIT-SDP）在代码审查和持续集成中对风险代码变更的优先级排序至关重要。然而，现有数据集在识别致错提交时普遍存在标签噪声大、精度低的问题。为此，我们提出ReDef（基于回滚的缺陷数据集）——一个从22个大规模C/C++项目中精心构建的函数级修改高置信度基准。缺陷案例以回滚提交为依据，干净案例则通过事后历史核查验证；模糊实例通过GPT辅助的多轮投票与审核分类流程进行保守过滤。该流程最终得到3164个缺陷修改和10268个干净修改，标签可靠性远超现有资源。除构建数据集外，我们首次系统评估了预训练语言模型（PLMs）对代码修改的推理机制——具体包括哪种输入编码能最有效揭示变更信息，以及模型是否真正捕捉到编辑语义。我们在五种编码策略下微调了CodeBERT、CodeT5+和UniXcoder，并通过反事实扰动（交换新增/删除代码块、反转差异极性或注入虚假标记）进一步探究模型的敏感性。结果显示，在所有PLM中，紧凑差异风格编码始终优于全函数格式，统计测试证实了这一不受模型影响的显著效果。但在反事实测试中，模型性能几乎未受影响——这揭示了看似稳健的表现实则源于对表面线索的依赖，而非真正的语义理解。这些发现表明，与基于快照的任务不同，当前PLM在真正理解代码修改方面能力仍有局限。

> Just-in-Time software defect prediction (JIT-SDP) plays a critical role in prioritizing risky code changes during code review and continuous integration. However, existing datasets often suffer from noisy labels and low precision in identifying bug-inducing commits. To address this, we present ReDef (Revert-based Defect dataset), a high-confidence benchmark of function-level modifications curated from 22 large-scale C/C++ projects. Defective cases are anchored by revert commits, while clean cases are validated through post-hoc history checks. Ambiguous instances are conservatively filtered out via a GPT-assisted triage process involving multiple votes and audits. This pipeline yields 3,164 defective and 10,268 clean modifications, offering substantially more reliable labels than prior existing resources. Beyond dataset construction, we provide the first systematic evaluation of how pre-trained language models (PLMs) reason about code modifications -- specifically, which input encodings most effectively expose change information, and whether models genuinely capture edit semantics. We fine-tune CodeBERT, CodeT5+, and UniXcoder under five encoding strategies, and further probe their sensitivity through counterfactual perturbations that swap added/deleted blocks, invert diff polarity, or inject spurious markers. Our results show that compact diff-style encodings consistently outperform whole-function formats across all PLMs, with statistical tests confirming large, model-independent effects. However, under counterfactual tests, performance degrades little or not at all -- revealing that what appears to be robustness in fact reflects reliance on superficial cues rather than true semantic understanding. These findings indicate that, unlike in snapshot-based tasks, current PLMs remain limited in their ability to genuinely comprehend code modifications.

[Arxiv](https://arxiv.org/abs/2509.09192)