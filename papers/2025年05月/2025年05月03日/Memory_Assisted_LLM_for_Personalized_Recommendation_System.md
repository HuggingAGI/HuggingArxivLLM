# # 内存辅助的大型语言模型助力个性化推荐系统

发布时间：2025年05月03日

`LLM应用

论文摘要：大型语言模型（LLMs）在推荐任务中展现出巨大潜力，尤其在理解用户偏好方面表现出色。当前研究通过提示设计和微调探索个性化推荐，但现有方法在捕捉用户偏好或更新历史时存在局限。为此，我们提出记忆增强个性化LLM（MAP）。MAP通过用户交互创建历史档案，记录偏好，并在推荐时提取相似记忆融入提示，提升个性化推荐效果。实验中，我们在单领域和跨领域场景下评估MAP，结果表明其优于传统LLM推荐器，且随着用户历史增长，优势更加明显。这使其成为处理连续个性化请求的理想选择。

LLM应用` `推荐系统`

> Memory Assisted LLM for Personalized Recommendation System

# 摘要

> 大型语言模型（LLMs）在推荐任务中展现出巨大潜力，尤其在理解用户偏好方面表现出色。当前研究通过提示设计和微调探索个性化推荐，但现有方法在捕捉用户偏好或更新历史时存在局限。为此，我们提出记忆增强个性化LLM（MAP）。MAP通过用户交互创建历史档案，记录偏好，并在推荐时提取相似记忆融入提示，提升个性化推荐效果。实验中，我们在单领域和跨领域场景下评估MAP，结果表明其优于传统LLM推荐器，且随着用户历史增长，优势更加明显。这使其成为处理连续个性化请求的理想选择。

> Large language models (LLMs) have demonstrated significant potential in solving recommendation tasks. With proven capabilities in understanding user preferences, LLM personalization has emerged as a critical area for providing tailored responses to individuals. Current studies explore personalization through prompt design and fine-tuning, paving the way for further research in personalized LLMs. However, existing approaches are either costly and inefficient in capturing diverse user preferences or fail to account for timely updates to user history. To address these gaps, we propose the Memory-Assisted Personalized LLM (MAP). Through user interactions, we first create a history profile for each user, capturing their preferences, such as ratings for historical items. During recommendation, we extract relevant memory based on similarity, which is then incorporated into the prompts to enhance personalized recommendations. In our experiments, we evaluate MAP using a sequential rating prediction task under two scenarios: single domain, where memory and tasks are from the same category (e.g., movies), and cross-domain (e.g., memory from movies and recommendation tasks in books). The results show that MAP outperforms regular LLM-based recommenders that integrate user history directly through prompt design. Moreover, as user history grows, MAP's advantage increases in both scenarios, making it more suitable for addressing successive personalized user requests.

[Arxiv](https://arxiv.org/abs/2505.03824)