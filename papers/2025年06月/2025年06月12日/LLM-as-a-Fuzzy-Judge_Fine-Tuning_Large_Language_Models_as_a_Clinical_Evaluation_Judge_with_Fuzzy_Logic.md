# LLM 作为模糊裁判：基于模糊逻辑的临床评估裁判微调

发布时间：2025年06月12日

`LLM应用` `医学教育` `教育技术`

> LLM-as-a-Fuzzy-Judge: Fine-Tuning Large Language Models as a Clinical Evaluation Judge with Fuzzy Logic

# 摘要

> 临床沟通技巧在医学教育中至关重要，但规模化练习和评估这些技巧充满挑战。尽管基于LLM的临床情景模拟显示出提升医学生临床实践的潜力，但实现遵循细腻医师判断的自动化和规模化临床评估仍然困难。本文结合模糊逻辑和大型语言模型（LLM），提出LLM-as-a-Fuzzy-Judge方法，旨在解决将医学生临床技能的自动化评估与主观医师偏好相匹配的难题。

LLM-as-a-Fuzzy-Judge是一种将LLM微调以根据来自四个模糊集（包括专业性、医学相关性、伦理行为和情境分心）的人类注释来评估学生与AI患者对话脚本中学生发言的方法。本文的方法从基于LLM的医学教育系统收集数据开始，基于多维模糊集进行数据标注，随后进行提示工程，并使用这些人类注释对预训练的LLM进行有监督微调（SFT）。

实验结果显示，LLM-as-a-Fuzzy-Judge的准确率超过80%，主要评估指标超过90%，成功利用模糊逻辑和LLM作为解决方案，提供可解释且符合人类判断的评估。这项工作表明，结合模糊逻辑和LLM与人类偏好对齐是可行的，推动了医学教育中的自动化评估，并支持了更强大的评估和判断实践。该工作的GitHub仓库地址为https://github.com/2sigmaEdTech/LLMAsAJudge

> Clinical communication skills are critical in medical education, and practicing and assessing clinical communication skills on a scale is challenging. Although LLM-powered clinical scenario simulations have shown promise in enhancing medical students' clinical practice, providing automated and scalable clinical evaluation that follows nuanced physician judgment is difficult. This paper combines fuzzy logic and Large Language Model (LLM) and proposes LLM-as-a-Fuzzy-Judge to address the challenge of aligning the automated evaluation of medical students' clinical skills with subjective physicians' preferences. LLM-as-a-Fuzzy-Judge is an approach that LLM is fine-tuned to evaluate medical students' utterances within student-AI patient conversation scripts based on human annotations from four fuzzy sets, including Professionalism, Medical Relevance, Ethical Behavior, and Contextual Distraction. The methodology of this paper started from data collection from the LLM-powered medical education system, data annotation based on multidimensional fuzzy sets, followed by prompt engineering and the supervised fine-tuning (SFT) of the pre-trained LLMs using these human annotations. The results show that the LLM-as-a-Fuzzy-Judge achieves over 80\% accuracy, with major criteria items over 90\%, effectively leveraging fuzzy logic and LLM as a solution to deliver interpretable, human-aligned assessment. This work suggests the viability of leveraging fuzzy logic and LLM to align with human preferences, advances automated evaluation in medical education, and supports more robust assessment and judgment practices. The GitHub repository of this work is available at https://github.com/2sigmaEdTech/LLMAsAJudge

[Arxiv](https://arxiv.org/abs/2506.11221)