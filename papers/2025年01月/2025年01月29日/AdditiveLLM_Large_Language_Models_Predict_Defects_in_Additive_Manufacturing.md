# AdditiveLLM: 大型语言模型助力增材制造缺陷预测

发布时间：2025年01月29日

`LLM应用

**理由**：该论文探讨了大型语言模型在增材制造领域的应用，具体是通过微调模型来预测制造缺陷模式。这属于将大型语言模型应用于特定领域（增材制造）的实际问题解决，因此归类为LLM应用。` `增材制造` `缺陷预测`

> AdditiveLLM: Large Language Models Predict Defects in Additive Manufacturing

# 摘要

> 本研究探讨了大型语言模型在给定工艺参数输入下预测增材制造缺陷模式的能力。我们使用工艺参数缺陷数据集微调了一组名为AdditiveLLM的模型，旨在预测包括Keyholing、Lack of Fusion和Balling在内的缺陷模式。通过比较不同输入格式方法，我们评估了模型在稀疏基线数据集和自然语言提示数据集上的表现。结果显示，模型具备强大的预测能力，准确率高达93%。自然语言输入的引入进一步简化了工艺参数选择，帮助用户找到最佳构建设置。

> In this work we investigate the ability of large language models to predict additive manufacturing defect regimes given a set of process parameter inputs. For this task we utilize a process parameter defect dataset to fine-tune a collection of models, titled AdditiveLLM, for the purpose of predicting potential defect regimes including Keyholing, Lack of Fusion, and Balling. We compare different methods of input formatting in order to gauge the model's performance to correctly predict defect regimes on our sparse Baseline dataset and our natural language Prompt dataset. The model displays robust predictive capability, achieving an accuracy of 93\% when asked to provide the defect regimes associated with a set of process parameters. The incorporation of natural language input further simplifies the task of process parameters selection, enabling users to identify optimal settings specific to their build.

[Arxiv](https://arxiv.org/abs/2501.17784)