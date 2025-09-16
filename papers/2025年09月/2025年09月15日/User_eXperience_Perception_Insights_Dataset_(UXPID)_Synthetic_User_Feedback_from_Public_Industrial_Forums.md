# 用户体验感知洞察数据集（UXPID）：源于公共工业论坛的合成用户反馈

发布时间：2025年09月15日

`LLM应用` `工业与制造`

> User eXperience Perception Insights Dataset (UXPID): Synthetic User Feedback from Public Industrial Forums

# 摘要

> 工业论坛中的客户反馈，是洞察真实产品体验的丰富却尚未充分挖掘的来源。这些公开讨论自然呈现了用户的期望、困扰与成功故事，而这些都深受特定使用场景的影响。然而，由于这类内容具有非结构化和领域特定的特点，要将其用于系统分析仍面临挑战。内容缺乏固定结构且充斥专业术语，导致传统数据分析技术难以准确解读、分类和量化这些反馈，进而限制了其为产品开发与支持策略提供指导的潜力。为应对这些挑战，本文提出用户体验感知洞察数据集（UXPID）——该数据集包含7130条人工合成并匿名化的用户反馈分支，均提取自某公共工业自动化论坛。每个JavaScript对象表示法（JSON）记录均包含与特定软硬件产品相关的多帖评论，并附带元数据及上下文对话信息。借助大型语言模型（LLM），我们对每个反馈分支进行了系统分析与标注，涵盖用户体验洞察、用户期望、问题严重程度、情感倾向评分及主题分类等维度。UXPID数据集旨在推动用户需求挖掘、用户体验（UX）分析及AI驱动反馈处理等领域的研究，尤其适用于因隐私与许可限制而难以获取真实世界数据的场景。该数据集可支持训练与评估基于Transformer的模型，以应对技术论坛中的问题检测、情感分析及需求提取等任务。

> Customer feedback in industrial forums reflect a rich but underexplored source of insight into real-world product experience. These publicly shared discussions offer an organic view of user expectations, frustrations, and success stories shaped by the specific contexts of use. Yet, harnessing this information for systematic analysis remains challenging due to the unstructured and domain-specific nature of the content. The lack of structure and specialized vocabulary makes it difficult for traditional data analysis techniques to accurately interpret, categorize, and quantify the feedback, thereby limiting its potential to inform product development and support strategies. To address these challenges, this paper presents the User eXperience Perception Insights Dataset (UXPID), a collection of 7130 artificially synthesized and anonymized user feedback branches extracted from a public industrial automation forum. Each JavaScript object notation (JSON) record contains multi-post comments related to specific hardware and software products, enriched with metadata and contextual conversation data. Leveraging a large language model (LLM), each branch is systematically analyzed and annotated for UX insights, user expectations, severity and sentiment ratings, and topic classifications. The UXPID dataset is designed to facilitate research in user requirements, user experience (UX) analysis, and AI-driven feedback processing, particularly where privacy and licensing restrictions limit access to real-world data. UXPID supports the training and evaluation of transformer-based models for tasks such as issue detection, sentiment analysis, and requirements extraction in the context of technical forums.

[Arxiv](https://arxiv.org/abs/2509.11777)