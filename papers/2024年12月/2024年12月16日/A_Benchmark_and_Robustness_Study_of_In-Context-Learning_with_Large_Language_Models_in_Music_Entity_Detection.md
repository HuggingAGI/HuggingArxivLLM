# 关于大型语言模型在音乐实体检测中的上下文学习的基准及鲁棒性研究

发布时间：2024年12月16日

`LLM应用` `语言模型`

> A Benchmark and Robustness Study of In-Context-Learning with Large Language Models in Music Entity Detection

# 摘要

> 检测诸如歌曲名或艺术家姓名等音乐实体是一项实用的应用，能助力处理音乐搜索查询或分析网络音乐消费等场景。近期的方法融入了像 BERT 这样的小型语言模型（SLMs），并取得了出色成果。然而，进一步研究显示，预训练时的实体暴露对模型性能影响颇大。随着大型语言模型（LLMs）的问世，它们在众多下游任务中都胜过 SLMs。但由于存在幻觉等问题，对于其是否适用于文本中的实体检测等任务，研究人员仍意见不一。在本文中，我们提供了一个新的用户生成元数据集，并利用具备上下文学习（ICL）的最新 LLMs 进行了基准测试和稳健性研究。我们的结果表明，在 ICL 设定下，LLMs 比 SLMs 表现更优。我们还揭示了实体暴露对我们研究中表现最佳的 LLM 有着重大影响。

> Detecting music entities such as song titles or artist names is a useful application to help use cases like processing music search queries or analyzing music consumption on the web. Recent approaches incorporate smaller language models (SLMs) like BERT and achieve high results. However, further research indicates a high influence of entity exposure during pre-training on the performance of the models. With the advent of large language models (LLMs), these outperform SLMs in a variety of downstream tasks. However, researchers are still divided if this is applicable to tasks like entity detection in texts due to issues like hallucination. In this paper, we provide a novel dataset of user-generated metadata and conduct a benchmark and a robustness study using recent LLMs with in-context-learning (ICL). Our results indicate that LLMs in the ICL setting yield higher performance than SLMs. We further uncover the large impact of entity exposure on the best performing LLM in our study.

[Arxiv](https://arxiv.org/abs/2412.11851)