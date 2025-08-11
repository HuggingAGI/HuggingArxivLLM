# 使用生成式AI自动生成与马来西亚中学数学课程相匹配的多项选择题

发布时间：2025年08月06日

`LLM应用` `生成式AI`

> Automated Generation of Curriculum-Aligned Multiple-Choice Questions for Malaysian Secondary Mathematics Using Generative AI

# 摘要

> 本文针对马来西亚教育体系中对可扩展且高质量教育评估工具的迫切需求展开研究。文章展现了生成式AI（GenAI）的潜力，同时承认在确保事实准确性与课程对齐性方面面临重大挑战，尤其是对于像马来语这样的低资源语言。本研究引入并比较了四种增量管道，用于使用OpenAI的GPT-4o生成初中一年级数学多选题（MCQs）的马来语版本。这些方法从非基于地面的提示（结构化和基础型）到检索增强生成（RAG）方法（一种使用LangChain框架，另一种手动实现）不等。该系统以官方课程文件为基础，包括教师准备的笔记和年度教学计划（RPT）。采用双重自动评估框架来评估生成的问题。课程对齐性通过与RPT的语义文本相似度（STS）进行衡量，而上下文有效性则通过一种新颖的RAG基础问答（RAG-QA）方法进行验证。结果显示，基于RAG的管道显著优于非基于地面的提示方法，生成的问题具有更高的课程对齐性和事实有效性。研究进一步分析了基于框架的RAG方法在实现简便性与手动管道提供的精细控制之间的权衡。本研究为在低资源语言中生成特定课程的教育内容提供了一种经过验证的方法论，引入了一种共生的RAG-QA评估技术，并为在马来西亚及类似地区开发和部署实用教育科技解决方案提供了可操作的见解。

> This paper addresses the critical need for scalable and high-quality educational assessment tools within the Malaysian education system. It highlights the potential of Generative AI (GenAI) while acknowledging the significant challenges of ensuring factual accuracy and curriculum alignment, especially for low-resource languages like Bahasa Melayu. This research introduces and compares four incremental pipelines for generating Form 1 Mathematics multiple-choice questions (MCQs) in Bahasa Melayu using OpenAI's GPT-4o. The methods range from non-grounded prompting (structured and basic) to Retrieval-Augmented Generation (RAG) approaches (one using the LangChain framework, one implemented manually). The system is grounded in official curriculum documents, including teacher-prepared notes and the yearly teaching plan (RPT). A dual-pronged automated evaluation framework is employed to assess the generated questions. Curriculum alignment is measured using Semantic Textual Similarity (STS) against the RPT, while contextual validity is verified through a novel RAG-based Question-Answering (RAG-QA) method. The results demonstrate that RAG-based pipelines significantly outperform non-grounded prompting methods, producing questions with higher curriculum alignment and factual validity. The study further analyzes the trade-offs between the ease of implementation of framework-based RAG and the fine-grained control offered by a manual pipeline. This work presents a validated methodology for generating curriculum-specific educational content in a low-resource language, introduces a symbiotic RAG-QA evaluation technique, and provides actionable insights for the development and deployment of practical EdTech solutions in Malaysia and similar regions.

[Arxiv](https://arxiv.org/abs/2508.04442)