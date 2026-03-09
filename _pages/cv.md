---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* 2022.09 - 2025.06    东北大学 - 计算机科学与技术（硕士） 
* 2018.09 - 2022.06    东北大学 - 物联网工程（本科）

Honors and Awards
======
* 东北大学校长奖学金
* 2022-2024 年 3 次东北大学一等学业奖学金
* 华为昇思 MindCon 个人赛二等奖
* 通义千问 AI 挑战赛 — Agent Builder 创意挑战赛 人气作品奖
* 天池 AICAS 2024 大挑战：通用算力大模型推理性能软硬协同优化挑战赛 优胜奖（17/218）

Work experience
======

* 2024.08 - 2025.06    浙江清华长三角研究院 — NLP 算法实习生
  * 使用 lm-evaluation-harness 评测、分析 LLM 在 C-eval 数据集上的性能，维护评测表并形成测试流程 SOP 文档，减少后续测试工作量
  * 基于 Slurm 作业调度系统，在 Arm CPU + Nvidia GPU 平台打通 Deepspeed 多机多卡训练全流程并形成 SOP 文档

* 2024.06 - 2024.08    深度赋智 — 算法研究员（实习）
  * 研究不同 LLM Agent Ensemble 策略在 Code Patch 生成上的性能，设计 ensemble 策略并通过筛选生成结果，效果提升 4%
  * 研究不同 LLM Debate 策略在 Code Patch 生成上的性能
  * 使用 mem0 实现 LLM Code Patch 生成过程记忆，优化 prompt 与记忆历史存储，Recall@5 从 60% 提升至 85.7%

* 2023.08 - 2024.04    阿里云智能 — 学术合作实习生
  * 预研大语言模型（LLM）、RAG 方法与微调技术，结合云网络业务挖掘可提升服务质量或解决业务困难的场景
  * 基于 Qwen-Max、RAG 与微调设计解决方案，使用 LangChain 实现工具调用与定制，并设计向量检索方案（FAISS、text2-vec-large、multi-qa-MiniLM-L6-cos-v1）
  * 基于 Gradio 搭建 Demo 服务，使用 Docker 部署与测试，汇总预研结果与 Demo 信息，撰写文档与 PPT 汇报

Competition Projects
======
* BetterSynth 多模态大模型数据合成挑战赛 —— 天池季军、最佳展示奖（4/1066）
  * 探究合成数据对多模态大模型训练的影响，探索高效数据合成方法与策略
  * 在 baseline 基础上评估 CLIP、BLIP 的数据筛选能力并据此设计数据合成方案，较 baseline 提升 150%

* BetterMixture 大模型数据混合挑战赛 —— 天池优胜奖（14/417）
  * 使用开源模型与正则表达式进行标注与筛选，确保高质量数据选取
  * 对垃圾数据进行打标与过滤，确保数据清洁
  * 使用 simhash、minhash 与基于语义编码的相似度进行多粒度去重，从数百万条数据中筛选高质量数据
  * 定向混入高数学得分且包含数学等式的数据，强化模型数学能力提升

* 首届明厨亮灶 AI 算法大赛 —— 天池分享奖（12/449）
  * 筛选高质量数据并进行数据增强，解决小样本、多标签分类问题
  * 微调 clip-vit-large-patch14 预训练模型，迭代优化参数提升性能
  * 推理侧采用暴力裁剪、多物体识别与差帧法裁剪关键帧，并加入地板检测避免误判；通过并行推理与内存/显存管理优化提升推理速度与资源利用率
  
Skills
======
* 深度学习框架
  * PyTorch；Transformer
  * 多模态模型：CLIP/BLIP；CLIP 系列
  * 大模型：Qwen系列等
* 大模型应用
  * Agent：Ensemble、Debate；Code Patch 生成；mem0 记忆增强
  * RAG：FAISS；向量检索与召回优化
  * 工具链：LangChain
* 训练与工程
  * DeepSpeed 多机多卡；Slurm；Arm CPU + Nvidia GPU
  * 评测：lm-evaluation-harness；C-Eval（SOP）
  * 数据：正则清洗/标注；simhash/minhash/语义去重
  * 交付：Gradio；Docker
* 语言与其他：CET-6；长跑/乒乓球/徒步/羽毛球

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
