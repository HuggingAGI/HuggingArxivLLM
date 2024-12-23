# 《恐惧的猎鹰和愤怒的美洲驼：人类与大型语言模型对论点的情绪类别标注》

发布时间：2024年12月20日

`LLM应用` `情绪研究`

> Fearful Falcons and Angry Llamas: Emotion Category Annotations of Arguments by Humans and LLMs

# 摘要

> 论点会引发情绪，从而影响论点自身的效果。不仅情绪的强烈程度，就连类别也会左右论点的成效，比如改变立场的意愿。虽说在论点中对二元情绪已有研究，但此类数据中针对离散情绪类别（如“愤怒”）的研究却付诸阙如。为填补这一空白，我们在一个德语论点语料库中众包了情绪类别的主观标注，并对基于自动 LLM 的标注方法予以评估。具体而言，我们在三个大型指令调优语言模型（Falcon-7b-instruct、Llama-3.1-8B-instruct、GPT-4o-mini）上对比了三种提示策略（零样本、单样本、思维链）。我们还进一步改变了输出空间的定义，使其成为二元（论点中是否存在情绪？）、封闭域（论点中存在给定标签集中的何种情绪？）或开放域（论点中存在哪种情绪？）。我们发现，情绪类别能增强对论点中情绪的预测，这凸显了在论点中进行离散情绪标注的必要性。在所有的提示设置和模型中，自动预测在预测愤怒和恐惧时呈现出高召回率但低精度的情况，表明对负面情绪存在强烈的偏向。

> Arguments evoke emotions, influencing the effect of the argument itself. Not only the emotional intensity but also the category influence the argument's effects, for instance, the willingness to adapt stances. While binary emotionality has been studied in arguments, there is no work on discrete emotion categories (e.g., "Anger") in such data. To fill this gap, we crowdsource subjective annotations of emotion categories in a German argument corpus and evaluate automatic LLM-based labeling methods. Specifically, we compare three prompting strategies (zero-shot, one-shot, chain-of-thought) on three large instruction-tuned language models (Falcon-7b-instruct, Llama-3.1-8B-instruct, GPT-4o-mini). We further vary the definition of the output space to be binary (is there emotionality in the argument?), closed-domain (which emotion from a given label set is in the argument?), or open-domain (which emotion is in the argument?). We find that emotion categories enhance the prediction of emotionality in arguments, emphasizing the need for discrete emotion annotations in arguments. Across all prompt settings and models, automatic predictions show a high recall but low precision for predicting anger and fear, indicating a strong bias toward negative emotions.

[Arxiv](https://arxiv.org/abs/2412.15993)