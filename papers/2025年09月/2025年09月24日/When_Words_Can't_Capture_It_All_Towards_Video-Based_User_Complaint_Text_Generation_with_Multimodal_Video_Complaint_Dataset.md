# 当文字难以尽述时：面向基于视频的用户投诉文本生成——基于多模态视频投诉数据集

发布时间：2025年09月24日

`RAG` `零售与电商`

> When Words Can't Capture It All: Towards Video-Based User Complaint Text Generation with Multimodal Video Complaint Dataset

# 摘要

> 尽管可解释投诉挖掘领域已有不少探索，但如何通过文本或视频清晰传达用户诉求仍是一大难题，常导致问题得不到解决。用户往往难以用文字说清投诉内容，却能轻松上传展示产品问题的视频——比如用‘最差产品’这种模糊描述，搭配5秒视频展示右耳罩损坏的耳机。为此，本文在投诉挖掘领域提出一项新任务——‘视频投诉描述（CoD-V）’，旨在帮普通用户写出更有说服力的投诉内容（例如，帮上述用户明确表达右耳罩损坏的问题）。我们构建了ComVID视频投诉数据集，包含1175条投诉视频及对应描述，并标注了投诉者的情绪状态。此外，我们还提出‘投诉保留（CR）’评估指标，以区分CoD-V任务与传统视频摘要生成、描述任务的差异。为推进该研究，我们设计了嵌入多模态检索增强生成（RAG）的VideoLLaMA2-7b模型，能结合用户情绪生成投诉内容。我们采用METEOR、困惑度、Coleman-Liau可读性分数等多种主流评估指标，对多个视频语言模型（含预训练与微调版本）在多项任务上开展了全面评测。本研究为‘视频投诉表达平台’这一新方向奠定了基础，未来可让用户通过视频更便捷地反馈问题。相关数据集与资源已开源：https://github.com/sarmistha-D/CoD-V。

> While there exists a lot of work on explainable complaint mining, articulating user concerns through text or video remains a significant challenge, often leaving issues unresolved. Users frequently struggle to express their complaints clearly in text but can easily upload videos depicting product defects (e.g., vague text such as `worst product' paired with a 5-second video depicting a broken headphone with the right earcup). This paper formulates a new task in the field of complaint mining to aid the common users' need to write an expressive complaint, which is Complaint Description from Videos (CoD-V) (e.g., to help the above user articulate her complaint about the defective right earcup). To this end, we introduce ComVID, a video complaint dataset containing 1,175 complaint videos and the corresponding descriptions, also annotated with the emotional state of the complainer. Additionally, we present a new complaint retention (CR) evaluation metric that discriminates the proposed (CoD-V) task against standard video summary generation and description tasks. To strengthen this initiative, we introduce a multimodal Retrieval-Augmented Generation (RAG) embedded VideoLLaMA2-7b model, designed to generate complaints while accounting for the user's emotional state. We conduct a comprehensive evaluation of several Video Language Models on several tasks (pre-trained and fine-tuned versions) with a range of established evaluation metrics, including METEOR, perplexity, and the Coleman-Liau readability score, among others. Our study lays the foundation for a new research direction to provide a platform for users to express complaints through video. Dataset and resources are available at: https://github.com/sarmistha-D/CoD-V.

[Arxiv](https://arxiv.org/abs/2509.19952)