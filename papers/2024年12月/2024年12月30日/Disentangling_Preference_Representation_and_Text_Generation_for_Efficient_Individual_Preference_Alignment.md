# 拆解偏好表示与文本生成，以达成高效的个体偏好对齐

发布时间：2024年12月30日

`LLM应用` `语言模型` `文本生成`

> Disentangling Preference Representation and Text Generation for Efficient Individual Preference Alignment

# 摘要

> 让大型语言模型（LLMs）契合一般人类偏好，已被证实对提升LLMs与人类的交互质量极为关键。然而，人类价值观在不同个体间本就多样，仅让LLMs与一般偏好相符远远不够。为此，依据个人反馈对LLMs进行个性化，成为颇具前景的解决之策。不过，此方法在对齐算法的效率上存在难题。在本项工作中，我们引入了一种灵活的个人偏好对齐模式。我们的方法从根本上提升了效率，将偏好表示从LLMs的文本生成中分离出来。我们在多个文本生成任务中验证了该方法，表明其能生成与基于PEFT的方法相同甚至更优的对齐质量，同时相比之下，为每个新的个人偏好减少80%至90%的额外训练时间。

> Aligning Large Language Models (LLMs) with general human preferences has been proved crucial in improving the interaction quality between LLMs and human. However, human values are inherently diverse among different individuals, making it insufficient to align LLMs solely with general preferences. To address this, personalizing LLMs according to individual feedback emerges as a promising solution. Nonetheless, this approach presents challenges in terms of the efficiency of alignment algorithms. In this work, we introduce a flexible paradigm for individual preference alignment. Our method fundamentally improves efficiency by disentangling preference representation from text generation in LLMs. We validate our approach across multiple text generation tasks and demonstrate that it can produce aligned quality as well as or better than PEFT-based methods, while reducing additional training time for each new individual preference by $80\%$ to $90\%$ in comparison with them.

[Arxiv](https://arxiv.org/abs/2412.20834)