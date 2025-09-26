# 以学提问促学总结：长文档摘要的对抗性智能体协同

发布时间：2025年09月25日

`Agent` `基础理论`

> Learning to Summarize by Learning to Quiz: Adversarial Agentic Collaboration for Long Document Summarization

# 摘要

> 长文档摘要仍是当前大型语言模型（LLMs）面临的一大难题——现有方法在处理超长文档时往往存在信息丢失、事实矛盾和连贯性不足等问题。为此，我们提出了SummQ——一种新颖的对抗性多智能体框架，它通过摘要与问答两个互补领域中专业智能体的协作智能来克服这些局限。该方法中，摘要生成器与评审器协同工作，生成并评估全面摘要；问答生成器与评审器则创建理解性问题，为摘要过程提供持续质量检验。这一对抗性动态还引入了考生智能体——它验证生成的摘要是否包含回答问答问题所需的信息，进而通过多维度反馈机制实现迭代优化。我们在三个主流长文档摘要基准数据集上对SummQ进行了评估。实验结果显示，该框架在ROUGE、BERTScore指标，以及LLM评判和人工评估中均显著优于现有最先进方法。综合分析进一步揭示了多智能体协作动态的有效性、不同智能体配置的影响，以及问答机制的作用。这项研究为长文档摘要开辟了新路径——通过对抗性智能体协作提升摘要质量。

> Long document summarization remains a significant challenge for current large language models (LLMs), as existing approaches commonly struggle with information loss, factual inconsistencies, and coherence issues when processing excessively long documents. We propose SummQ, a novel adversarial multi-agent framework that addresses these limitations through collaborative intelligence between specialized agents operating in two complementary domains: summarization and quizzing. Our approach employs summary generators and reviewers that work collaboratively to create and evaluate comprehensive summaries, while quiz generators and reviewers create comprehension questions that serve as continuous quality checks for the summarization process. This adversarial dynamic, enhanced by an examinee agent that validates whether the generated summary contains the information needed to answer the quiz questions, enables iterative refinement through multifaceted feedback mechanisms. We evaluate SummQ on three widely used long document summarization benchmarks. Experimental results demonstrate that our framework significantly outperforms existing state-of-the-art methods across ROUGE and BERTScore metrics, as well as in LLM-as-a-Judge and human evaluations. Our comprehensive analyses reveal the effectiveness of the multi-agent collaboration dynamics, the influence of different agent configurations, and the impact of the quizzing mechanism. This work establishes a new approach for long document summarization that uses adversarial agentic collaboration to improve summarization quality.

[Arxiv](https://arxiv.org/abs/2509.20900)