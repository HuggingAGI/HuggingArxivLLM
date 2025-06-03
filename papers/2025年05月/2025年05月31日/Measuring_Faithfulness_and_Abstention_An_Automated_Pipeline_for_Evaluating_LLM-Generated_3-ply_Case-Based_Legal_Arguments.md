# 衡量忠实性与弃权：一个评估LLM生成三重案例法律论点的自动化流程

发布时间：2025年05月31日

`LLM应用`

> Measuring Faithfulness and Abstention: An Automated Pipeline for Evaluating LLM-Generated 3-ply Case-Based Legal Arguments

# 摘要

> 大型语言模型（LLMs）在复杂法律任务，如论证生成方面展现出潜力，然而它们的可靠性仍是一个问题。本文基于前期工作，介绍了一个自动化评估管道，用于研究LLMs生成三段式法律论证的能力，重点关注忠实度、因素利用和适当弃用。我们定义幻觉为生成输入材料中不存在的因素，弃用则指模型在无事实依据时停止生成论点的能力。我们的方法通过外部LLM提取论点中的因素，并与输入案例中的真实因素进行对比。我们对八种LLMs进行了三项测试：1）生成标准三段式论点；2）生成具有互换先例角色的论点；3）识别无法生成论点并停止生成。结果显示，LLMs在避免幻觉方面表现优异（超过90%），但未能充分利用所有相关因素。在弃用测试中，大多数模型未能遵循指示，生成了无意义的论点。这一自动化管道为评估LLM行为提供了一种可扩展的方法，强调了改进因素利用和弃用能力的重要性。项目页面：https://github.com/lizhang-AIandLaw/Measuring-Faithfulness-and-Abstention.

> Large Language Models (LLMs) demonstrate potential in complex legal tasks like argument generation, yet their reliability remains a concern. Building upon pilot work assessing LLM generation of 3-ply legal arguments using human evaluation, this paper introduces an automated pipeline to evaluate LLM performance on this task, specifically focusing on faithfulness (absence of hallucination), factor utilization, and appropriate abstention. We define hallucination as the generation of factors not present in the input case materials and abstention as the model's ability to refrain from generating arguments when instructed and no factual basis exists. Our automated method employs an external LLM to extract factors from generated arguments and compares them against the ground-truth factors provided in the input case triples (current case and two precedent cases). We evaluated eight distinct LLMs on three tests of increasing difficulty: 1) generating a standard 3-ply argument, 2) generating an argument with swapped precedent roles, and 3) recognizing the impossibility of argument generation due to lack of shared factors and abstaining. Our findings indicate that while current LLMs achieve high accuracy (over 90%) in avoiding hallucination on viable argument generation tests (Tests 1 & 2), they often fail to utilize the full set of relevant factors present in the cases. Critically, on the abstention test (Test 3), most models failed to follow instructions to stop, instead generating spurious arguments despite the lack of common factors. This automated pipeline provides a scalable method for assessing these crucial LLM behaviors, highlighting the need for improvements in factor utilization and robust abstention capabilities before reliable deployment in legal settings. Project page: https://github.com/lizhang-AIandLaw/Measuring-Faithfulness-and-Abstention.

[Arxiv](https://arxiv.org/abs/2506.00694)