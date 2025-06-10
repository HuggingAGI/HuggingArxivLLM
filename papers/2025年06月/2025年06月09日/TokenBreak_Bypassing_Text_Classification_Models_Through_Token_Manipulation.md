# TokenBreak：利用令牌操作避开文本分类模型

发布时间：2025年06月09日

`LLM应用

理由：这篇论文探讨了针对大型语言模型（LLMs）的新型攻击方法TokenBreak，以及相关的防御策略。它直接涉及LLMs的安全性和防护机制，属于应用层面的研究。` `网络安全` `防御机制`

> TokenBreak: Bypassing Text Classification Models Through Token Manipulation

# 摘要

> 自然语言处理（NLP）模型用于文本分类与生成等任务。在处理输入数据时，模型首先会将人类可读的文本分词，转换为自身可理解的格式，从而实现推理与上下文理解。文本分类模型可用于防范针对大型语言模型（LLMs）的提示注入攻击、有毒输入及垃圾邮件等网络安全威胁。

本文介绍了一种新型攻击方法——TokenBreak。该攻击利用防护模型的分词策略，通过篡改输入文本，使某些模型输出错误分类结果。值得注意的是，攻击目标（LLM或邮件接收者）仍能理解并响应被篡改的文本，这意味着它们可能遭受本应被防护模型阻止的攻击。

分词器与模型架构紧密相关，因此可以根据模型家族判断其是否易受攻击。此外，我们还提出了一种防御策略，作为额外保护层，无需重新训练防御模型即可实施。

> Natural Language Processing (NLP) models are used for text-related tasks such as classification and generation. To complete these tasks, input data is first tokenized from human-readable text into a format the model can understand, enabling it to make inferences and understand context. Text classification models can be implemented to guard against threats such as prompt injection attacks against Large Language Models (LLMs), toxic input and cybersecurity risks such as spam emails. In this paper, we introduce TokenBreak: a novel attack that can bypass these protection models by taking advantage of the tokenization strategy they use. This attack technique manipulates input text in such a way that certain models give an incorrect classification. Importantly, the end target (LLM or email recipient) can still understand and respond to the manipulated text and therefore be vulnerable to the very attack the protection model was put in place to prevent. The tokenizer is tied to model architecture, meaning it is possible to predict whether or not a model is vulnerable to attack based on family. We also present a defensive strategy as an added layer of protection that can be implemented without having to retrain the defensive model.

[Arxiv](https://arxiv.org/abs/2506.07948)