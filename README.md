# Hi, I'm sec-jay

恶意软件研究方向学生研究者，聚焦 AI Security、对抗恶意软件生成，以及长期建设更扎实的恶意软件分析与逆向工程能力。  
Malware researcher focused on AI security, adversarial malware generation, and building a deeper long-term foundation in malware analysis and reverse engineering.

这个主页会逐步从“工作 / 专业 brag document”扩展成一个更完整的个人主页，同时也记录我如何学习、成长，并建立支撑长期工作的生活方式。  
This profile is gradually becoming a more complete personal homepage: first as a clear work / professional brag document, and over time as a place that also reflects how I learn, grow, and build a sustainable life around the work.

## About Me | 关于我

我是广州大学网络空间安全学院人工智能方向硕士生，研究位于恶意软件研究与 AI 安全的交叉点。当前主要关注恶意软件生成、对抗样本生成、分布外检测，以及生成模型和强化学习在安全研究中的实际应用。  
I am an MSc student at Guangzhou University, School of Cyberspace Security, working at the intersection of malware research and AI security. My current work centers on malware generation, adversarial sample generation, out-of-distribution detection, and the practical use of generative models and reinforcement learning in security research.

我重视扎实、可复用、能够持续积累的方法，希望自己逐步成长为一个既能做论文、也能做实验、还能深入恶意软件分析实践的人。  
I care about doing rigorous work, building reusable research pipelines, and growing into someone who can move fluently between papers, experiments, and deeper malware analysis practice.

## Work / Professional Highlights | 工作 / 专业亮点

### Research Interests | 研究方向

- 恶意软件生成：关注生成结果的可控性、真实性，以及低痕迹、高规避样本构造  
  Malware generation with an emphasis on controllability, realism, and low-trace, high-evasion sample construction
- 对抗样本生成与安全对抗：特别关注强化学习与对抗生成的结合  
  Adversarial sample generation and security confrontation, especially combining reinforcement learning with adversarial generation
- 逆向学习路线：作为长期方向，持续加强二进制分析与恶意软件行为理解  
  Reverse-engineering learning as a long-term path toward stronger binary analysis and malware behavior understanding

### Publications / Under Review | 论文与在投工作

#### Unknown malware detection based on hyperspherical embedding and out-of-distribution sample detection

- 状态：在投，`IEEE IoTJ`  
  Status: Under Review, IEEE IoTJ
- 亮点：基于超球面嵌入与置信度校准的稳健 OOD 恶意软件检测  
  Highlight: robust OOD malware detection with hyperspherical embedding and calibrated confidence
- 贡献：提出统一的超球面嵌入 + OOD 置信度框架，用于零日检测并降低误报  
  Contribution: a unified hyperspherical embedding + OOD confidence framework for zero-day detection with lower false positives
- 方法：超球面嵌入、`SupCon`、`vMF` 建模、Mahalanobis 置信度判定  
  Method: hyperspherical embedding, `SupCon`, `vMF` modeling, and Mahalanobis-confidence-based detection
- 特征：融合字符串、API、opcode 等多源静态特征，并进行重点特征筛选  
  Features: multi-source static features across strings, APIs, and opcodes, with focused feature selection
- 评估：与 `KNN`、`Malconv`、`CIDER` 等基线进行对比  
  Evaluation: compared against baselines including `KNN`, `Malconv`, and `CIDER`

#### An Evolutionary Strategy-Enhanced Conditional GAN for High-Evasion and Low-Trace Adversarial Malware Generation

- 状态：在投，期刊 / 会议待定  
  Status: Under Review, venue TBD
- 亮点：`ES-CGAN` 在保持 PE 合规扰动的前提下实现高规避与低痕迹  
  Highlight: `ES-CGAN` achieves high evasion with minimal, PE-compliant perturbations
- 贡献：提出一个双层优化框架，在不可微字节空间中平衡规避率与隐蔽性  
  Contribution: a two-level optimization framework bridging non-differentiable byte space with evasion / stealth trade-offs
- 方法：`CMA-ES + CGAN`，面向离散 PE 扰动生成  
  Method: `CMA-ES + CGAN` for discrete PE perturbations
- 结果：在 VirusTotal 上达到 `79.43%` 峰值规避率、`69.60%` 平均 ASR、`0.9%` PBR  
  Result: achieved `79.43%` peak evasion on VirusTotal, `69.60%` mean ASR, and `0.9%` PBR
- 扰动设计：包含符合 PE 结构约束的 DOS / header 修改、节空间填充和新节注入  
  Perturbation design: PE-structure-compliant changes including DOS/header-related edits, section-space padding, and new section injection

#### Research on adversarial-sample-based malware evasion | 基于对抗样本的恶意软件逃逸研究

- 状态：在投，《软件学报》  
  Status: Under Review, Journal of Software
- 亮点：系统梳理对抗恶意软件逃逸方法与开放挑战  
  Highlight: a systematic review of adversarial malware evasion methods and open challenges
- 贡献：构建对抗恶意软件逃逸中的威胁模型与扰动策略统一分类框架  
  Contribution: a unified taxonomy of threat models and perturbation strategies for adversarial malware evasion
- 覆盖内容：攻击构造、扰动策略、评估指标与防御方向  
  Coverage: attack construction, perturbation strategies, evaluation metrics, and defense directions

### Methods & Skills | 方法与技能

- 恶意软件分析 | Malware analysis
- 安全对抗研究 | Security adversarial research
- 生成模型 | Generative models
- 强化学习 | Reinforcement learning
- 分布外检测 | OOD detection
- 数据集构建与预处理 | Dataset curation and preprocessing

## Selected Work / Impact | 代表性工作 / 影响

### Research Projects | 研究项目

#### Adversarial malware generation experiment track | 对抗恶意软件生成实验路线

- 作为对抗恶意软件研究的可复用实验支撑线持续建设  
  Built as a reusable experimental line supporting adversarial malware research
- 已完成 `CycleGAN` 相关实验，并建立基础训练与评估脚本  
  Completed `CycleGAN`-related experiments and established baseline training / evaluation scripts
- 持续拆解 `DQN` 实现，强化对强化学习实验范式的理解  
  Continuing to unpack `DQN` implementations to strengthen reinforcement learning experimentation

#### DataCon dataset reproduction plan | DataCon 数据集复现实验计划

- 已获取奇安信 `DataCon` 比赛数据集  
  Acquired the Qi An Xin `DataCon` competition dataset
- 正在复现基线模型，并搭建更稳定的预处理与评估流程  
  Reproducing baseline models and building a more stable preprocessing and evaluation pipeline
- 目标是形成可复用的恶意软件分析工作流  
  Goal: form a reusable malware analysis workflow for follow-on research

## Current Focus | 当前重点

- 打磨在投论文，提升实验质量与实现细节  
  Refining current papers and improving experiment quality and implementation details
- 复现 `DataCon` 基线并稳定预处理 / 评估流程  
  Reproducing `DataCon` baselines and stabilizing preprocessing / evaluation workflows
- 建立系统化的逆向学习路径，深化恶意软件行为分析能力  
  Building a systematic reverse-engineering learning path for deeper malware behavior analysis

## Beyond Work / Life, Learning & Growth | 工作之外：生活、学习与成长

- 在工作之外继续认真学习，慢慢扩展自己的视野  
  Learning beyond work, slowly and deliberately
- 建立支持长期深度工作的生活技能与可持续习惯  
  Building life skills and sustainable routines that support deep work
- 发展研究之外的创造性与反思性实践  
  Developing creative and reflective practices outside research
- 记录细小但真实的个人成长  
  Documenting small but meaningful personal growth over time

## Notes / Future Pages | 备注 / 未来页面

- [work-brag-document.md](./work-brag-document.md)
- [life-brag-document.md](./life-brag-document.md)
- [now.md](./now.md)

这些页面目前还是占位，后续会逐步从研究型简介扩展成更完整的个人主页。  
These are placeholders for future pages as this profile evolves from a research profile into a broader personal homepage.

## Education | 教育背景

- 广州大学，网络空间安全学院  
  Guangzhou University, School of Cyberspace Security
  
  人工智能硕士，`2025-2027`（预计）  
  MSc in Artificial Intelligence, `2025-2027` (expected)

- 海南大学，土木建筑工程学院  
  Hainan University, College of Civil Engineering & Architecture
  
  工程管理本科，`2017-2021`  
  BEng in Engineering Management, `2017-2021`

## Connect | 联系方式

- 邮箱 | Email: `2112433088@e.gzhu.edu.cn`
- GitHub：[`sec-jay`](https://github.com/sec-jay)  
  GitHub: [`sec-jay`](https://github.com/sec-jay)
- Google Scholar：持续完善中  
  Google Scholar: profile in progress
- CV：后续补充链接 / 可按需提供  
  CV: available on request / profile link to be added
