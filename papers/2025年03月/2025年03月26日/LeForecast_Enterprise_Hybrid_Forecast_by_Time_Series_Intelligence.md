# LeForecast：通过时间序列智能实现企业混合预测

发布时间：2025年03月26日

`LLM应用` `数据分析`

> LeForecast: Enterprise Hybrid Forecast by Time Series Intelligence

# 摘要

> 工业领域对多学科预测的需求激增，各行各业都需要通过规划和预测来优化智能业务管理，例如需求预测、产品规划、库存优化等。具体而言，这些任务期待智能方法从按顺序收集的历史数据中学习，然后预测最可能的趋势，即时间序列预测。其挑战在于解释复杂的业务背景以及建模的效率和泛化能力。鉴于大型基础模型在众多任务中取得了显著成功，我们致力于开发预训练基础模型以满足这一需求。为此，我们推出了\leforecast{}，一个专为时间序列任务设计的企业智能平台。该平台整合了对时间序列数据和多源信息的先进解释，以及一个由大型基础模型（Le-TSFM）、多模态模型和混合模型组成的三支柱建模引擎，用于挖掘见解、预测未来并推动企业运营中多领域的优化。该框架由模型池、模型配置文件模块以及两种不同的融合方法组成，涉及原始模型架构。实验结果验证了我们提出的融合概念的效率：基于路由的融合网络和大小模型的协调，导致了模型冗余开发和维护的高昂成本。本文回顾了LeForecast的部署及其在三个工业用例中的性能表现。我们的综合实验表明，LeForecast是一个强大而实用的平台，能够实现高效且具有竞争力的性能。我们希望这项工作能够启发时间序列技术在加速企业应用中的研究和应用。

> Demand is spiking in industrial fields for multidisciplinary forecasting, where a broad spectrum of sectors needs planning and forecasts to streamline intelligent business management, such as demand forecasting, product planning, inventory optimization, etc. Specifically, these tasks expecting intelligent approaches to learn from sequentially collected historical data and then foresee most possible trend, i.e. time series forecasting. Challenge of it lies in interpreting complex business contexts and the efficiency and generalisation of modelling. With aspirations of pre-trained foundational models for such purpose, given their remarkable success of large foundation model across legions of tasks, we disseminate \leforecast{}, an enterprise intelligence platform tailored for time series tasks. It integrates advanced interpretations of time series data and multi-source information, and a three-pillar modelling engine combining a large foundation model (Le-TSFM), multimodal model and hybrid model to derive insights, predict or infer futures, and then drive optimisation across multiple sectors in enterprise operations. The framework is composed by a model pool, model profiling module, and two different fusion approaches regarding original model architectures. Experimental results verify the efficiency of our trail fusion concepts: router-based fusion network and coordination of large and small models, resulting in high costs for redundant development and maintenance of models. This work reviews deployment of LeForecast and its performance in three industrial use cases. Our comprehensive experiments indicate that LeForecast is a profound and practical platform for efficient and competitive performance. And we do hope that this work can enlighten the research and grounding of time series techniques in accelerating enterprise.

[Arxiv](https://arxiv.org/abs/2503.22747)