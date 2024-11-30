# DFIN-SQL 是一项创新技术，它将聚焦模式与 DIN-SQL 整合，旨在提升在处理大型数据库时的查询精确度。

发布时间：2024年03月01日

`RAG`

> DFIN-SQL: Integrating Focused Schema with DIN-SQL for Superior Accuracy in Large-Scale Databases

# 摘要

> 将自然语言查询转译为SQL查询是一项精细活儿，DIN-SQL（分解式上下文SQL）技术为此领域带来了重大突破。本文提出了一项DIN-SQL的革新延伸——DFIN（分解焦点上下文），它专注于修复模式链接错误这一关键误差源，进而提升文本转SQL的质量。DFIN独创性地结合运用提示技术和检索增强生成（RAG），灵活适应各类大小和复杂度的数据库模式。预处理阶段巧妙嵌入数据库定义，并借鉴BIRD数据集等资源中注释文件的优势，以便于实时提取相关模式信息，从而大幅度减少模式链接所需的标记数量。得益于此，DFIN能够借助标准版GPT-4模型，在处理大型数据库时，效率与经济性俱佳。实验证明，在极具挑战性的现实基准BIRD数据集上，DFIN不仅展现出了卓越的可扩展性，而且精度显著提升，得分高达51.69，远超先前仅采用上下文学习而非微调技术、位列第三的DIN-SQL（其原得分为50.72）。DFIN的这一进步生动展现了结合高级语言模型的上下文学习方法所蕴含的持续发展潜力，为今后探索复杂文本转SQL难题的研究开辟了一条充满希望的新路径。

> The task of converting natural language queries into SQL queries is intricate, necessitating a blend of precise techniques for an accurate translation. The DIN-SQL (Decomposed-In-Context SQL) methodology represents a significant development in this domain. This paper introduces DFIN (Decomposed Focused-In-Context), an innovative extension of DIN-SQL that enhances Text-to-SQL conversion by addressing schema linking errors, which are a major source of inaccuracies. DFIN uniquely alternates between prompting techniques and Retrieval-Augmented Generation (RAG), adapting to the size and complexity of the database schema. A preprocessing phase embeds database definitions and leverages annotated files, akin to those in the BIRD dataset, facilitating the runtime retrieval of pertinent schema information. This strategy significantly reduces the token count for schema linking prompts, enabling the use of a standard GPT-4 model over its larger context variant, thus handling large-scale databases more effectively and economically. Our evaluation on the BIRD dataset, a challenging real-world benchmark, demonstrates that DFIN not only scales efficiently but also improves accuracy, achieving a score of 51.69. This improvement surpasses DIN-SQL method (the current third-place), which is the highest-ranked model employing in-context learning rather than fine-tuning, previously scoring 50.72. The advancement of DFIN underscores the evolving capabilities of in-context learning methodologies combined with advanced language models, offering a promising avenue for future research in complex Text-to-SQL conversion tasks.

[Arxiv](https://arxiv.org/abs/2403.00872)