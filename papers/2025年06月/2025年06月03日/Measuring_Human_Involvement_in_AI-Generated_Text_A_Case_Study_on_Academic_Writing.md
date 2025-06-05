# AI生成文本中人类参与度的测量：以学术写作为例

发布时间：2025年06月03日

`LLM应用

理由：这篇论文探讨了大型语言模型在内容创作中的应用，特别是如何检测和分类AI生成的文本，以及人类在生成过程中的参与程度。这属于LLM的应用层面，因为它专注于解决实际问题（如学术诚信中的AI检测）并提出具体的方法和解决方案，而不是探讨LLM的理论或Agent的行为模式。` `内容创作`

> Measuring Human Involvement in AI-Generated Text: A Case Study on Academic Writing

# 摘要

> 内容创作领域随着像ChatGPT和Claude这样的大型语言模型的快速发展取得了显著进展。这些进步极大地提升了生活和工作的多个方面，但也给社会带来了一些负面影响。最近的一项调查显示，近30%的大学生使用生成式AI来帮助撰写学术论文和报告。大多数对策将AI生成文本的检测视为二分类任务，因而缺乏鲁棒性。这种做法忽视了人类在内容生成中的参与，尽管人机协作正在成为主流。除了生成完整的文本，人们可能还会利用机器完成或修改文本。这种人类参与的程度因情况而异，使得二分类方法难以令人满意。我们称这种情况为参与检测模糊化。我们建议使用BERTScore作为指标来衡量人类在生成过程中的参与程度，并提出了一种基于多任务RoBERTa的回归器，通过分词分类任务来解决这一问题。为了评估该方法的有效性，我们模拟了学术场景并创建了一个反映不同程度人类参与的连续数据集。所有现有的检测器在该数据集上都未能检测到人类参与的水平。然而，我们的方法成功了（F1得分为0.9423，回归器均方误差为0.004）。此外，该方法在生成模型之间表现出一定的通用性。我们的代码可在https://github.com/gyc-nii/CAS-CS-and-dual-head-detector上获得

> Content creation has dramatically progressed with the rapid advancement of large language models like ChatGPT and Claude. While this progress has greatly enhanced various aspects of life and work, it has also negatively affected certain areas of society. A recent survey revealed that nearly 30% of college students use generative AI to help write academic papers and reports. Most countermeasures treat the detection of AI-generated text as a binary classification task and thus lack robustness. This approach overlooks human involvement in the generation of content even though human-machine collaboration is becoming mainstream. Besides generating entire texts, people may use machines to complete or revise texts. Such human involvement varies case by case, which makes binary classification a less than satisfactory approach. We refer to this situation as participation detection obfuscation. We propose using BERTScore as a metric to measure human involvement in the generation process and a multi-task RoBERTa-based regressor trained on a token classification task to address this problem. To evaluate the effectiveness of this approach, we simulated academic-based scenarios and created a continuous dataset reflecting various levels of human involvement. All of the existing detectors we examined failed to detect the level of human involvement on this dataset. Our method, however, succeeded (F1 score of 0.9423 and a regressor mean squared error of 0.004). Moreover, it demonstrated some generalizability across generative models. Our code is available at https://github.com/gyc-nii/CAS-CS-and-dual-head-detector

[Arxiv](https://arxiv.org/abs/2506.03501)