# 主题：基于语义股票表征与时间动态提升主题投资

发布时间：2025年08月29日

`LLM应用` `金融科技`

> THEME: Enhancing Thematic Investing with Semantic Stock Representations and Temporal Dynamics

# 摘要

> 主题投资致力于构建契合结构性趋势的投资组合，但受行业边界重叠与市场动态演变影响，这一领域始终充满挑战。从文本数据中挖掘投资主题的语义表示是个颇具前景的方向，然而通用LLM嵌入模型虽能力出众，却难以精准捕捉金融资产的独特属性——毕竟投资资产的语义内涵与普通金融文本可能存在本质差异。为此，我们推出THEME框架，通过分层对比学习对嵌入进行微调：先利用主题与成分股的层级关系实现两者对齐，再结合股票回报进一步优化嵌入。最终生成的表示能高效检索主题匹配且回报潜力强劲的资产。实证研究显示，THEME在两大核心领域表现突出：一是主题资产检索性能显著超越主流大型语言模型，二是构建的投资组合收益表现亮眼。通过融合文本中的主题关联与回报中的市场动态，THEME为各类实际投资场景量身打造了专用股票嵌入。

> Thematic investing, which aims to construct portfolios aligned with structural trends, remains a challenging endeavor due to overlapping sector boundaries and evolving market dynamics. A promising direction is to build semantic representations of investment themes from textual data. However, despite their power, general-purpose LLM embedding models are not well-suited to capture the nuanced characteristics of financial assets, since the semantic representation of investment assets may differ fundamentally from that of general financial text. To address this, we introduce THEME, a framework that fine-tunes embeddings using hierarchical contrastive learning. THEME aligns themes and their constituent stocks using their hierarchical relationship, and subsequently refines these embeddings by incorporating stock returns. This process yields representations effective for retrieving thematically aligned assets with strong return potential. Empirical results demonstrate that THEME excels in two key areas. For thematic asset retrieval, it significantly outperforms leading large language models. Furthermore, its constructed portfolios demonstrate compelling performance. By jointly modeling thematic relationships from text and market dynamics from returns, THEME generates stock embeddings specifically tailored for a wide range of practical investment applications.

[Arxiv](https://arxiv.org/abs/2508.16936)