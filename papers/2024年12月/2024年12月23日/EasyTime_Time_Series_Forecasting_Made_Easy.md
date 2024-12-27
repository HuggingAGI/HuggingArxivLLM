# EasyTime：使时间序列预测轻松实现

发布时间：2024年12月23日

`LLM应用` `时间序列预测` `软件开发`

> EasyTime: Time Series Forecasting Made Easy

# 摘要

> 时间序列预测在众多领域都有着重要的应用。我们所展示的 EasyTime 系统，为研究人员和从业者轻松运用时间序列预测方法提供了便利。其一，EasyTime 实现了一键评估，借助 TFB 灵活且统一的评估流程，让研究人员能够使用预先收集的多样化时间序列数据集套件来评估新的预测方法。其二，当从业者要在新数据集上进行预测时，首要且关键的一步往往是找到合适的预测方法。EasyTime 提供了一个自动集成模块，将有前景的预测方法加以整合，相比单个方法能获得更出色的预测准确率。其三，EasyTime 借助大型语言模型推出了自然语言问答模块。比如给定“对于具有强烈季节性的时间序列进行长期预测，哪种方法最佳？”这样的问题，EasyTime 会将其转换为对 TFB 所得结果数据库的 SQL 查询，然后以自然语言和图表给出答案。通过展示 EasyTime，我们意在表明如何简化时间序列预测的使用，并为新一代时间序列预测方法的开发提供更有力的支持。

> Time series forecasting has important applications across diverse domains. EasyTime, the system we demonstrate, facilitates easy use of time-series forecasting methods by researchers and practitioners alike. First, EasyTime enables one-click evaluation, enabling researchers to evaluate new forecasting methods using the suite of diverse time series datasets collected in the preexisting time series forecasting benchmark (TFB). This is achieved by leveraging TFB's flexible and consistent evaluation pipeline. Second, when practitioners must perform forecasting on a new dataset, a nontrivial first step is often to find an appropriate forecasting method. EasyTime provides an Automated Ensemble module that combines the promising forecasting methods to yield superior forecasting accuracy compared to individual methods. Third, EasyTime offers a natural language Q&A module leveraging large language models. Given a question like "Which method is best for long term forecasting on time series with strong seasonality?", EasyTime converts the question into SQL queries on the database of results obtained by TFB and then returns an answer in natural language and charts. By demonstrating EasyTime, we intend to show how it is possible to simplify the use of time series forecasting and to offer better support for the development of new generations of time series forecasting methods.

[Arxiv](https://arxiv.org/abs/2412.17603)