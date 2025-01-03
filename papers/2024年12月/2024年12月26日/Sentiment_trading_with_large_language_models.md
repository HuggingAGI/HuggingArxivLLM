# 基于大型语言模型的情感交易

发布时间：2024年12月26日

`LLM应用

**理由**：这篇论文探讨了大型语言模型（LLMs）在金融新闻情感分析和股市回报预测中的应用。具体来说，它分析了不同LLMs（如BERT、OPT、FINBERT）在金融领域中的表现，并展示了它们在预测股票回报和投资组合管理中的潜力。这属于LLM在实际场景中的应用，因此分类为LLM应用。` `股市预测`

> Sentiment trading with large language models

# 摘要

> 我们探讨了大型语言模型（LLMs）在美国金融新闻情感分析中的表现及其预测股市回报的潜力。我们分析了2010年1月1日至2023年6月30日期间的965,375篇新闻文章，重点关注了BERT、OPT、FINBERT等LLMs以及传统的Loughran-McDonald词典模型的表现。研究发现，LLM评分与次日股票回报之间存在显著关联。其中，基于GPT-3的OPT模型在情感预测中表现最佳，准确率达74.4%，略高于BERT（72.5%）和FINBERT（72.2%）。而Loughran-McDonald词典模型的准确率仅为50.1%，效果明显较差。回归分析显示，OPT模型评分对次日股票回报有显著正向影响，系数分别为0.274和0.254。BERT和FINBERT也表现出一定的预测能力，但效果较弱。值得注意的是，Loughran-McDonald词典模型评分与股票回报之间并无显著关联，这对其在当前金融环境中的有效性提出了质疑。在投资组合表现方面，多空OPT策略的夏普比率高达3.05，远超BERT（2.11）和FINBERT（2.07）。而基于Loughran-McDonald词典的策略夏普比率仅为1.23。研究结果表明，先进的LLMs，尤其是OPT，在金融市场预测和投资组合管理中表现卓越，标志着金融分析工具领域的重大变革，对金融监管和政策分析具有深远影响。

> We investigate the efficacy of large language models (LLMs) in sentiment analysis of U.S. financial news and their potential in predicting stock market returns. We analyze a dataset comprising 965,375 news articles that span from January 1, 2010, to June 30, 2023; we focus on the performance of various LLMs, including BERT, OPT, FINBERT, and the traditional Loughran-McDonald dictionary model, which has been a dominant methodology in the finance literature. The study documents a significant association between LLM scores and subsequent daily stock returns. Specifically, OPT, which is a GPT-3 based LLM, shows the highest accuracy in sentiment prediction with an accuracy of 74.4%, slightly ahead of BERT (72.5%) and FINBERT (72.2%). In contrast, the Loughran-McDonald dictionary model demonstrates considerably lower effectiveness with only 50.1% accuracy. Regression analyses highlight a robust positive impact of OPT model scores on next-day stock returns, with coefficients of 0.274 and 0.254 in different model specifications. BERT and FINBERT also exhibit predictive relevance, though to a lesser extent. Notably, we do not observe a significant relationship between the Loughran-McDonald dictionary model scores and stock returns, challenging the efficacy of this traditional method in the current financial context. In portfolio performance, the long-short OPT strategy excels with a Sharpe ratio of 3.05, compared to 2.11 for BERT and 2.07 for FINBERT long-short strategies. Strategies based on the Loughran-McDonald dictionary yield the lowest Sharpe ratio of 1.23. Our findings emphasize the superior performance of advanced LLMs, especially OPT, in financial market prediction and portfolio management, marking a significant shift in the landscape of financial analysis tools with implications to financial regulation and policy analysis.

[Arxiv](https://arxiv.org/abs/2412.19245)