# 基于提示词的大型语言模型能否识别学生背景并在评分过程中产生偏见影响？

发布时间：2025年04月30日

`LLM应用

理由：这篇论文探讨了大型语言模型（LLMs）在自动作文评分（AES）中的应用，特别是基于提示的评分范式。研究关注模型的偏见问题，特别是在评分过程中对弱势群体的偏见，以及模型如何从作文中推断人口统计属性。这些内容属于LLM的实际应用及其在评分系统中的表现，因此归类为LLM应用。` `公平性`

> Does the Prompt-based Large Language Model Recognize Students' Demographics and Introduce Bias in Essay Scoring?

# 摘要

> 大型语言模型（LLMs）凭借其强大的语义理解能力，在自动作文评分（AES）领域得到了广泛应用。传统微调方法需要较高的技术门槛，限制了非技术人员的使用。然而，借助基于提示的工具如ChatGPT，AES变得更加亲民，教育工作者只需通过自然语言提示即可获得机器评分（即基于提示的范式）。尽管技术不断进步，但先前研究表明微调后的LLMs存在偏见，尤其对弱势群体表现明显。目前尚不清楚这种偏见在基于提示的范式和最新工具中是否仍然存在或被放大。鉴于这些偏见可能源于预训练模型中嵌入的人口统计信息（即LLMs文本嵌入预测人口统计属性的能力），本研究旨在探究模型基于学生作文预测其人口统计属性的能力，及其在基于提示范式下评分偏见之间的关系。我们利用一个包含25,000多名学生议论文的公开数据集，设计了提示来提取人口统计推断（如性别、第一语言背景），并评估自动评分的公平性。随后，通过多元回归分析，我们探讨了模型预测人口统计的能力对其评分结果的影响。研究发现：（i）基于提示的LLMs能够从学生作文中推断其人口统计属性，尤其在识别第一语言背景方面表现突出；（ii）当LLMs正确预测学生第一语言背景时，评分偏见更为显著；（iii）对于非英语母语者，当LLMs正确识别其身份时，评分错误率会增加。

> Large Language Models (LLMs) are widely used in Automated Essay Scoring (AES) due to their ability to capture semantic meaning. Traditional fine-tuning approaches required technical expertise, limiting accessibility for educators with limited technical backgrounds. However, prompt-based tools like ChatGPT have made AES more accessible, enabling educators to obtain machine-generated scores using natural-language prompts (i.e., the prompt-based paradigm). Despite advancements, prior studies have shown bias in fine-tuned LLMs, particularly against disadvantaged groups. It remains unclear whether such biases persist or are amplified in the prompt-based paradigm with cutting-edge tools. Since such biases are believed to stem from the demographic information embedded in pre-trained models (i.e., the ability of LLMs' text embeddings to predict demographic attributes), this study explores the relationship between the model's predictive power of students' demographic attributes based on their written works and its predictive bias in the scoring task in the prompt-based paradigm. Using a publicly available dataset of over 25,000 students' argumentative essays, we designed prompts to elicit demographic inferences (i.e., gender, first-language background) from GPT-4o and assessed fairness in automated scoring. Then we conducted multivariate regression analysis to explore the impact of the model's ability to predict demographics on its scoring outcomes. Our findings revealed that (i) prompt-based LLMs can somewhat infer students' demographics, particularly their first-language backgrounds, from their essays; (ii) scoring biases are more pronounced when the LLM correctly predicts students' first-language background than when it does not; and (iii) scoring error for non-native English speakers increases when the LLM correctly identifies them as non-native.

[Arxiv](https://arxiv.org/abs/2504.21330)