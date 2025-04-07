# 叙事中人物的位置：安徒生与劝说数据集

发布时间：2025年04月04日

`LLM应用` `阅读理解`

> Locations of Characters in Narratives: Andersen and Persuasion Datasets

# 摘要

> 机器在叙事语境中掌握空间理解的能力是阅读理解中一个引人入胜的方面，这一领域仍在不断研究之中。为了测试AI在理解叙事中角色与其位置关系方面的能力，我们引入了两个新的数据集：Andersen和Persuasion。对于Andersen数据集，我们从《安徒生童话》中精选了十五个儿童故事，并手动标注了每个故事中角色及其相应的位置。同样地，对于Persuasion数据集，我们也手动标注了《劝导》中角色及其位置。我们使用这些数据集来提示大型语言模型（LLMs）。提示的创建方法是提取故事或小说中的片段，并结合一个问题，询问该片段中提到的角色的位置。在测试的五种LLMs中，Andersen数据集表现最佳的模型在61.85%的例子中准确识别了位置，而Persuasion数据集表现最佳的模型在56.06%的案例中做到了这一点。

> The ability of machines to grasp spatial understanding within narrative contexts is an intriguing aspect of reading comprehension that continues to be studied. Motivated by the goal to test the AI's competence in understanding the relationship between characters and their respective locations in narratives, we introduce two new datasets: Andersen and Persuasion. For the Andersen dataset, we selected fifteen children's stories from "Andersen's Fairy Tales" by Hans Christian Andersen and manually annotated the characters and their respective locations throughout each story. Similarly, for the Persuasion dataset, characters and their locations in the novel "Persuasion" by Jane Austen were also manually annotated. We used these datasets to prompt Large Language Models (LLMs). The prompts are created by extracting excerpts from the stories or the novel and combining them with a question asking the location of a character mentioned in that excerpt. Out of the five LLMs we tested, the best-performing one for the Andersen dataset accurately identified the location in 61.85% of the examples, while for the Persuasion dataset, the best-performing one did so in 56.06% of the cases.

[Arxiv](https://arxiv.org/abs/2504.03434)