# **未雨绸缪：金融领域的长上下文问答解决方案**

发布时间：2025年02月10日

`LLM应用` `问答系统`

> Expect the Unexpected: FailSafe Long Context QA for Finance

# 摘要

> 我们提出了一种新的长上下文金融基准测试——FailSafeQA，旨在评估LLMs在基于LLM的问答系统中面对六种人机交互变化时的稳健性和上下文感知能力。我们专注于两个案例研究：查询失败和上下文失败。在查询失败场景中，我们改变原始查询的领域专业知识、完整性和语言准确性。在上下文失败案例中，我们模拟上传降级、不相关和空白文档。我们采用LLM-as-a-Judge方法，使用Qwen2.5-72B-Instruct，并采用精细的评分标准，为24个现成模型定义和计算稳健性、上下文定位和合规性分数。结果表明，尽管某些模型在缓解输入扰动方面表现出色，但它们需要在稳健回答与避免幻觉之间取得平衡。值得注意的是，被公认为最合规的模型Palmyra-Fin-128k-Instruct保持了强大的基线性能，但在17%的测试案例中难以维持稳健预测。另一方面，最稳健的模型OpenAI o3-mini在41%的测试案例中编造了信息。结果表明，即使高性能模型也有显著改进空间，并凸显了FailSafeQA作为开发适用于金融应用的可靠LLMs工具的作用。数据集可在以下链接获取：https://huggingface.co/datasets/Writer/FailSafeQA

> We propose a new long-context financial benchmark, FailSafeQA, designed to test the robustness and context-awareness of LLMs against six variations in human-interface interactions in LLM-based query-answer systems within finance. We concentrate on two case studies: Query Failure and Context Failure. In the Query Failure scenario, we perturb the original query to vary in domain expertise, completeness, and linguistic accuracy. In the Context Failure case, we simulate the uploads of degraded, irrelevant, and empty documents. We employ the LLM-as-a-Judge methodology with Qwen2.5-72B-Instruct and use fine-grained rating criteria to define and calculate Robustness, Context Grounding, and Compliance scores for 24 off-the-shelf models. The results suggest that although some models excel at mitigating input perturbations, they must balance robust answering with the ability to refrain from hallucinating. Notably, Palmyra-Fin-128k-Instruct, recognized as the most compliant model, maintained strong baseline performance but encountered challenges in sustaining robust predictions in 17% of test cases. On the other hand, the most robust model, OpenAI o3-mini, fabricated information in 41% of tested cases. The results demonstrate that even high-performing models have significant room for improvement and highlight the role of FailSafeQA as a tool for developing LLMs optimized for dependability in financial applications. The dataset is available at: https://huggingface.co/datasets/Writer/FailSafeQA

[Arxiv](https://arxiv.org/abs/2502.06329)