# 基于日志增强的检索增强生成（RAG）实现学生与智能体互动的个性化

发布时间：2025年05月22日

`RAG`

> Personalizing Student-Agent Interactions Using Log-Contextualized Retrieval Augmented Generation (RAG)

# 摘要

> 协作对话为了解学生的批判性思维和学习过程提供了丰富见解，这对STEM+C教育环境中适配教学智能体以提升学生学习与问题解决能力至关重要。尽管大型语言模型（LLMs）能够支持动态教学互动，但潜在的幻觉问题可能影响学生对系统信任度和教学效果。检索增强生成（RAG）通过将LLM输出与精选知识库结合，为对话提供了坚实基础，但其效果依赖于用户输入与知识库之间清晰的语义关联，在学生对话中这种关联往往较为薄弱。我们提出了一种日志上下文化检索增强生成（LC-RAG），通过整合环境日志来为协作对话提供上下文支持，从而提升RAG的检索能力。我们的研究结果表明，LC-RAG相较于仅基于对话的基线模型，显著提升了检索效果，并使协作同伴智能体Copa能够在一个协作计算建模环境中提供相关且个性化的指导，从而支持学生的批判性思维和知识决策能力。

> Collaborative dialogue offers rich insights into students' learning and critical thinking. This is essential for adapting pedagogical agents to students' learning and problem-solving skills in STEM+C settings. While large language models (LLMs) facilitate dynamic pedagogical interactions, potential hallucinations can undermine confidence, trust, and instructional value. Retrieval-augmented generation (RAG) grounds LLM outputs in curated knowledge, but its effectiveness depends on clear semantic links between user input and a knowledge base, which are often weak in student dialogue. We propose log-contextualized RAG (LC-RAG), which enhances RAG retrieval by incorporating environment logs to contextualize collaborative discourse. Our findings show that LC-RAG improves retrieval over a discourse-only baseline and allows our collaborative peer agent, Copa, to deliver relevant, personalized guidance that supports students' critical thinking and epistemic decision-making in a collaborative computational modeling environment, XYZ.

[Arxiv](https://arxiv.org/abs/2505.17238)