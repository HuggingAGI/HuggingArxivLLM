# 超越问题：借助 ColBERT 实现关键词搜索

发布时间：2024年12月04日

`LLM应用`

> Beyond Questions: Leveraging ColBERT for Keyphrase Search

# 摘要

> 虽说类问题查询日益流行，搜索引擎用户也愈发青睐，可关键词搜索向来都是网络搜索的基石。在诸如学术或专业搜索等专业搜索任务中，这种查询类型同样常见，专家们依靠关键词来阐明自身的信息需求。然而，当下的密集检索模型在应对类似关键词的查询时往往表现不佳，主要原因在于它们大多是基于类问题查询进行训练的。本文引入了一个运用 ColBERT 架构的新型模型，旨在提升关键词查询的文档排名。鉴于缺乏大型的基于关键词的检索数据集，我们首先探究大型语言模型怎样将类问题查询转化为关键词格式。接着，利用这些关键词，我们训练了一个基于关键词的 ColBERT 排名器（ColBERTKP_QD），以改进处理关键词查询时的性能。另外，为降低训练完整 ColBERT 模型所产生的训练成本，我们研究了仅训练关键词查询编码器而保持文档编码器权重固定（ColBERTKP_Q）的可行性。我们通过自动生成和人工标注的关键词来评估我们方案的排名性能。我们的结果展现了在关键词搜索场景下后期交互架构的潜力。

> While question-like queries are gaining popularity and search engines' users increasingly adopt them, keyphrase search has traditionally been the cornerstone of web search. This query type is also prevalent in specialised search tasks such as academic or professional search, where experts rely on keyphrases to articulate their information needs. However, current dense retrieval models often fail with keyphrase-like queries, primarily because they are mostly trained on question-like ones. This paper introduces a novel model that employs the ColBERT architecture to enhance document ranking for keyphrase queries. For that, given the lack of large keyphrase-based retrieval datasets, we first explore how Large Language Models can convert question-like queries into keyphrase format. Then, using those keyphrases, we train a keyphrase-based ColBERT ranker (ColBERTKP_QD) to improve the performance when working with keyphrase queries. Furthermore, to reduce the training costs associated with training the full ColBERT model, we investigate the feasibility of training only a keyphrase query encoder while keeping the document encoder weights static (ColBERTKP_Q). We assess our proposals' ranking performance using both automatically generated and manually annotated keyphrases. Our results reveal the potential of the late interaction architecture when working under the keyphrase search scenario.

[Arxiv](https://arxiv.org/abs/2412.03193)