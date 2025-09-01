# 自动化深空网络数据系统；基于智能体AI的自适应异常检测案例研究

发布时间：2025年08月28日

`Agent` `工业与制造`

> Automating the Deep Space Network Data Systems; A Case Study in Adaptive Anomaly Detection through Agentic AI

# 摘要

> 深空网络（DSN）是NASA最大的天线设施网络，能产生海量多变量时间序列数据。这些设施中的DSN天线和发射器长期使用会逐渐退化，可能造成高昂的数据传输中断损失，还会威胁数十个以DSN为生命线的航天器与地球的通信连接。本研究旨在试验多种方法，助力喷气推进实验室（JPL）工程师通过采集数据直接定位异常和设备退化问题，从而保障DSN的持续维护与运营，为未来的深空探测任务提供支持。为此，我们探索了多种机器学习技术，可通过预测分析实现数据的完整重建，并借助统计计算与阈值分析识别实时数据集中的异常条目。在训练测试完备的机器学习模型之上，我们进一步集成了强化学习子系统（按严重程度对异常分类）和大型语言模型（为每个异常条目生成解释标签），这些模块均可通过人类反馈持续优化与微调。针对DSN发射器，我们还构建了完整的数据管道系统，整合了数据提取、解析与处理全流程——此前这类任务一直缺乏连贯的程序或脚本支持。借助该数据管道，我们还能对接基于DSN天线数据训练的模型，最终打通了DSN异常检测的全数据工作流。这一切都由一个智能体AI系统统筹连接，该系统通过复杂推理完成异常数据的分类与预测。

> The Deep Space Network (DSN) is NASA's largest network of antenna facilities that generate a large volume of multivariate time-series data. These facilities contain DSN antennas and transmitters that undergo degradation over long periods of time, which may cause costly disruptions to the data flow and threaten the earth-connection of dozens of spacecraft that rely on the Deep Space Network for their lifeline. The purpose of this study was to experiment with different methods that would be able to assist JPL engineers with directly pinpointing anomalies and equipment degradation through collected data, and continue conducting maintenance and operations of the DSN for future space missions around our universe. As such, we have researched various machine learning techniques that can fully reconstruct data through predictive analysis, and determine anomalous data entries within real-time datasets through statistical computations and thresholds. On top of the fully trained and tested machine learning models, we have also integrated the use of a reinforcement learning subsystem that classifies identified anomalies based on severity level and a Large Language Model that labels an explanation for each anomalous data entry, all of which can be improved and fine-tuned over time through human feedback/input. Specifically, for the DSN transmitters, we have also implemented a full data pipeline system that connects the data extraction, parsing, and processing workflow all together as there was no coherent program or script for performing these tasks before. Using this data pipeline system, we were able to then also connect the models trained from DSN antenna data, completing the data workflow for DSN anomaly detection. This was all wrapped around and further connected by an agentic AI system, where complex reasoning was utilized to determine the classifications and predictions of anomalous data.

[Arxiv](https://arxiv.org/abs/2508.21111)