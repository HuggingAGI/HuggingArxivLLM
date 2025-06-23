# 我们像治疗师一样与机器人交流，而它们能否相应地回应？人工智能情感支持中的语言对齐

发布时间：2025年06月19日

`Agent` `心理健康` `对话系统`

> Do We Talk to Robots Like Therapists, and Do They Respond Accordingly? Language Alignment in AI Emotional Support

# 摘要

> 随着对话式智能体越来越多地参与情感支持对话，理解它们的表现与传统治疗环境的相似性变得尤为重要。本研究探讨了与机器人分享的担忧是否与人类对人类（H2H）治疗 session 中分享的内容一致，以及机器人的回应在语义上是否与人类治疗师的回应相似。我们分析了两个数据集：一个是用户与专业治疗师之间的互动（Hugging Face 的 NLP 心理健康对话），另一个是与社交机器人（LuxAI 的 QTrobot）的支援对话，该机器人由大型语言模型（LLM，GPT-3.5）驱动。通过使用句子嵌入和 K-means 聚类，我们采用了一种基于距离的聚类拟合方法来评估跨智能体的主题一致性，该方法评估一种智能体类型的回应是否映射到另一种智能体类型得出的聚类，并使用欧几里得距离进行了验证。研究结果表明，90.88% 的机器人对话披露可以映射到人类治疗数据集的聚类，表明主题结构的相似性。对于匹配的聚类，我们使用 Transformer、Word2Vec 和 BERT 嵌入比较了主题以及治疗师和机器人的回应，发现两个数据集中主题披露的语义重叠很强，以及在类似人类披露主题下不同智能体类型（机器人与人类治疗师）的回应之间也存在强烈的语义重叠。这些发现揭示了机器人主导支持对话的相似性与界限，以及它们在增强心理健康干预方面的潜力。

> As conversational agents increasingly engage in emotionally supportive dialogue, it is important to understand how closely their interactions resemble those in traditional therapy settings. This study investigates whether the concerns shared with a robot align with those shared in human-to-human (H2H) therapy sessions, and whether robot responses semantically mirror those of human therapists. We analyzed two datasets: one of interactions between users and professional therapists (Hugging Face's NLP Mental Health Conversations), and another involving supportive conversations with a social robot (QTrobot from LuxAI) powered by a large language model (LLM, GPT-3.5). Using sentence embeddings and K-means clustering, we assessed cross-agent thematic alignment by applying a distance-based cluster-fitting method that evaluates whether responses from one agent type map to clusters derived from the other, and validated it using Euclidean distances. Results showed that 90.88% of robot conversation disclosures could be mapped to clusters from the human therapy dataset, suggesting shared topical structure. For matched clusters, we compared the subjects as well as therapist and robot responses using Transformer, Word2Vec, and BERT embeddings, revealing strong semantic overlap in subjects' disclosures in both datasets, as well as in the responses given to similar human disclosure themes across agent types (robot vs. human therapist). These findings highlight both the parallels and boundaries of robot-led support conversations and their potential for augmenting mental health interventions.

[Arxiv](https://arxiv.org/abs/2506.16473)