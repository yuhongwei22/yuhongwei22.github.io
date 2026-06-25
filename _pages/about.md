---
permalink: /
title: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about"></span>

# 👋 个人简介

我是**余宏伟**,目前在[北京科技大学](https://www.ustb.edu.cn/)攻读计算机科学与技术博士学位(2022.09 至今,预计 2027.06 毕业),研究方向聚焦于 **AIGC、可信人工智能、Diffusion 模型与 Agent**。

迄今为止已发表论文 17 篇、在投 7 篇,其中**第一作者 7 篇、共同一作 5 篇、CCF-A 类会议 13 篇**,工作发表于 ICCV (Spotlight)、ICML、AAAI、ICASSP 等国际顶级会议,并有论文在投 NeurIPS、TPAMI、EMNLP、ACM MM、IJCV。曾获**博士国家奖学金**及**本科生国家奖学金**。

我目前正在京东零售 TGT 顶尖青年技术天才计划参与多模态图像视频生成大模型方向的研究,此前曾在阶跃 (StepFun) 基模组从事 GUI-Agent 后训练,在阿里巴巴高德地图从事 AIGC 方向的研究。

如对学术合作或工作机会感兴趣,欢迎邮件联系:[yuhongwei22@xs.ustb.edu.cn](mailto:yuhongwei22@xs.ustb.edu.cn)。

---

<span class="anchor" id="education"></span>

# 📖 教育经历

- *2022.09 - 至今*,**博士研究生**,北京科技大学 计算机科学与技术,北京  
  &nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#888">获博士国家奖学金</span>
- *2018.09 - 2022.06*,**学士**,北京科技大学 计算机科学与技术,北京  
  &nbsp;&nbsp;&nbsp;&nbsp;<span style="color:#888">获本科生国家奖学金</span>

---

<span class="anchor" id="news"></span>

# 🔥 新闻

- *2026.05*: 加入**京东零售 TGT 顶尖青年技术天才计划**,参与多模态图像视频生成大模型方向。
- *2026.01*: 加入**阶跃 (StepFun) 基模组**,担任 GUI-Agent Post Training 算法实习生。
- *2025.09*: 加入**阿里巴巴高德地图**,担任 AIGC 算法实习生。
- *2025*: 一作论文 **DADet**(基于扩散异常的对抗与后门样本检测)被 **ICCV 2025** 接收为 **Spotlight**。
- *2025*: 一作论文 **MEDUSA**(基于时序注意力谱攻击的视频扩散模型运动消除)被 **ICML 2025** 接收。
- *2025*: 共同一作论文 **FactGuard**(强化学习多模态智能体视频虚假信息检测)被 **ICML 2025** 接收。
- *2024*: 获**博士国家奖学金**。

---

<span class="anchor" id="publications"></span>

# 📝 论文发表

> 共发表 17 篇,在投 7 篇,其中一作 7 篇,共同一作 5 篇,CCF-A 13 篇。**加粗**为本人,\*表示同等贡献。

## AIGC 安全与可信扩散模型

- `ICCV 2025` <span style="color:#d32f2f">(Spotlight)</span> [DADet: Safeguarding Image Conditional Diffusion Models against Adversarial and Backdoor Attacks via Diffusion Anomaly Detection](#) , **Hongwei Yu**, et al.  
  *基于扩散异常现象,联合发散性与同质性,构建针对扩散模型对抗与后门攻击的检测框架。*
- `ICML 2025` [MEDUSA: Motion Elimination in Diffusion Using Spectral Attack](#) , **Hongwei Yu**, et al.  
  *证明视频时序动态等价于注意力矩阵的 Rank-1 退化,通过最小化核范数诱发秩坍缩,阻断 VDMs 运动生成。*
- `AAAI 2024` [Step Vulnerability Guided Mean Fluctuation Adversarial Attack against Conditional Diffusion Models](#) , **Hongwei Yu**, et al.  
  *提出 MFA 均值波动攻击,建模反向步骤脆弱性以引导对抗采样,显著提升攻击效能。*
- `ICASSP` [Defending against Universal Patch Attacks by Restricting Token Attention in Vision Transformers](#) , **Hongwei Yu**, et al.
- `ICCV 2025` <span style="color:#d32f2f">(Spotlight)</span> [Kaleidoscopic Background Attack: Disrupting Pose Estimation with Multi-Fold Radial Symmetry Textures](#) , co-first author.
- `Submitted to TPAMI` [Unveiling Diffusion Anomalies: Passive Detection and Proactive Inversion of Backdoors](#) , **Hongwei Yu**, et al.

## 多模态智能体与虚假信息检测

- `ICML 2025` [FactGuard: Agentic Video Misinformation Detection via Reinforcement Learning](#) , co-first author.  
  *提出代理型框架 FactGuard,引入证据引导动作模块 (FactProbe + ClipScout),通过 SFT + GRPO 优化工具调用策略,在多个数据集达到 SOTA。*
- `Submitted to EMNLP` [Skill-Guided Continuation Distillation for GUI Agents](#) , co-first author.  
  *提出基于 skill 的 continuation distillation 框架,在学生模型自身 rollout 中间状态上引入强模型 supervision,OSWorld-Verified 最高达到 58.4%。*

## 图像融合与扩散模型加速

- `Submitted to NeurIPS` [Towards Speed and Robustness: Hybrid Reinforcement Learning for One-step Degraded Image Fusion](#) , **Hongwei Yu**, et al.  
  *提出 OneHRL,引入 Flow-GRPO 范式,通过 ODE→SDE 注入可控随机性,Qwen2.5-VL × SAM 由粗到细混合奖励,相比扩散方法实现 62.5× 加速。*
- `Submitted to ACM MM` [Recovering Degradations with Generative Model: A Consistency-aware Distillation Network for Infrared and Visible Image Fusion](#) , **Hongwei Yu**, et al.
- `AAAI` [A²rnet: Adversarial Attack Resilient Network for Robust Infrared and Visible Image Fusion](#) , co-first author.

## 其他

- `Submitted to IJCV` [Focusing on Object Relations in Scenes: A Multi-collaborative Graph-structured Framework](#) , co-first author.

---

<span class="anchor" id="internships"></span>

# 💻 实习经历

### 京东零售 TGT 顶尖青年技术天才计划 · 多模态图像视频生成大模型 *(2026.05 - 至今)*

- **商品视频生成一致性与性能优化**:面向电商场景下的商品视频生成任务,提升人物图、背景图、商品图与 prompt 条件下的视频一致性,重点优化人物身份保持、商品细节还原、背景稳定性与跨帧动作连续性。
- **I2V → R2V OPD 探索**:针对两阶段链路(Gemini 生成首帧 → I2V 补充运动)训练负担与目标 R2V 模型的差异,探索使用 I2V 高质量生成结果指导 R2V 训练,通过 OPD 将首帧组合能力与视频生成能力压缩到单阶段 R2V 模型中。

### 阶跃 (StepFun) 基模组 · GUI-Agent Post Training 算法实习生 *(2026.01 - 2026.05)*

- **OSWorld GUI Agent 性能提升**:面向 OSWorld-Verified 真实桌面 GUI Agent benchmark,参与构建 Step → Kimi 的 **k-start continuation distillation** 流程:基模在 VM 中执行前 K 步暴露真实学生状态分布,Kimi/Kimi-guided policy 从该状态继续完成任务,通过 verifier 与轨迹审计筛选成功 continuation,将 recovery action 蒸馏回基模。**OSWorld-Verified 成功率从 40%+ 提升至 60%+**。
- **Skill 引导的脱轨状态延续性蒸馏 (SGCD)**:参与论文设计与实验,提出基于 skill 的 continuation distillation 框架,在多模态 GUI Agent 基座上稳定提升成功率,**最高达到 58.4%**。

### 阿里巴巴 高德地图 · AIGC 算法实习生 *(2025.09 - 2026.01)*

- **FactGuard:结合强化学习的多模态智能体视频虚假信息检测**(ICML Accepted)。将验证过程建模为基于 MLLMs 的迭代决策过程,引入证据引导动作模块 (FactProbe + ClipScout),通过 SFT + GRPO 训练,在多数据集达到 SOTA。
- **OneHRL:基于混合强化学习的单步退化图像融合框架**(NeurIPS Submitted)。引入 Flow-GRPO 范式将 ODE→SDE 注入可控随机性;设计 Qwen2.5-VL 全局语义 + SAM 实例级得分的混合奖励。**相比扩散方法 62.5× 加速,单张仅 0.4s**,在复合退化场景下融合质量与下游感知精度均达到顶级水平。

---

<span class="anchor" id="honors"></span>

# 🎖 荣誉奖项

- 博士生**国家奖学金**
- 本科生**国家奖学金**
- **华为未来之星奖学金**
- **计算机博弈大赛 全国一等奖**
- 三好研究生 / 三好学生
- 校级优秀毕业生

---

<span class="anchor" id="skills"></span>

# 🛠 技能

- **编程语言 / 框架**:Python、PyTorch
- **研究领域**:Diffusion 模型、对抗与后门攻击防御、多模态大模型 (MLLMs)、强化学习 (GRPO / Flow-GRPO)、GUI Agent、图像/视频融合
- **英语**:CET-6
