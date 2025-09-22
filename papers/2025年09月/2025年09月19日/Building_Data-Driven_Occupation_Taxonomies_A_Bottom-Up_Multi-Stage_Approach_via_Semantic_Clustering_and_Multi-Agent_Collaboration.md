# 构建数据驱动的职业分类体系：基于语义聚类与多智能体协作的自下而上多阶段方法

发布时间：2025年09月19日

`Agent` `基础理论`

> Building Data-Driven Occupation Taxonomies: A Bottom-Up Multi-Stage Approach via Semantic Clustering and Multi-Agent Collaboration

# 摘要

> 构建稳健的职业分类体系对职位推荐、劳动力市场情报等应用至关重要，但其创建过程一直充满挑战：手动整理耗时费力，现有自动方法则各有短板——自上而下的方法无法适应动态区域市场，自下而上的方法又难以从噪声数据中构建连贯层次结构。为此，我们提出CLIMB（基于聚类的多智能体分类体系构建器）——一个能从原始招聘信息中全自动生成高质量数据驱动分类体系的框架。CLIMB首先通过全局语义聚类提取核心职业，再借助基于反思的多智能体系统迭代构建连贯层次结构。在三个不同的真实数据集上的实验表明，CLIMB生成的分类体系不仅比现有方法更连贯、更具可扩展性，还能成功捕捉独特的区域特征。我们已在https://anonymous.4open.science/r/CLIMB开源了代码和数据集。

> Creating robust occupation taxonomies, vital for applications ranging from job recommendation to labor market intelligence, is challenging. Manual curation is slow, while existing automated methods are either not adaptive to dynamic regional markets (top-down) or struggle to build coherent hierarchies from noisy data (bottom-up). We introduce CLIMB (CLusterIng-based Multi-agent taxonomy Builder), a framework that fully automates the creation of high-quality, data-driven taxonomies from raw job postings. CLIMB uses global semantic clustering to distill core occupations, then employs a reflection-based multi-agent system to iteratively build a coherent hierarchy. On three diverse, real-world datasets, we show that CLIMB produces taxonomies that are more coherent and scalable than existing methods and successfully capture unique regional characteristics. We release our code and datasets at https://anonymous.4open.science/r/CLIMB.

[Arxiv](https://arxiv.org/abs/2509.15786)