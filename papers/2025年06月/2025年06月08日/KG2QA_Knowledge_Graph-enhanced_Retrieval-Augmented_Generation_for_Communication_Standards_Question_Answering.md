# KG2QA：知识图谱增强的检索增强生成，面向通信标准问答

发布时间：2025年06月08日

`RAG` `问答系统`

> KG2QA: Knowledge Graph-enhanced Retrieval-Augmented Generation for Communication Standards Question Answering

# 摘要

> 通信领域的标准类型丰富多样。传统的咨询模式由于周期较长且依赖专家知识和经验，难以满足快速发展的技术需求。本文结合大型语言模型的微调与知识图谱的构建，实现通信标准领域的智能咨询问答系统。实验结果显示，在通信标准领域包含6,587个问答的数据集上进行LoRA微调后，Qwen2.5-7B-Instruct在测试集上展现出卓越的专业能力。BLEU-4从18.8564提升至66.8993，ROUGE等评估指标也显著提升，优于对比模型Llama-3-8B-Instruct的微调效果。基于包含6个实体属性和10个关系属性的本体框架，构建了包含13,906个实体和13,524个关系的通信标准领域知识图谱，查询准确率表现良好。智能咨询问答系统使服务端微调后的模型能够访问本地知识图谱，首先进行关键信息的图谱检索，有助于提升问答效果。在测试集上使用DeepSeek作为Judge进行评估，结果显示我们的RAG框架使微调后的模型在五个角度的评分均有所提升，平均分提升2.26%。并且结合WebService和API接口，在交互体验和后端接入方面取得了非常好的效果，具有非常好的实际应用价值。

> There are many types of standards in the field of communication. The traditional consulting model has a long cycle and relies on the knowledge and experience of experts, making it difficult to meet the rapidly developing technological demands. This paper combines the fine-tuning of large language models with the construction of knowledge graphs to implement an intelligent consultation and question-answering system for communication standards. The experimental results show that after LoRA tuning on the constructed dataset of 6,587 questions and answers in the field of communication standards, Qwen2.5-7B-Instruct demonstrates outstanding professional capabilities in the field of communication standards on the test set. BLEU-4 rose from 18.8564 to 66.8993, and evaluation indicators such as ROUGE also increased significantly, outperforming the fine-tuning effect of the comparison model Llama-3-8B-Instruct. Based on the ontology framework containing 6 entity attributes and 10 relation attributes, a knowledge graph of the communication standard domain containing 13,906 entities and 13,524 relations was constructed, showing a relatively good query accuracy rate. The intelligent consultation and question-answering system enables the fine-tuned model on the server side to access the locally constructed knowledge graph and conduct graphical retrieval of key information first, which is conducive to improving the question-answering effect. The evaluation using DeepSeek as the Judge on the test set shows that our RAG framework enables the fine-tuned model to improve the scores at all five angles, with an average score increase of 2.26%. And combined with web services and API interfaces, it has achieved very good results in terms of interaction experience and back-end access, and has very good practical application value.

[Arxiv](https://arxiv.org/abs/2506.07037)