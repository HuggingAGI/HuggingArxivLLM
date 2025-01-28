# LemmaHead: 基于大型语言模型的RAG辅助证明生成

发布时间：2025年01月27日

`RAG

理由：该论文摘要提到使用检索增强生成（RAG）来弥补大型语言模型（LLM）在数学推理中的不足，并开发了一个名为LemmaHead的RAG知识库。这表明该研究的核心是使用RAG技术来增强LLM的能力，因此应归类为RAG。` `自动化定理证明`

> LemmaHead: RAG Assisted Proof Generation Using Large Language Models

# 摘要

> # 摘要
为LLMs开发解决数学问题或撰写数学证明所需的逻辑是一个颇具挑战的目标。目前，主流方法是通过在学术出版物和教科书等数学内容上微调模型，使其模仿数学写作风格。在本项目中，我们探索了使用检索增强生成（RAG）来弥补LLMs在数学推理中的不足。我们开发了LemmaHead，这是一个RAG知识库，通过提供相关数学上下文（尤其是教科书内容）来增强模型的查询能力。为了评估模型在数学推理中的表现，我们的测试重点是通过生成Lean形式语言中的数学证明来自动化定理证明。

> Developing the logic necessary to solve mathematical problems or write mathematical proofs is one of the more difficult objectives for large language models (LLMS). Currently, the most popular methods in literature consists of fine-tuning the model on written mathematical content such as academic publications and textbooks, so that the model can learn to emulate the style of mathematical writing. In this project, we explore the effectiveness of using retrieval augmented generation (RAG) to address gaps in the mathematical reasoning of LLMs. We develop LemmaHead, a RAG knowledge base that supplements queries to the model with relevant mathematical context, with particular focus on context from published textbooks. To measure our model's performance in mathematical reasoning, our testing paradigm focuses on the task of automated theorem proving via generating proofs to a given mathematical claim in the Lean formal language.

[Arxiv](https://arxiv.org/abs/2501.15797)