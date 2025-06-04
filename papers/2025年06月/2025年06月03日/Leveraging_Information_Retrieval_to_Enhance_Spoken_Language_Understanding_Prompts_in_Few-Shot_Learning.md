# 借助信息检索提升少样本学习中的口语理解能力

发布时间：2025年06月03日

`LLM应用` `智能服务` `家庭自动化`

> Leveraging Information Retrieval to Enhance Spoken Language Understanding Prompts in Few-Shot Learning

# 摘要

> 口语语言理解（SLU）在家庭助手、预订系统和推荐系统等应用中至关重要，因为它直接影响系统的可靠性。当前最先进的SLU技术虽然依赖大量数据，但在特定任务或语言上却面临标注数据匮乏的挑战。

幸运的是，指令微调的大型语言模型（LLMs）在少量样本下表现优异，尤其是在适当提示的情况下。本研究创新性地提出利用信息检索（IR）方法进行示例选择，构建增强的提示，应用于SLU任务。通过在多个基准测试中的验证，我们发现基于词汇的IR方法不仅显著提升了性能，还保持了提示的简洁性。

> Understanding user queries is fundamental in many applications, such as home assistants, booking systems, or recommendations. Accordingly, it is crucial to develop accurate Spoken Language Understanding (SLU) approaches to ensure the reliability of the considered system. Current State-of-the-Art SLU techniques rely on large amounts of training data; however, only limited annotated examples are available for specific tasks or languages.
  In the meantime, instruction-tuned large language models (LLMs) have shown exceptional performance on unseen tasks in a few-shot setting when provided with adequate prompts. In this work, we propose to explore example selection by leveraging Information retrieval (IR) approaches to build an enhanced prompt that is applied to an SLU task. We evaluate the effectiveness of the proposed method on several SLU benchmarks. Experimental results show that lexical IR methods significantly enhance performance without increasing prompt length.

[Arxiv](https://arxiv.org/abs/2506.03035)