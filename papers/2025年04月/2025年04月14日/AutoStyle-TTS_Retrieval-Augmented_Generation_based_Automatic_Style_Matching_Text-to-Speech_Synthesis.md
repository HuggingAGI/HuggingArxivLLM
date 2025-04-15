# AutoStyle-TTS：检索增强生成（RAG）驱动的自动风格匹配文本到语音合成

发布时间：2025年04月14日

`RAG` `人工智能` `语音合成`

> AutoStyle-TTS: Retrieval-Augmented Generation based Automatic Style Matching Text-to-Speech Synthesis

# 摘要

> 语音合成技术的飞速发展让用户对合成语音的自然度和表现力有了更高期待。然而，现有研究往往忽视了提示选择的重要性。我们提出了一种基于检索增强生成（RAG）技术的文本到语音（TTS）框架，能够根据文本内容动态调整语音风格，带来更自然生动的交流体验。我们构建了一个包含多种场景下高质量语音样本的语音风格知识库，并开发了一套风格匹配方案。该方案利用Llama、PER-LLM-Embedder和Moka提取的嵌入向量，在知识库中精准匹配，选择最适合的语音风格进行合成。实证研究证明了我们方法的有效性。体验我们的演示请点击：https://thuhcsi.github.io/icme2025-AutoStyle-TTS

> With the advancement of speech synthesis technology, users have higher expectations for the naturalness and expressiveness of synthesized speech. But previous research ignores the importance of prompt selection. This study proposes a text-to-speech (TTS) framework based on Retrieval-Augmented Generation (RAG) technology, which can dynamically adjust the speech style according to the text content to achieve more natural and vivid communication effects. We have constructed a speech style knowledge database containing high-quality speech samples in various contexts and developed a style matching scheme. This scheme uses embeddings, extracted by Llama, PER-LLM-Embedder,and Moka, to match with samples in the knowledge database, selecting the most appropriate speech style for synthesis. Furthermore, our empirical research validates the effectiveness of the proposed method. Our demo can be viewed at: https://thuhcsi.github.io/icme2025-AutoStyle-TTS

[Arxiv](https://arxiv.org/abs/2504.10309)