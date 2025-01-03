# 个性化与顺序式文本生成图像

发布时间：2024年12月09日

`Agent

理由：这篇论文描述了一个强化学习（RL）代理，用于个性化、交互式文本到图像（T2I）生成。该代理通过一系列提示扩展迭代优化用户生成的图像，并结合大型多模态语言模型（LMM）和基于价值的RL方法，为用户推荐个性化和多样化的提示扩展。因此，这篇论文主要涉及Agent的设计和应用。` `图像生成` `个性化推荐`

> Personalized and Sequential Text-to-Image Generation

# 摘要

> 我们致力于解决个性化、交互式文本到图像（T2I）生成问题，设计了一个强化学习（RL）代理，通过一系列提示扩展迭代优化用户生成的图像。我们利用人类评分者创建了一个新颖的顺序偏好数据集，并结合大规模开源（非顺序）数据集。通过EM策略，我们构建了用户偏好和选择模型，识别出不同的用户偏好类型。随后，我们借助大型多模态语言模型（LMM）和基于价值的RL方法，为用户推荐个性化和多样化的提示扩展。我们的个性化顺序文本到图像代理（PASTA）扩展了T2I模型的个性化多轮能力，促进协作共创，并解决用户意图中的不确定性或未明确性。通过人类评分者的评估，PASTA显示出相较于基线方法的显著改进。我们还发布了顺序评分者数据集和模拟用户评分者交互，以支持未来在个性化多轮T2I生成领域的研究。

> We address the problem of personalized, interactive text-to-image (T2I) generation, designing a reinforcement learning (RL) agent which iteratively improves a set of generated images for a user through a sequence of prompt expansions. Using human raters, we create a novel dataset of sequential preferences, which we leverage, together with large-scale open-source (non-sequential) datasets. We construct user-preference and user-choice models using an EM strategy and identify varying user preference types. We then leverage a large multimodal language model (LMM) and a value-based RL approach to suggest a personalized and diverse slate of prompt expansions to the user. Our Personalized And Sequential Text-to-image Agent (PASTA) extends T2I models with personalized multi-turn capabilities, fostering collaborative co-creation and addressing uncertainty or underspecification in a user's intent. We evaluate PASTA using human raters, showing significant improvement compared to baseline methods. We also release our sequential rater dataset and simulated user-rater interactions to support future research in personalized, multi-turn T2I generation.

[Arxiv](https://arxiv.org/abs/2412.10419)