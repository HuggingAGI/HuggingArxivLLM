# 从深层挖掘语义：手势合成的 RAG 解决方案

发布时间：2024年12月09日

`RAG` `手势生成` `非言语交流`

> Retrieving Semantics from the Deep: an RAG Solution for Gesture Synthesis

# 摘要

> 非言语交流往往包含语义丰富的手势，有助于传达话语之意。现有的神经系统能生成有节奏的节拍手势，却难以产出有语义的手势，所以生成此类语义伴随言语的手势一直是个重大挑战。为此，我们推出了 RAG-Gesture，这是一种基于扩散的手势生成方式，借助检索增强生成（RAG）来打造自然且语义丰富的手势。我们的神经显式手势生成方法旨在生成基于可解释语言知识的语义手势。我们利用显式领域知识从伴随言语手势的数据库中检索示例动作来达成此目的。一旦检索完成，在推理时，我们通过 DDIM 反演和检索引导将这些语义示例手势注入基于扩散的手势生成流程，无需任何训练。另外，我们还提出了一种用于引导的控制范例，使用户能够调节每次检索插入对生成序列的影响程度。我们的对比评估证实了我们的方法相较于近期手势生成方法的有效性。诚邀读者在我们的项目页面查看结果。

> Non-verbal communication often comprises of semantically rich gestures that help convey the meaning of an utterance. Producing such semantic co-speech gestures has been a major challenge for the existing neural systems that can generate rhythmic beat gestures, but struggle to produce semantically meaningful gestures. Therefore, we present RAG-Gesture, a diffusion-based gesture generation approach that leverages Retrieval Augmented Generation (RAG) to produce natural-looking and semantically rich gestures. Our neuro-explicit gesture generation approach is designed to produce semantic gestures grounded in interpretable linguistic knowledge. We achieve this by using explicit domain knowledge to retrieve exemplar motions from a database of co-speech gestures. Once retrieved, we then inject these semantic exemplar gestures into our diffusion-based gesture generation pipeline using DDIM inversion and retrieval guidance at the inference time without any need of training. Further, we propose a control paradigm for guidance, that allows the users to modulate the amount of influence each retrieval insertion has over the generated sequence. Our comparative evaluations demonstrate the validity of our approach against recent gesture generation approaches. The reader is urged to explore the results on our project page.

[Arxiv](https://arxiv.org/abs/2412.06786)