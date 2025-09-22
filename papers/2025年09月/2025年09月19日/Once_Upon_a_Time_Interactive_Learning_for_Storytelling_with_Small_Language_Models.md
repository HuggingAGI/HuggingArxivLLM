# # Once Upon a Time: Interactive Learning for Storytelling with Small Language Models
从前：小型语言模型的故事创作交互式学习

发布时间：2025年09月19日

`LLM理论` `基础理论`

> Once Upon a Time: Interactive Learning for Storytelling with Small Language Models

# 摘要

> 儿童高效习得语言，靠的不只是倾听，还有在社交环境中与他人的互动。相比之下，大型语言模型的训练方式通常是在海量文本上进行下一词预测。受这一差异的启发，我们探究语言模型能否通过双重学习——不仅学习下一词预测，还结合高级的、受认知启发的反馈——实现用更少数据完成训练。我们让学生模型生成故事，再由教师模型从可读性、叙事连贯性和创造力三个维度进行评分。通过调整反馈循环前的预训练量，我们评估这种交互式学习对语言形式与功能能力的影响。研究发现，高级反馈的数据效率极高：在交互式学习中仅输入100万词，讲故事能力的提升效果就与4.1亿词下一词预测训练相当。

> Children efficiently acquire language not just by listening, but by interacting with others in their social environment. Conversely, large language models are typically trained with next-word prediction on massive amounts of text. Motivated by this contrast, we investigate whether language models can be trained with less data by learning not only from next-word prediction but also from high-level, cognitively inspired feedback. We train a student model to generate stories, which a teacher model rates on readability, narrative coherence, and creativity. By varying the amount of pretraining before the feedback loop, we assess the impact of this interactive learning on formal and functional linguistic competence. We find that the high-level feedback is highly data efficient: With just 1 M words of input in interactive learning, storytelling skills can improve as much as with 410 M words of next-word prediction.

[Arxiv](https://arxiv.org/abs/2509.15714)