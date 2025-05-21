# VideoEval-Pro：强健且真实的长视频理解评测

发布时间：2025年05月20日

`LLM应用

摘要讨论了大型多模态模型（LMMs）在长视频理解（LVU）中的应用，提出了新的评估基准VideoEval-Pro。这属于LLM的应用层面，因为它关注如何应用模型以及如何更有效地评估它们的性能。` `视频分析` `评估基准`

> VideoEval-Pro: Robust and Realistic Long Video Understanding Evaluation

# 摘要

> 大型多模态模型（LMMs）近年来在长视频理解（LVU）领域表现突出，推动了标准化评估基准的开发。然而，我们对现有LVU基准的研究揭示了几个关键问题：首先，大多数基准过度依赖多项选择题（MCQs），其评估结果因可能的猜测而被夸大；其次，这些基准中的许多问题具有强烈先验，使得模型无需观看视频即可直接回答。例如，Gemini-1.5-Pro仅凭长视频的随机一帧即可在Video-MME上达到50%以上的准确率。我们还发现，增加帧数并不一定能提升现有基准的表现，这一现象违反直觉。因此，现有LVU基准的有效性和可靠性受到质疑，限制了对LMMs长视频理解能力的准确评估。为了解决这一问题，我们提出了VideoEval-Pro，这是一个包含开放性简答题的现实LVU基准，真正要求理解整个视频内容。VideoEval-Pro通过感知和推理任务，评估段落级和全视频理解能力。通过对21个专有和开源的视频LMMs进行评估，我们得出以下结论：（1）视频LMMs在开放性问题上的性能比MCQs下降超过25%；（2）令人惊讶的是，更高的MCQ分数并不一定带来VideoEval-Pro上的更高开放性得分；（3）与其他MCQ基准相比，VideoEval-Pro从增加输入帧数中受益更多。我们的研究表明，VideoEval-Pro为长视频理解提供了一个更现实和可靠的评估标准，为该领域的发展提供了更清晰的视角。

> Large multimodal models (LMMs) have recently emerged as a powerful tool for long video understanding (LVU), prompting the development of standardized LVU benchmarks to evaluate their performance. However, our investigation reveals a rather sober lesson for existing LVU benchmarks. First, most existing benchmarks rely heavily on multiple-choice questions (MCQs), whose evaluation results are inflated due to the possibility of guessing the correct answer; Second, a significant portion of questions in these benchmarks have strong priors to allow models to answer directly without even reading the input video. For example, Gemini-1.5-Pro can achieve over 50\% accuracy given a random frame from a long video on Video-MME. We also observe that increasing the number of frames does not necessarily lead to improvement on existing benchmarks, which is counterintuitive. As a result, the validity and robustness of current LVU benchmarks are undermined, impeding a faithful assessment of LMMs' long-video understanding capability. To tackle this problem, we propose VideoEval-Pro, a realistic LVU benchmark containing questions with open-ended short-answer, which truly require understanding the entire video. VideoEval-Pro assesses both segment-level and full-video understanding through perception and reasoning tasks. By evaluating 21 proprietary and open-source video LMMs, we conclude the following findings: (1) video LMMs show drastic performance ($>$25\%) drops on open-ended questions compared with MCQs; (2) surprisingly, higher MCQ scores do not lead to higher open-ended scores on VideoEval-Pro; (3) compared to other MCQ benchmarks, VideoEval-Pro benefits more from increasing the number of input frames. Our results show that VideoEval-Pro offers a more realistic and reliable measure of long video understanding, providing a clearer view of progress in this domain.

[Arxiv](https://arxiv.org/abs/2505.14640)