# 需求明确的跟进问题生成

发布时间：2025年07月03日

`LLM应用` `软件工程` `人工智能`

> Requirements Elicitation Follow-Up Question Generation

# 摘要

> 访谈是需求elicitation中常用的手段，旨在收集软件系统利益相关者的需求、偏好和期望。然而，有效访谈需要访谈者在面对领域不熟、认知过载和信息过载等多重挑战时，实时制定恰当问题。近期，大型语言模型（LLMs）在文本摘要和蕴含等任务中表现卓越。为助力访谈者，我们基于常见访谈错误类型框架，研究了将GPT-4o应用于需求elicitation中生成后续问题的方法。同时，我们还探讨了根据受访者发言生成问题的技术。我们通过受控实验评估了LLM生成与人工编写问题的表现，结果表明：LLM生成的问题在清晰度、相关性和信息量上与人工编写问题持平。当以常见错误类型为指导时，LLM生成的问题表现更优。这表明，LLMs有望帮助访谈者实时提升需求访谈的质量和效率。

> Interviews are a widely used technique in eliciting requirements to gather stakeholder needs, preferences, and expectations for a software system. Effective interviewing requires skilled interviewers to formulate appropriate interview questions in real time while facing multiple challenges, including lack of familiarity with the domain, excessive cognitive load, and information overload that hinders how humans process stakeholders' speech. Recently, large language models (LLMs) have exhibited state-of-the-art performance in multiple natural language processing tasks, including text summarization and entailment. To support interviewers, we investigate the application of GPT-4o to generate follow-up interview questions during requirements elicitation by building on a framework of common interviewer mistake types. In addition, we describe methods to generate questions based on interviewee speech. We report a controlled experiment to evaluate LLM-generated and human-authored questions with minimal guidance, and a second controlled experiment to evaluate the LLM-generated questions when generation is guided by interviewer mistake types. Our findings demonstrate that, for both experiments, the LLM-generated questions are no worse than the human-authored questions with respect to clarity, relevancy, and informativeness. In addition, LLM-generated questions outperform human-authored questions when guided by common mistakes types. This highlights the potential of using LLMs to help interviewers improve the quality and ease of requirements elicitation interviews in real time.

[Arxiv](https://arxiv.org/abs/2507.02858)