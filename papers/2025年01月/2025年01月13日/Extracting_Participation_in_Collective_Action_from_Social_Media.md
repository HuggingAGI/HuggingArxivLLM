# 从社交媒体中挖掘集体行动的参与情况

发布时间：2025年01月13日

`LLM应用

理由：这篇论文主要讨论了如何利用BERT和Llama3等语言模型来开发文本分类器，用于从社交媒体帖子中识别参与集体行动的表达。虽然论文涉及了语言模型的应用，但重点在于如何利用这些模型来解决特定的社会科学问题（即识别集体行动的参与水平），而不是探讨语言模型本身的理论或架构。因此，将其归类为“LLM应用”更为合适。` `社交媒体` `计算社会科学`

> Extracting Participation in Collective Action from Social Media

# 摘要

> 社交媒体在动员集体行动中发挥着关键作用，为研究个体如何积极参与应对全球挑战提供了潜力。然而，由于缺乏关于个体社交媒体用户参与集体行动水平的细粒度和大规模真实数据，这一领域的定量研究受到了限制。为此，我们开发了一套新颖的文本分类器，能够以主题无关的方式从社交媒体帖子中识别参与集体行动的表达。基于社会运动动员的理论框架，我们的分类器将参与分为四个层次：识别集体问题、参与行动号召、表达行动意图和报告积极参与。我们通过众包构建了一个Reddit评论的标注训练数据集，用于训练BERT分类器并微调Llama3模型。研究结果显示，较小的语言模型能够可靠地检测参与表达（加权F1=0.71），并在捕捉细微参与水平方面与较大模型相媲美。通过将我们的方法应用于Reddit，我们展示了其作为一种强大工具的有效性，与主题建模、立场检测和基于关键词的方法相比，能够以创新的方式描述在线社区。我们的框架为计算社会科学研究提供了新的可靠注释来源，有助于研究集体行动的社会动态。

> Social media play a key role in mobilizing collective action, holding the potential for studying the pathways that lead individuals to actively engage in addressing global challenges. However, quantitative research in this area has been limited by the absence of granular and large-scale ground truth about the level of participation in collective action among individual social media users. To address this limitation, we present a novel suite of text classifiers designed to identify expressions of participation in collective action from social media posts, in a topic-agnostic fashion. Grounded in the theoretical framework of social movement mobilization, our classification captures participation and categorizes it into four levels: recognizing collective issues, engaging in calls-to-action, expressing intention of action, and reporting active involvement. We constructed a labeled training dataset of Reddit comments through crowdsourcing, which we used to train BERT classifiers and fine-tune Llama3 models. Our findings show that smaller language models can reliably detect expressions of participation (weighted F1=0.71), and rival larger models in capturing nuanced levels of participation. By applying our methodology to Reddit, we illustrate its effectiveness as a robust tool for characterizing online communities in innovative ways compared to topic modeling, stance detection, and keyword-based methods. Our framework contributes to Computational Social Science research by providing a new source of reliable annotations useful for investigating the social dynamics of collective action.

[Arxiv](https://arxiv.org/abs/2501.07368)