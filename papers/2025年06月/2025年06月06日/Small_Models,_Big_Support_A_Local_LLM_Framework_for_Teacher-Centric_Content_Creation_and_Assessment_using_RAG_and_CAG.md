# 小模型，大力支撑：本地LLM框架，助力以教师为中心的内容创作与评估，采用RAG和CAG方法

发布时间：2025年06月06日

`LLM应用

论文摘要：尽管大型语言模型（LLMs）在教育领域应用广泛，但其在支持教育工作者方面的潜力，尤其是通过本地部署和可定制的开源方案，仍未得到充分挖掘。现有教育解决方案多依赖昂贵的云服务或专有工具，可能引发隐私问题。预算有限的行业亟需经济实惠的自托管方案。我们推出了一款端到端开源框架，利用小型（30亿至70亿参数）、本地部署的LLMs实现定制化教学材料生成与评估。我们的系统独创性地整合了小型模型优化的关键交互式循环，以及辅助LLM验证器，有效降低越狱风险，提升输出的可靠性和安全性。借助检索和上下文增强生成（RAG/CAG），系统能够生成事实准确、定制化且符合教学风格的内容。本地部署确保数据隐私，经评估管道和大学物理课程试点验证。研究发现，精心设计的小型LLM系统不仅功能强大、经济实用且安全可靠，针对特定任务，其表现可与大型模型相媲美。

LLM应用`

> Small Models, Big Support: A Local LLM Framework for Teacher-Centric Content Creation and Assessment using RAG and CAG

# 摘要

> 尽管大型语言模型（LLMs）在教育领域应用广泛，但其在支持教育工作者方面的潜力，尤其是通过本地部署和可定制的开源方案，仍未得到充分挖掘。现有教育解决方案多依赖昂贵的云服务或专有工具，可能引发隐私问题。预算有限的行业亟需经济实惠的自托管方案。我们推出了一款端到端开源框架，利用小型（30亿至70亿参数）、本地部署的LLMs实现定制化教学材料生成与评估。我们的系统独创性地整合了小型模型优化的关键交互式循环，以及辅助LLM验证器，有效降低越狱风险，提升输出的可靠性和安全性。借助检索和上下文增强生成（RAG/CAG），系统能够生成事实准确、定制化且符合教学风格的内容。本地部署确保数据隐私，经评估管道和大学物理课程试点验证。研究发现，精心设计的小型LLM系统不仅功能强大、经济实用且安全可靠，针对特定任务，其表现可与大型模型相媲美。

> While Large Language Models (LLMs) are increasingly utilized as student-facing educational aids, their potential to directly support educators, particularly through locally deployable and customizable open-source solutions, remains significantly underexplored. Many existing educational solutions rely on cloud-based infrastructure or proprietary tools, which are costly and may raise privacy concerns. Regulated industries with limited budgets require affordable, self-hosted solutions. We introduce an end-to-end, open-source framework leveraging small (3B-7B parameters), locally deployed LLMs for customized teaching material generation and assessment. Our system uniquely incorporates an interactive loop crucial for effective small-model refinement, and an auxiliary LLM verifier to mitigate jailbreaking risks, enhancing output reliability and safety. Utilizing Retrieval and Context Augmented Generation (RAG/CAG), it produces factually accurate, customized pedagogically-styled content. Deployed on-premises for data privacy and validated through an evaluation pipeline and a college physics pilot, our findings show that carefully engineered small LLM systems can offer robust, affordable, practical, and safe educator support, achieving utility comparable to larger models for targeted tasks.

[Arxiv](https://arxiv.org/abs/2506.05925)