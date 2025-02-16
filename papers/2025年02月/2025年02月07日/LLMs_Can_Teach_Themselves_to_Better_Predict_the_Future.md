# 大型语言模型 (LLMs) 可通过自我训练提升预测未来的能力。

发布时间：2025年02月07日

`LLM理论` `人工智能` `机器学习`

> LLMs Can Teach Themselves to Better Predict the Future

# 摘要

> 我们提出了一种基于结果的微调框架，旨在提升大型语言模型（LLMs）的预测能力，而无需依赖人工编写的推理样本。通过模型自我对弈，我们为一组在模型知识截止日期后可解答的多样化问题生成多样化的推理轨迹和概率预测。随后，根据推理轨迹与实际结果之间的距离对这些轨迹进行排序，并通过直接偏好优化（DPO）对模型进行微调。在单独的测试集上，我们的方法使Phi-4 14B和DeepSeek-R1 14B的预测准确率相较于基础模型和使用随机标签的DPO微调对照模型提高了7-10%，使其预测能力与更大规模的前沿模型（如GPT-4o）相媲美。

> We present an outcome-driven fine-tuning framework that enhances the forecasting capabilities of large language models (LLMs) without relying on human-curated reasoning samples. Our method leverages model self-play to generate pairs of diverse reasoning trajectories and probabilistic forecasts for a set of diverse questions that resolve after the models' knowledge cutoff date. We then rank pairs of these reasoning traces by their distance to the actual outcomes before fine-tuning the model via Direct Preference Optimization (DPO). On a separate test set, our approach increases prediction accuracy of Phi-4 14B and DeepSeek-R1 14B by between 7--10\% over a base model and a DPO fine-tuned control model with randomized labels, bringing them on par with forecasting capabilities of much larger frontier models like GPT-4o.

[Arxiv](https://arxiv.org/abs/2502.05253)