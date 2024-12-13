# SPRec：借助自我博弈来纠正基于大型语言模型推荐中的偏好对齐偏差

发布时间：2024年12月12日

`LLM应用` `推荐系统` `用户偏好`

> SPRec: Leveraging Self-Play to Debias Preference Alignment for Large Language Model-based Recommendations

# 摘要

> 大型语言模型（LLMs）在推荐系统领域备受瞩目。当下基于 LLM 的推荐系统主要依赖监督微调（SFT）来训练用于推荐任务的模型。然而，仅依靠正样本会限制模型与用户满意度和期望的契合度。为应对此问题，研究人员引入了直接偏好优化（DPO），利用离线偏好排名数据让推荐与用户偏好明确一致。尽管其有优势，但我们的理论分析显示，DPO 本身会使模型偏向少数项目，加重过滤气泡问题，最终降低用户体验。在本文中，我们提出了 SPRec 这一全新的自玩推荐框架，旨在减少过度推荐并提升公平性，无需额外数据或人工干预。在每次自玩迭代中，模型先进行 SFT 步骤，接着进行 DPO 步骤，将离线交互数据当作正样本，把前一轮迭代的预测输出视为负样本。这有效地利用模型的对数几率重新衡量 DPO 损失函数，自适应地抑制有偏差的项目。在多个真实世界数据集上的大量实验表明，SPRec 在提高推荐准确性和解决公平性问题方面成效显著。

> Large language models (LLMs) have attracted significant attention in recommendation systems. Current LLM-based recommender systems primarily rely on supervised fine-tuning (SFT) to train the model for recommendation tasks. However, relying solely on positive samples limits the model's ability to align with user satisfaction and expectations. To address this, researchers have introduced Direct Preference Optimization (DPO), which explicitly aligns recommendations with user preferences using offline preference ranking data. Despite its advantages, our theoretical analysis reveals that DPO inherently biases the model towards a few items, exacerbating the filter bubble issue and ultimately degrading user experience. In this paper, we propose SPRec, a novel self-play recommendation framework designed to mitigate over-recommendation and improve fairness without requiring additional data or manual intervention. In each self-play iteration, the model undergoes an SFT step followed by a DPO step, treating offline interaction data as positive samples and the predicted outputs from the previous iteration as negative samples. This effectively re-weights the DPO loss function using the model's logits, adaptively suppressing biased items. Extensive experiments on multiple real-world datasets demonstrate SPRec's effectiveness in enhancing recommendation accuracy and addressing fairness concerns.

[Arxiv](https://arxiv.org/abs/2412.09243)