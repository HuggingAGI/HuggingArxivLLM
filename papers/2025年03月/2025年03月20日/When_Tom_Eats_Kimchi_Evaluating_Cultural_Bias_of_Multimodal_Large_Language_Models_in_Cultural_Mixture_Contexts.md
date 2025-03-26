# # 当汤姆吃泡菜的时候：在文化混合环境中评估多模态大型语言模型的文化偏见

发布时间：2025年03月20日

`LLM应用` `人工智能` `跨文化计算`

> When Tom Eats Kimchi: Evaluating Cultural Bias of Multimodal Large Language Models in Cultural Mixture Contexts

# 摘要

> 在全球化的今天，多模态大型语言模型（MLLMs）正确识别和处理混合文化输入显得尤为重要。例如，无论是亚洲女性还是非洲男性食用泡菜（韩式食物），模型都应能准确识别出泡菜。然而，当前的MLLMs存在过度依赖人物视觉特征的问题，导致实体分类错误。为了评估MLLMs对不同种族的鲁棒性，我们提出了跨文化偏见基准测试MixCuBe，并研究了来自五个国家和四个种族的元素。研究发现，MLLMs在高资源文化中展现出更高的准确性和对干扰的更低敏感度，但在低资源文化中表现不佳。其中，表现最佳的模型GPT-4o在低资源文化中，原文化和干扰文化设置下的准确率差异高达58%。我们的数据集已公开发布，访问链接为：https://huggingface.co/datasets/kyawyethu/MixCuBe。

> In a highly globalized world, it is important for multi-modal large language models (MLLMs) to recognize and respond correctly to mixed-cultural inputs. For example, a model should correctly identify kimchi (Korean food) in an image both when an Asian woman is eating it, as well as an African man is eating it. However, current MLLMs show an over-reliance on the visual features of the person, leading to misclassification of the entities. To examine the robustness of MLLMs to different ethnicity, we introduce MixCuBe, a cross-cultural bias benchmark, and study elements from five countries and four ethnicities. Our findings reveal that MLLMs achieve both higher accuracy and lower sensitivity to such perturbation for high-resource cultures, but not for low-resource cultures. GPT-4o, the best-performing model overall, shows up to 58% difference in accuracy between the original and perturbed cultural settings in low-resource cultures. Our dataset is publicly available at: https://huggingface.co/datasets/kyawyethu/MixCuBe.

[Arxiv](https://arxiv.org/abs/2503.16826)