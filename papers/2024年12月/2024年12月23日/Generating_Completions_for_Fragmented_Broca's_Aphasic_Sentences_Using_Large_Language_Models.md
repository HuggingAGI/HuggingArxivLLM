# 利用大型语言模型为布洛卡失语症患者的碎片化句子生成完整内容

发布时间：2024年12月23日

`LLM应用` `失语症治疗`

> Generating Completions for Fragmented Broca's Aphasic Sentences Using Large Language Models

# 摘要

> 布罗卡失语症是一种言语产出不流畅、费劲且破碎，但理解能力相对不错的失语症类型。鉴于传统的失语症治疗手段往往费时费力，还无法体现真实世界的对话场景，采用诸如大型语言模型（LLMs）这类基于自然语言处理的方法，或许能助力改进现有的治疗方式。为应对这一问题，我们探索运用序列到序列的LLMs来完善布罗卡失语症患者支离破碎的语句。我们先是利用基于规则的系统生成模拟布罗卡失语症言语语言特征的合成数据，接着用这些合成数据对四个预训练的LLMs在完成破碎句子的任务上进行微调。我们在合成及真实的布罗卡失语症数据上对微调后的模型予以评估。我们展示了LLMs重建破碎句子的能力，模型在输入话语较长时性能更优。我们的成果凸显了LLMs在为布罗卡失语症患者以及可能的其他临床人群推动交流辅助工具方面的潜力。

> Broca's aphasia is a type of aphasia characterized by non-fluent, effortful and fragmented speech production with relatively good comprehension. Since traditional aphasia treatment methods are often time-consuming, labour-intensive, and do not reflect real-world conversations, applying natural language processing based approaches such as Large Language Models (LLMs) could potentially contribute to improving existing treatment approaches. To address this issue, we explore the use of sequence-to-sequence LLMs for completing fragmented Broca's aphasic sentences. We first generate synthetic Broca's aphasic data using a rule-based system designed to mirror the linguistic characteristics of Broca's aphasic speech. Using this synthetic data, we then fine-tune four pre-trained LLMs on the task of completing fragmented sentences. We evaluate our fine-tuned models on both synthetic and authentic Broca's aphasic data. We demonstrate LLMs' capability for reconstructing fragmented sentences, with the models showing improved performance with longer input utterances. Our result highlights the LLMs' potential in advancing communication aids for individuals with Broca's aphasia and possibly other clinical populations.

[Arxiv](https://arxiv.org/abs/2412.17669)