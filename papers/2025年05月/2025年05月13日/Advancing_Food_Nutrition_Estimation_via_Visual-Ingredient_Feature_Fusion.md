# 基于视觉-成分特征融合的食品营养评估方法研究

发布时间：2025年05月13日

`其他` `营养学` `计算机视觉`

> Advancing Food Nutrition Estimation via Visual-Ingredient Feature Fusion

# 摘要

> 营养估计是促进健康饮食和缓解饮食相关健康风险的重要一环。尽管在食物分类和食材识别等任务上已取得进展，但受缺乏营养标注数据集的限制，营养估计领域的发展仍显滞后。为解决这一难题，我们推出了FastFood数据集，包含908类快餐食品的84,446张图像，并附带了详实的食材和营养信息标注。同时，我们提出了一种全新的模型不可知视觉-食材特征融合（VIF$^2$）方法，通过整合视觉与食材特征提升营养估计的准确性。通过训练过程中采用同义词替换和重采样策略，我们显著增强了食材识别的鲁棒性。食材感知的视觉特征融合模块巧妙结合了食材特征与视觉表征，从而实现了精准的营养预测。在测试阶段，我们借助大型多模态模型，通过数据增强和多数投票策略对食材预测结果进行优化。实验结果表明，我们在FastFood和Nutrition5k数据集上采用不同 backbone（如Resnet、InceptionV3和ViT）实现的方法均表现出色，充分证明了食材信息在营养估计中的关键作用。

> Nutrition estimation is an important component of promoting healthy eating and mitigating diet-related health risks. Despite advances in tasks such as food classification and ingredient recognition, progress in nutrition estimation is limited due to the lack of datasets with nutritional annotations. To address this issue, we introduce FastFood, a dataset with 84,446 images across 908 fast food categories, featuring ingredient and nutritional annotations. In addition, we propose a new model-agnostic Visual-Ingredient Feature Fusion (VIF$^2$) method to enhance nutrition estimation by integrating visual and ingredient features. Ingredient robustness is improved through synonym replacement and resampling strategies during training. The ingredient-aware visual feature fusion module combines ingredient features and visual representation to achieve accurate nutritional prediction. During testing, ingredient predictions are refined using large multimodal models by data augmentation and majority voting. Our experiments on both FastFood and Nutrition5k datasets validate the effectiveness of our proposed method built in different backbones (e.g., Resnet, InceptionV3 and ViT), which demonstrates the importance of ingredient information in nutrition estimation. https://huiyanqi.github.io/fastfood-nutrition-estimation/.

[Arxiv](https://arxiv.org/abs/2505.08747)