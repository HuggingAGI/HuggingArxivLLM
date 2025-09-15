# SI-FACT：基于自改进忠实度感知对比调优的知识冲突缓解方法

发布时间：2025年09月12日

`LLM应用` `基础理论`

> SI-FACT: Mitigating Knowledge Conflict via Self-Improving Faithfulness-Aware Contrastive Tuning

# 摘要

> 在知识密集型任务中，大型语言模型常因知识冲突生成不忠实响应——它们更倾向依赖内部参数化知识，而非给定上下文。为此，我们提出全新自改进框架：自改进忠实性感知对比调优（SI-FACT）。该框架借助自指令机制，让基础LLM自动生成高质量结构化对比学习数据，包括锚样本、语义等效正样本及模拟不忠实场景的负样本，大幅减少人工标注成本。接着通过对比学习训练模型，使忠实响应在表示空间中彼此靠近，不忠实响应则相距更远。在知识冲突评估基准ECARE-KRE和COSE-KRE上的实验显示：基于Llama3-8B-Instruct的SI-FACT模型，上下文召回率较最佳基线方法提升6.2%，同时显著降低对内部记忆的依赖。这表明SI-FACT在增强LLM上下文忠实性方面高效且数据利用率高，为构建更主动可信的语言模型提供了实用方案。

> Large Language Models often generate unfaithful responses in knowledge intensive tasks due to knowledge conflict,that is,a preference for relying on internal parametric knowledge rather than the provided context.To address this issue,we propose a novel self improving framework,Self Improving Faithfulness Aware Contrastive Tuning.The framework uses a self instruct mechanism that allows the base LLM to automatically generate high quality,structured contrastive learning data,including anchor samples,semantically equivalent positive samples,and negative samples simulating unfaithful scenarios.This approach significantly reduces the cost of manual annotation.Subsequently,contrastive learning is applied to train the model,enabling it to pull faithful responses closer and push unfaithful responses farther apart in the representation space.Experiments on knowledge conflict evaluation benchmarks ECARE KRE and COSE KRE show that the SI FACT model based on Llama3 8B Instruct improves the Contextual Recall Rate by 6.2% over the best baseline method,while significantly reducing dependence on internal memory.The results indicate that SI FACT provides strong effectiveness and high data efficiency in enhancing the contextual faithfulness of LLMs,offering a practical pathway toward building more proactive and trustworthy language models.

[Arxiv](https://arxiv.org/abs/2509.10208)