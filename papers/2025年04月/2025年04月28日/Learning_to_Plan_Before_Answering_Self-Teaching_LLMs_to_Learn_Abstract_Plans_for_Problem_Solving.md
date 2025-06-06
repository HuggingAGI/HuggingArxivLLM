# # 在回答前学会规划：通过自我教学让大语言模型掌握抽象计划以解决难题

发布时间：2025年04月28日

`LLM理论` `人工智能`

> Learning to Plan Before Answering: Self-Teaching LLMs to Learn Abstract Plans for Problem Solving

# 摘要

> 在大型语言模型（LLM）的后训练领域，利用LLM自身生成的合成数据的有效性已得到充分验证。然而，一个关键问题仍未解决：这类自动生成的数据应包含哪些核心信息？现有方法仅生成逐步问题解决方案，却未能捕捉到实现类似问题泛化所需的抽象元知识。受认知科学启发，人类在深入细节前会运用高层次抽象来简化复杂问题，我们提出了一种新颖的自训练算法：LEPA（提前规划再回答学习）。LEPA训练LLM在接触问题复杂性之前先制定预期计划，这些计划作为解决问题的抽象元知识。这种方法不仅勾勒了解决方案生成的路径，还使LLM免受无关细节的干扰。在数据生成过程中，LEPA首先根据问题制定预期计划，然后生成与计划和问题相一致的解决方案。通过自我反思，LEPA不断完善计划，力求获得有助于产生正确解决方案的计划。在模型优化阶段，LLM被训练来预测经过优化的计划及其对应的解决方案。通过高效地提取和利用预期计划，LEPA在各种具有挑战性的自然语言推理基准测试中表现出显著优于传统算法的优势。

> In the field of large language model (LLM) post-training, the effectiveness of utilizing synthetic data generated by the LLM itself has been well-presented. However, a key question remains unaddressed: what essential information should such self-generated data encapsulate? Existing approaches only produce step-by-step problem solutions, and fail to capture the abstract meta-knowledge necessary for generalization across similar problems. Drawing insights from cognitive science, where humans employ high-level abstraction to simplify complex problems before delving into specifics, we introduce a novel self-training algorithm: LEarning to Plan before Answering (LEPA). LEPA trains the LLM to formulate anticipatory plans, which serve as abstract meta-knowledge for problem-solving, before engaging with the intricacies of problems. This approach not only outlines the solution generation path but also shields the LLM from the distraction of irrelevant details. During data generation, LEPA first crafts an anticipatory plan based on the problem, and then generates a solution that aligns with both the plan and the problem. LEPA refines the plan through self-reflection, aiming to acquire plans that are instrumental in yielding correct solutions. During model optimization, the LLM is trained to predict both the refined plans and the corresponding solutions. By efficiently extracting and utilizing the anticipatory plans, LEPA demonstrates remarkable superiority over conventional algorithms on various challenging natural language reasoning benchmarks.

[Arxiv](https://arxiv.org/abs/2505.00031)