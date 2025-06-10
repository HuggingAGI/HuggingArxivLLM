# ConfQA：自信时才作答

发布时间：2025年06月08日

`LLM应用` `信息检索` `问答系统`

> ConfQA: Answer Only If You Are Confident

# 摘要

> 我们能否教会大型语言模型（LLMs）避免虚构事实？本文提出了一种名为ConfQA的微调策略，该策略可将虚构率从20-40%降低到5%以下，适用于多个事实性基准测试。核心思想简单却有效：当模型正确回答问题时，继续给出答案；否则，承认'我不确定'。两个关键因素使训练效果显著。首先，我们引入了'仅在您确定时回答'的抑制提示，以明确引导模型行为，否则虚构率仍保持在15%-25%的高水平。其次，我们利用知识图谱中的属性值等简单事实陈述，帮助模型校准信心，从而实现在不同领域和问题类型上的稳健泛化。基于此，我们提出了双神经知识框架，该框架根据ConfQA的信心无缝选择内部参数化的神经知识或外部记录的符号知识。该框架不仅使潜在准确率提升至95%以上，还减少了30%以上的不必要的外部检索。

> Can we teach Large Language Models (LLMs) to refrain from hallucinating factual statements? In this paper we present a fine-tuning strategy that we call ConfQA, which can reduce hallucination rate from 20-40% to under 5% across multiple factuality benchmarks. The core idea is simple: when the LLM answers a question correctly, it is trained to continue with the answer; otherwise, it is trained to admit "I am unsure". But there are two key factors that make the training highly effective. First, we introduce a dampening prompt "answer only if you are confident" to explicitly guide the behavior, without which hallucination remains high as 15%-25%. Second, we leverage simple factual statements, specifically attribute values from knowledge graphs, to help LLMs calibrate the confidence, resulting in robust generalization across domains and question types. Building on this insight, we propose the Dual Neural Knowledge framework, which seamlessly select between internally parameterized neural knowledge and externally recorded symbolic knowledge based on ConfQA's confidence. The framework enables potential accuracy gains to beyond 95%, while reducing unnecessary external retrievals by over 30%.

[Arxiv](https://arxiv.org/abs/2506.07309)