# DeepDubber-V1：致力于高质量对话、旁白与独白的自适应电影配音，创新多模态链式推理引导方案

发布时间：2025年03月30日

`LLM应用`

> DeepDubber-V1: Towards High Quality and Dialogue, Narration, Monologue Adaptive Movie Dubbing Via Multi-Modal Chain-of-Thoughts Reasoning Guidance

# 摘要

> 当前的电影配音技术能够从给定的语音提示生成理想的声音，确保语音与画面的良好同步，并准确传达情感。然而，如何适应不同配音风格、有效处理对白、旁白和独白，以及理解说话者年龄和性别等细节，仍是未充分研究的领域。为解决这一问题，我们提出了一种多模态大语言模型框架。首先，该框架利用多模态链式推理（CoT）方法分析视觉输入，理解配音风格和细粒度属性。其次，通过大型语音生成模型，在多模态条件下生成高质量配音。我们还开发了一个带有CoT注释的电影配音数据集。实验结果表明，相较于现有最优方法，我们的框架在多个数据集上实现了性能提升。具体而言，在V2C Animation数据集上，配音设置2.0的SPK-SIM和EMO-SIM分别从82.48%提升至89.74%，从66.24%提升至78.88%；在Grid数据集上，LSE-D和MCD-SL分别从14.79降至14.63，从5.24降至4.74；在我们的CoT-Movie-Dubbing数据集上，初始推理设置的SPK-SIM从64.03提升至83.42，WER从52.69%降至23.20%，展现出显著优势。

> Current movie dubbing technology can generate the desired voice from a given speech prompt, ensuring good synchronization between speech and visuals while accurately conveying the intended emotions. However, in movie dubbing, key aspects such as adapting to different dubbing styles, handling dialogue, narration, and monologue effectively, and understanding subtle details like the age and gender of speakers, have not been well studied. To address this challenge, we propose a framework of multi-modal large language model. First, it utilizes multimodal Chain-of-Thought (CoT) reasoning methods on visual inputs to understand dubbing styles and fine-grained attributes. Second, it generates high-quality dubbing through large speech generation models, guided by multimodal conditions. Additionally, we have developed a movie dubbing dataset with CoT annotations. The evaluation results demonstrate a performance improvement over state-of-the-art methods across multiple datasets. In particular, for the evaluation metrics, the SPK-SIM and EMO-SIM increases from 82.48% to 89.74%, 66.24% to 78.88% for dubbing setting 2.0 on V2C Animation dataset, LSE-D and MCD-SL decreases from 14.79 to 14.63, 5.24 to 4.74 for dubbing setting 2.0 on Grid dataset, SPK-SIM increases from 64.03 to 83.42 and WER decreases from 52.69% to 23.20% for initial reasoning setting on proposed CoT-Movie-Dubbing dataset in the comparison with the state-of-the art models.

[Arxiv](https://arxiv.org/abs/2503.23660)