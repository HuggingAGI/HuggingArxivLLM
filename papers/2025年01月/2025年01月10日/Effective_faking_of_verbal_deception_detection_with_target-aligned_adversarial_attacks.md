# 利用目标对齐的对抗攻击，有效伪造言语欺骗检测

发布时间：2025年01月10日

`LLM应用

理由：这篇论文主要讨论了使用大型语言模型（LLM）来重写欺骗性陈述，使其看起来真实，并评估了人类和机器学习模型在欺骗检测任务中的表现。论文的核心在于LLM在欺骗检测中的应用，特别是如何通过对抗性修改来影响人类和机器的判断。因此，这篇论文应归类为“LLM应用”。` `欺骗检测` `语言模型`

> Effective faking of verbal deception detection with target-aligned adversarial attacks

# 摘要

> 背景：通过语言分析进行欺骗检测是一个充满潜力的领域，既依赖人类判断，也依赖自动化机器学习判断。然而，自动化对抗攻击通过重写欺骗性陈述使其显得真实，对这两种可信度评估方式构成了严重威胁。方法：我们在欺骗检测任务中使用了一个包含243个真实和262个虚构自传故事的数据集，供人类和机器学习模型评估。一个大型语言模型被用来重写欺骗性陈述，使其看起来真实。在研究1中，人类通过欺骗判断或详细性启发式，以及两个机器学习模型（一个微调的语言模型和一个简单的n-gram模型），对原始或对抗性修改的欺骗性陈述进行了评估。在研究2中，我们调整了修改的目标对齐，即根据评估者是人类还是计算机模型来定制攻击。结果：当对抗性修改与目标对齐时，人类（d=-0.07和d=-0.04）和机器判断（51%准确率）降至随机水平。当攻击未与目标对齐时，人类启发式判断（d=0.30和d=0.36）和机器学习预测（63-78%）显著优于随机。结论：易于使用的语言模型可以有效帮助任何人伪造欺骗检测结果，无论是针对人类还是机器学习模型。人类和机器对对抗性修改的鲁棒性取决于目标对齐。最后，我们提出了通过对抗攻击设计推进欺骗研究的建议。

> Background: Deception detection through analysing language is a promising avenue using both human judgments and automated machine learning judgments. For both forms of credibility assessment, automated adversarial attacks that rewrite deceptive statements to appear truthful pose a serious threat. Methods: We used a dataset of 243 truthful and 262 fabricated autobiographical stories in a deception detection task for humans and machine learning models. A large language model was tasked to rewrite deceptive statements so that they appear truthful. In Study 1, humans who made a deception judgment or used the detailedness heuristic and two machine learning models (a fine-tuned language model and a simple n-gram model) judged original or adversarial modifications of deceptive statements. In Study 2, we manipulated the target alignment of the modifications, i.e. tailoring the attack to whether the statements would be assessed by humans or computer models. Results: When adversarial modifications were aligned with their target, human (d=-0.07 and d=-0.04) and machine judgments (51% accuracy) dropped to the chance level. When the attack was not aligned with the target, both human heuristics judgments (d=0.30 and d=0.36) and machine learning predictions (63-78%) were significantly better than chance. Conclusions: Easily accessible language models can effectively help anyone fake deception detection efforts both by humans and machine learning models. Robustness against adversarial modifications for humans and machines depends on that target alignment. We close with suggestions on advancing deception research with adversarial attack designs.

[Arxiv](https://arxiv.org/abs/2501.05962)