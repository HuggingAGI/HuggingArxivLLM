# EmoNews：用于富有表现力新闻对话的语音对话系统

发布时间：2025年06月16日

`LLM应用` `对话系统` `语音合成`

> EmoNews: A Spoken Dialogue System for Expressive News Conversations

# 摘要

> 我们开发了一个任务导向的口语对话系统（SDS），通过上下文线索调节情绪化语音，以实现更富有同理心的新闻对话。尽管情感语音合成（TTS）技术取得了进展，但任务导向情感对话系统的探索仍然较少，这主要是由于对话系统与情感TTS研究领域之间的割裂，以及缺乏针对社交目标的标准化评估指标。我们通过开发一个用于新闻对话的情感对话系统来解决这些挑战，该系统利用大型语言模型（LLM）- 基础的情感分析器来识别适当的情绪，并使用PromptTTS来合成符合上下文的带有情绪的语音。我们还为情感对话系统提出了主观评估标准，并对所提系统与基线系统的的情绪调节性能进行了评估。实验表明，我们的情感对话系统在情绪调节和参与度方面优于基线系统。这些结果表明，语音情绪对于更吸引人的对话具有关键作用。我们的所有源代码均可在https://github.com/dhatchi711/espnet-emotional-news/tree/emo-sds/egs2/emo_news_sds/sds1上公开获取。

> We develop a task-oriented spoken dialogue system (SDS) that regulates emotional speech based on contextual cues to enable more empathetic news conversations. Despite advancements in emotional text-to-speech (TTS) techniques, task-oriented emotional SDSs remain underexplored due to the compartmentalized nature of SDS and emotional TTS research, as well as the lack of standardized evaluation metrics for social goals. We address these challenges by developing an emotional SDS for news conversations that utilizes a large language model (LLM)-based sentiment analyzer to identify appropriate emotions and PromptTTS to synthesize context-appropriate emotional speech. We also propose subjective evaluation scale for emotional SDSs and judge the emotion regulation performance of the proposed and baseline systems. Experiments showed that our emotional SDS outperformed a baseline system in terms of the emotion regulation and engagement. These results suggest the critical role of speech emotion for more engaging conversations. All our source code is open-sourced at https://github.com/dhatchi711/espnet-emotional-news/tree/emo-sds/egs2/emo_news_sds/sds1

[Arxiv](https://arxiv.org/abs/2506.13894)