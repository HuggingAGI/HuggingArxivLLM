# 文化多样性多语言多模态视频基准测试与模型

发布时间：2025年06月08日

`LLM应用` `视频处理` `多语言支持`

> A Culturally-diverse Multilingual Multimodal Video Benchmark & Model

# 摘要

> 大型多模态模型（LMMs）因其在理解和生成视觉内容描述方面的有效性，最近受到了广泛关注。现有的大多数LMMs都是英文的。尽管最近有一些研究探索了多语言图像LMMs，但据我们所知，针对视频LMMs的研究在文化和语言包容性方面尚未深入。为了推动更具包容性的视频LMMs的发展，我们引入了一个多语言视频LMM基准测试，名为ViMUL-Bench，用于评估涵盖14种语言的视频LMMs，包括资源丰富的语言和资源匮乏的语言：英语、中文、西班牙语、法语、德语、印地语、阿拉伯语、俄语、孟加拉语、乌尔都语、僧伽罗语、泰米尔语、瑞典语和日语。我们的ViMUL-Bench设计了15个测试类别，其中包括8个文化多样性类别，涵盖从生活方式和节日到食物和仪式，再到地标和文化名人等各个方面。ViMUL-Bench包含开放式问题（短文本和长文本）和多项选择题，覆盖了不同时长的视频（短、中、长），并经过8,000个样本的人工验证，由母语者完成。此外，我们还引入了一个机器翻译的多语言视频训练集，包含120万个样本，并开发了一个简单的多语言视频LMM，名为ViMUL，它在视频理解方面展示了在高资源语言和低资源语言之间更好的平衡。我们希望ViMUL-Bench和多语言视频LMM，以及大规模的多语言视频训练集，能够为未来开发更具文化与语言包容性的多语言视频LMMs提供支持。我们的基准测试、视频LMM和训练数据将在https://mbzuai-oryx.github.io/ViMUL/公开发布。

> Large multimodal models (LMMs) have recently gained attention due to their effectiveness to understand and generate descriptions of visual content. Most existing LMMs are in English language. While few recent works explore multilingual image LMMs, to the best of our knowledge, moving beyond the English language for cultural and linguistic inclusivity is yet to be investigated in the context of video LMMs. In pursuit of more inclusive video LMMs, we introduce a multilingual Video LMM benchmark, named ViMUL-Bench, to evaluate Video LMMs across 14 languages, including both low- and high-resource languages: English, Chinese, Spanish, French, German, Hindi, Arabic, Russian, Bengali, Urdu, Sinhala, Tamil, Swedish, and Japanese. Our ViMUL-Bench is designed to rigorously test video LMMs across 15 categories including eight culturally diverse categories, ranging from lifestyles and festivals to foods and rituals and from local landmarks to prominent cultural personalities. ViMUL-Bench comprises both open-ended (short and long-form) and multiple-choice questions spanning various video durations (short, medium, and long) with 8k samples that are manually verified by native language speakers. In addition, we also introduce a machine translated multilingual video training set comprising 1.2 million samples and develop a simple multilingual video LMM, named ViMUL, that is shown to provide a better tradeoff between high-and low-resource languages for video understanding. We hope our ViMUL-Bench and multilingual video LMM along with a large-scale multilingual video training set will help ease future research in developing cultural and linguistic inclusive multilingual video LMMs. Our proposed benchmark, video LMM and training data will be publicly released at https://mbzuai-oryx.github.io/ViMUL/.

[Arxiv](https://arxiv.org/abs/2506.07032)