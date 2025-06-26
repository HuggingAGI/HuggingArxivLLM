# Step-Opt：助力提升大型语言模型优化建模能力，采用迭代数据合成与结构化验证方法

发布时间：2025年06月21日

`LLM应用` `运筹学` `优化建模`

> Step-Opt: Boosting Optimization Modeling in LLMs through Iterative Data Synthesis and Structured Validation

# 摘要

> 大型语言模型（LLMs）虽然在多个领域取得了突破性进展，但在处理运筹学（OR）中的优化建模任务时，尤其是面对复杂问题时，仍然面临巨大的挑战。为解决这一问题，我们提出了 Step-Opt-Instruct 框架，通过增强现有数据集并生成专门针对优化建模的高质量微调数据，系统性地提升模型性能。Step-Opt-Instruct 采用迭代问题生成方法，逐步增加问题复杂度，并通过严格的数据验证流程，确保数据质量，防止错误传播。基于此框架，我们对开源大型语言模型（如 LLaMA-3-8B 和 Mistral-7B）进行了微调，成功开发出了 Step-Opt 模型。在 NL4OPT、MAMO 和 IndustryOR 等基准测试中，Step-Opt 达到了当前最优性能。实验结果表明，Step-Opt 在处理复杂 OR 任务方面表现出色，尤其在解决难题时，微平均准确率提升了 17.01%。这些成果证明了将结构化验证与逐步问题优化相结合的有效性，为利用 LLMs 推动决策过程自动化提供了重要参考。代码和数据集可在 https://github.com/samwu-learn/Step 获取。

> Large Language Models (LLMs) have revolutionized various domains but encounter substantial challenges in tackling optimization modeling tasks for Operations Research (OR), particularly when dealing with complex problem. In this work, we propose Step-Opt-Instruct, a framework that augments existing datasets and generates high-quality fine-tuning data tailored to optimization modeling. Step-Opt-Instruct employs iterative problem generation to systematically increase problem complexity and stepwise validation to rigorously verify data, preventing error propagation and ensuring the quality of the generated dataset. Leveraging this framework, we fine-tune open-source LLMs, including LLaMA-3-8B and Mistral-7B, to develop Step-Opt--a model that achieves state-of-the-art performance on benchmarks such as NL4OPT, MAMO, and IndustryOR. Extensive experiments demonstrate the superior performance of Step-Opt, especially in addressing complex OR tasks, with a notable 17.01\% improvement in micro average accuracy on difficult problems. These findings highlight the effectiveness of combining structured validation with gradual problem refinement to advance the automation of decision-making processes using LLMs.The code and dataset are available at https://github.com/samwu-learn/Step.

[Arxiv](https://arxiv.org/abs/2506.17637)