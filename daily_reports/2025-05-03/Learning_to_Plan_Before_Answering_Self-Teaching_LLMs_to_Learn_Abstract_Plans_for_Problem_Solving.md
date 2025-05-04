# # 在回答前学会规划：通过自我教学让大语言模型掌握抽象计划以解决难题
发布时间：2025年04月28日


> Learning to Plan Before Answering: Self-Teaching LLMs to Learn Abstract Plans for Problem Solving
>
> 在大型语言模型（LLM）的后训练领域，利用LLM自身生成的合成数据的有效性已得到充分验证。然而，一个关键问题仍未解决：这类自动生成的数据应包含哪些核心信息？现有方法仅生成逐步问题解决方案，却未能捕捉到实现类似问题泛化所需的抽象元知识。受认知科学启发，人类在深入细节前会运用高层次抽象来简化复杂问题，我们提出了一种新颖的自训练算法：LEPA（提前规划再回答学习）。LEPA训练LLM在接触问题复杂性之前先制定预期计划，这些计划作为解决问题的抽象元知识。这种方法不仅勾勒了解决方案生成的路径，还使LLM免受无关细节的干扰。在数据生成过程中，LEPA首先根据问题制定预期计划，然后生成与计划和问题相一致的解决方案。通过自我反思，LEPA不断完善计划，力求获得有助于产生正确解决方案的计划。在模型优化阶段，LLM被训练来预测经过优化的计划及其对应的解决方案。通过高效地提取和利用预期计划，LEPA在各种具有挑战性的自然语言推理基准测试中表现出显著优于传统算法的优势。
>
> https://arxiv.org/abs/2505.00031

**如遇无法添加，请+ vx: iamxxn886**
<hr />


<hr />

- 论文原文: [https://arxiv.org/abs/2505.00031](https://arxiv.org/abs/2505.00031)
- 获取更多最新Arxiv论文更新: [https://github.com/HuggingAGI/HuggingArxiv](https://github.com/HuggingAGI/HuggingArxiv)!
- 加入社群，+v: iamxxn886
- 点击公众号菜单加入讨论
![](https://raw.githubusercontent.com/HuggingAGI/wx_assets/main/2024/07/31/1722434818326-94339e92-22f1-4472-9d27-fed232f70b5d.jpeg)