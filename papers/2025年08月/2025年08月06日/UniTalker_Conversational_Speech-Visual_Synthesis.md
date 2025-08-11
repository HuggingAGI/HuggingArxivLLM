# UniTalker：对话式语音与视觉合成

发布时间：2025年08月06日

`LLM应用

理由：这篇论文探讨了大规模语言模型在多模态对话中的应用，特别是如何通过整合语音和视觉元素来提升智能体的交互体验。研究重点在于利用LLM进行情感推断和内容生成，属于LLM的实际应用领域。` `智能交互` `人工智能`

> UniTalker: Conversational Speech-Visual Synthesis

# 摘要

> 对话式语音合成（CSS）是用户与智能体交互中的核心任务，致力于生成更具表现力和共情力的语音。然而，现实人际交流中，“倾听”与“眼神交流”对情感传达至关重要。现有 CSS 研究仅限于感知对话中的文本与语音，这限制了其效果。此外，单一语音响应进一步削弱了交互体验。为突破这些限制，我们提出了对话式语音-视觉合成（CSVS）任务，作为传统 CSS 的升级版。通过整合多模态对话上下文，CSVS 为用户带来更连贯的视听体验。为此，我们开发了名为 UniTalker 的 CSVS 系统，这是一个融合多模态感知与渲染能力的统一模型。具体而言，UniTalker 借助大规模语言模型，全面解析对话中的多模态线索，包括说话人、文本、语音及讲话人脸动画。随后，通过多任务序列预测，先推断目标 utterance 的情感，再生成富有共情的语音与自然的讲话人脸动画。为确保生成内容在情感、内容和时长上保持一致，我们引入三大优化策略：1) 开发专用神经关键点编解码器，实现面部表情序列的精准分词与重建。2) 提出双模态语音-视觉硬对齐解码策略。3) 在生成阶段融入情感引导渲染机制。详尽的实验结果表明，UniTalker 不仅能够生成更具共情力的语音，更能为用户呈现更自然且情感一致的讲话人脸动画，显著提升交互体验。

> Conversational Speech Synthesis (CSS) is a key task in the user-agent interaction area, aiming to generate more expressive and empathetic speech for users. However, it is well-known that "listening" and "eye contact" play crucial roles in conveying emotions during real-world interpersonal communication. Existing CSS research is limited to perceiving only text and speech within the dialogue context, which restricts its effectiveness. Moreover, speech-only responses further constrain the interactive experience. To address these limitations, we introduce a Conversational Speech-Visual Synthesis (CSVS) task as an extension of traditional CSS. By leveraging multimodal dialogue context, it provides users with coherent audiovisual responses. To this end, we develop a CSVS system named UniTalker, which is a unified model that seamlessly integrates multimodal perception and multimodal rendering capabilities. Specifically, it leverages a large-scale language model to comprehensively understand multimodal cues in the dialogue context, including speaker, text, speech, and the talking-face animations. After that, it employs multi-task sequence prediction to first infer the target utterance's emotion and then generate empathetic speech and natural talking-face animations. To ensure that the generated speech-visual content remains consistent in terms of emotion, content, and duration, we introduce three key optimizations: 1) Designing a specialized neural landmark codec to tokenize and reconstruct facial expression sequences. 2) Proposing a bimodal speech-visual hard alignment decoding strategy. 3) Applying emotion-guided rendering during the generation stage. Comprehensive objective and subjective experiments demonstrate that our model synthesizes more empathetic speech and provides users with more natural and emotionally consistent talking-face animations.

[Arxiv](https://arxiv.org/abs/2508.04585)