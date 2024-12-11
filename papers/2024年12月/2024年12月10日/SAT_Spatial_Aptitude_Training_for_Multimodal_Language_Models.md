# SAT：用于多模态语言模型的空间能力训练

发布时间：2024年12月10日

`LLM应用` `空间推理` `人工智能`

> SAT: Spatial Aptitude Training for Multimodal Language Models

# 摘要

> 空间感知乃智力的基本构成要素。尽管诸多研究指出大型多模态语言模型（MLMs）在空间推理上存在困境，然而它们仅测试了静态空间推理，像对物体相对位置的分类。与此同时，现实世界的应用需要诸如视角转换和以自我为中心的动作识别这类动态能力。作为提升空间智能的路线图，我们引入了 SAT，即空间能力训练，其超越了静态的相对物体位置问题，迈向更具动态性的任务。SAT 涵盖 218K 个问答对，涉及 22K 个合成场景，分布于训练集与测试集。通过逼真的物理引擎生成，我们的数据集能够任意缩放，并能轻松拓展至新的动作、场景和 3D 资产。我们发现，即便在静态问题上表现尚可的 MLMs，也难以精准回答动态空间问题。此外，我们表明 SAT 指令调整数据不但提升了 SAT 上的动态空间推理能力，还提高了现有真实图像空间基准的零样本性能：在 CVBench 上提升 23％，在更具难度的 BLINK 基准上提升 8％，在 VSR 上提升 18％。当在 SAT 上进行指令调整时，我们的 13B 模型在空间推理方面能与更大的专有 MLMs，如 GPT4-V 和 Gemini-3-1.0 相媲美。我们的数据/代码可于 http://arijitray1993.github.io/SAT/ 获取。

> Spatial perception is a fundamental component of intelligence. While many studies highlight that large multimodal language models (MLMs) struggle to reason about space, they only test for static spatial reasoning, such as categorizing the relative positions of objects. Meanwhile, real-world deployment requires dynamic capabilities like perspective-taking and egocentric action recognition. As a roadmap to improving spatial intelligence, we introduce SAT, Spatial Aptitude Training, which goes beyond static relative object position questions to the more dynamic tasks. SAT contains 218K question-answer pairs for 22K synthetic scenes across a training and testing set. Generated using a photo-realistic physics engine, our dataset can be arbitrarily scaled and easily extended to new actions, scenes, and 3D assets. We find that even MLMs that perform relatively well on static questions struggle to accurately answer dynamic spatial questions. Further, we show that SAT instruction-tuning data improves not only dynamic spatial reasoning on SAT, but also zero-shot performance on existing real-image spatial benchmarks: $23\%$ on CVBench, $8\%$ on the harder BLINK benchmark, and $18\%$ on VSR. When instruction-tuned on SAT, our 13B model matches larger proprietary MLMs like GPT4-V and Gemini-3-1.0 in spatial reasoning. Our data/code is available at http://arijitray1993.github.io/SAT/ .

[Arxiv](https://arxiv.org/abs/2412.07755)