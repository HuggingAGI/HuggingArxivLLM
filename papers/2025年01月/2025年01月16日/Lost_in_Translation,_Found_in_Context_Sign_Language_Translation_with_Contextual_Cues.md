# 翻译迷失，上下文寻回：基于上下文线索的手语翻译

发布时间：2025年01月16日

`LLM应用

**理由**：该论文主要描述了如何利用预训练的大型语言模型（LLM）进行手语翻译，并通过整合额外的上下文线索来提升翻译性能。这属于将LLM应用于特定任务（手语翻译）的范畴，因此分类为LLM应用。` `手语翻译`

> Lost in Translation, Found in Context: Sign Language Translation with Contextual Cues

# 摘要

> 我们的目标是将连续手语翻译为口语文本。受人类翻译员依赖上下文进行准确翻译的启发，我们将额外的上下文线索与手语视频结合，构建了一个新的翻译框架。具体来说，除了编码输入视频的视觉手语识别特征外，我们还整合了以下补充文本信息：(i) 描述背景节目的字幕，(ii) 前几句的翻译，以及 (iii) 转录手语的伪注释。这些信息被自动提取并与视觉特征一起输入到预训练的大型语言模型（LLM）中，我们对该模型进行微调以生成文本形式的口语翻译。通过广泛的消融研究，我们展示了每个输入线索对翻译性能的积极贡献。我们在BOBSL——目前最大的英国手语数据集上训练和评估了我们的方法。结果表明，与之前报道的BOBSL结果相比，我们的上下文方法显著提升了翻译质量，并且优于我们作为基线实现的最先进方法。此外，我们还将该方法应用于How2Sign（一个美国手语数据集），并取得了竞争性结果，进一步证明了我们方法的通用性。

> Our objective is to translate continuous sign language into spoken language text. Inspired by the way human interpreters rely on context for accurate translation, we incorporate additional contextual cues together with the signing video, into a new translation framework. Specifically, besides visual sign recognition features that encode the input video, we integrate complementary textual information from (i) captions describing the background show, (ii) translation of previous sentences, as well as (iii) pseudo-glosses transcribing the signing. These are automatically extracted and inputted along with the visual features to a pre-trained large language model (LLM), which we fine-tune to generate spoken language translations in text form. Through extensive ablation studies, we show the positive contribution of each input cue to the translation performance. We train and evaluate our approach on BOBSL -- the largest British Sign Language dataset currently available. We show that our contextual approach significantly enhances the quality of the translations compared to previously reported results on BOBSL, and also to state-of-the-art methods that we implement as baselines. Furthermore, we demonstrate the generality of our approach by applying it also to How2Sign, an American Sign Language dataset, and achieve competitive results.

[Arxiv](https://arxiv.org/abs/2501.09754)