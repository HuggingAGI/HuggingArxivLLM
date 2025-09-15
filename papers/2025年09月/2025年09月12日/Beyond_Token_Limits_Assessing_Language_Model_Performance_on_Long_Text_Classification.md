# # 突破令牌限制：评估语言模型在长文本分类上的性能

发布时间：2025年09月12日

`LLM应用` `法律科技`

> Beyond Token Limits: Assessing Language Model Performance on Long Text Classification

# 摘要

> 社会科学中最常用的大型语言模型（如BERT及其衍生模型RoBERTa等）在输入文本长度上存在限制，这直接影响其预测生成能力。对于需处理长文本的分类任务而言，这一限制尤为棘手——例如法律及法案草案领域，文本常长达数百页，仅能处理512个标记的模型对此难以胜任。本文针对比较议程项目（其编码手册涵盖教育至医疗保健等21个政策主题标签）的多类分类任务，使用XLM-RoBERTa、Longformer、GPT-3.5及GPT-4模型在5种语言上开展实验。结果显示：专为长文本设计的Longformer模型未显优势；而GPT变体与最优开放模型相比，后者更胜一筹。进一步的类别级因素分析表明，在长文本分类中，特定类别间的支持与内容重叠程度对性能至关重要。

> The most widely used large language models in the social sciences (such as BERT, and its derivatives, e.g. RoBERTa) have a limitation on the input text length that they can process to produce predictions. This is a particularly pressing issue for some classification tasks, where the aim is to handle long input texts. One such area deals with laws and draft laws (bills), which can have a length of multiple hundred pages and, therefore, are not particularly amenable for processing with models that can only handle e.g. 512 tokens. In this paper, we show results from experiments covering 5 languages with XLM-RoBERTa, Longformer, GPT-3.5, GPT-4 models for the multiclass classification task of the Comparative Agendas Project, which has a codebook of 21 policy topic labels from education to health care. Results show no particular advantage for the Longformer model, pre-trained specifically for the purposes of handling long inputs. The comparison between the GPT variants and the best-performing open model yielded an edge for the latter. An analysis of class-level factors points to the importance of support and substance overlaps between specific categories when it comes to performance on long text inputs.

[Arxiv](https://arxiv.org/abs/2509.10199)