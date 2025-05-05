# 基于多模态大型语言模型的系统设计与应用，实现事故数据集生成的端到端自动化

发布时间：2025年04月23日

`LLM应用

理由：这篇论文展示了大型语言模型（LLMs）在解决实际问题中的应用，特别是利用LLMs进行网络爬虫、新闻分类和数据提取，以自动化道路交通事故数据的收集。这属于LLM的实际应用，因此归类为LLM应用。` `交通安全` `数据分析`

> Design and Application of Multimodal Large Language Model Based System for End to End Automation of Accident Dataset Generation

# 摘要

> 道路交通事故仍是孟加拉国等发展中国家的重大公共安全和社会经济问题。目前的事故数据收集工作存在手动、分散、不可靠等问题，导致报告不足和记录不一致。本研究提出了一种基于大型语言模型（LLMs）和网络爬虫技术的完全自动化系统，以应对这些挑战。该系统包含四个核心模块：自动化网络爬虫代码生成、在线新闻采集、事故新闻分类与结构化数据提取，以及去重处理。系统采用多模态生成型 LLM Gemini-2.0-Flash 实现全流程自动化。代码生成模块将网页分为分页、动态和无限滚动三类，并为每类生成相应的 Python 爬虫脚本。LLMs 还负责事故新闻的分类，并提取关键信息，包括日期、时间、地点、伤亡人数、道路类型、车辆类型和行人涉入情况。通过去重算法，系统可有效删除重复报告，确保数据完整性。在 2024 年 10 月 1 日至 2025 年 1 月 20 日的 111 天里，该系统爬取了 14 家主要孟加拉国新闻网站，处理了超 1.5 万篇新闻文章，识别出 705 起独立事故。代码生成模块的校准准确率为 91.3%，验证准确率为 80%。统计显示，吉大港的事故数量（80 起）、死亡人数（70 人）和受伤人数（115 人）最多，其次是达卡、法里德布尔、格查普尔和科克斯巴扎尔。事故发生高峰期为上午（8-9 点）、中午（12-1 点）和傍晚（6-7 点）。本研究还开发了一个公开代码仓库，并附有详细使用说明。本研究证明了基于 LLM 的可扩展系统在事故数据收集方面的可行性，为孟加拉国制定基于数据的交通安全政策奠定了基础。

> Road traffic accidents remain a major public safety and socio-economic issue in developing countries like Bangladesh. Existing accident data collection is largely manual, fragmented, and unreliable, resulting in underreporting and inconsistent records. This research proposes a fully automated system using Large Language Models (LLMs) and web scraping techniques to address these challenges. The pipeline consists of four components: automated web scraping code generation, news collection from online sources, accident news classification with structured data extraction, and duplicate removal. The system uses the multimodal generative LLM Gemini-2.0-Flash for seamless automation. The code generation module classifies webpages into pagination, dynamic, or infinite scrolling categories and generates suitable Python scripts for scraping. LLMs also classify and extract key accident information such as date, time, location, fatalities, injuries, road type, vehicle types, and pedestrian involvement. A deduplication algorithm ensures data integrity by removing duplicate reports. The system scraped 14 major Bangladeshi news sites over 111 days (Oct 1, 2024 - Jan 20, 2025), processing over 15,000 news articles and identifying 705 unique accidents. The code generation module achieved 91.3% calibration and 80% validation accuracy. Chittagong reported the highest number of accidents (80), fatalities (70), and injuries (115), followed by Dhaka, Faridpur, Gazipur, and Cox's Bazar. Peak accident times were morning (8-9 AM), noon (12-1 PM), and evening (6-7 PM). A public repository was also developed with usage instructions. This study demonstrates the viability of an LLM-powered, scalable system for accurate, low-effort accident data collection, providing a foundation for data-driven road safety policymaking in Bangladesh.

[Arxiv](https://arxiv.org/abs/2505.00015)