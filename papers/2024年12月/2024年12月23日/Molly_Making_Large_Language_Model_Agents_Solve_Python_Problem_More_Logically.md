# 莫莉：助力大型语言模型代理更具逻辑性地解决 Python 问题

发布时间：2024年12月23日

`Agent` `计算机编程`

> Molly: Making Large Language Model Agents Solve Python Problem More Logically

# 摘要

> 将大型语言模型（LLMs）用作教学辅助，这在智能教育中，尤其是计算机课程里，备受关注。为缩小LLMs与计算机编程教育专家的差距，现有研究中的两大主流方法是微调与检索增强生成（RAG）。然而，针对特定任务的微调资源消耗大，还可能削弱模型的泛化能力。RAG在减少LLMs的幻觉方面表现不错，但在推理时生成不相关的事实内容，可能会让学习者感到十分困惑。为解决这些问题，我们推出了Molly代理，专注于处理学习者在学习Python编程语言时碰到的难题。我们的代理通过基于场景的交互，自动解析学习者的提问意图，从而能从构建的知识库中精准检索相关文档。在生成阶段，代理会对生成的回答进行反思，确保其既符合事实内容，又能有效回答用户的问题。在构建的中文Python问答数据集上进行的大量实验证明了Molly代理的有效性，表明其在为Python问题提供有用回答方面的性能有所提升。

> Applying large language models (LLMs) as teaching assists has attracted much attention as an integral part of intelligent education, particularly in computing courses. To reduce the gap between the LLMs and the computer programming education expert, fine-tuning and retrieval augmented generation (RAG) are the two mainstream methods in existing researches. However, fine-tuning for specific tasks is resource-intensive and may diminish the model`s generalization capabilities. RAG can perform well on reducing the illusion of LLMs, but the generation of irrelevant factual content during reasoning can cause significant confusion for learners. To address these problems, we introduce the Molly agent, focusing on solving the proposed problem encountered by learners when learning Python programming language. Our agent automatically parse the learners' questioning intent through a scenario-based interaction, enabling precise retrieval of relevant documents from the constructed knowledge base. At generation stage, the agent reflect on the generated responses to ensure that they not only align with factual content but also effectively answer the user's queries. Extensive experimentation on a constructed Chinese Python QA dataset shows the effectiveness of the Molly agent, indicating an enhancement in its performance for providing useful responses to Python questions.

[Arxiv](https://arxiv.org/abs/2412.18093)