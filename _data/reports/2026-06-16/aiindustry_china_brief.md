## AI产业简报 — 中国

### 摘要
2026年6月，中国AI产业正处于从"进口替代"向"自主创新"加速转型的关键节点。阿里巴巴平头哥镇武M890芯片累计出货56万颗，标志着国产AI芯片规模化商用取得实质性突破；DeepSeek V4系列在开源模型领域实现全球领先，并完成华为昇腾芯片深度适配。美国对华芯片出口管制持续升级——H20于3月被禁、H200虽获许可但至今未实际发货——反而加速了中国AI算力自主化进程。产业整体处于成长期向成熟期过渡阶段，硬件层和模型层国产化率快速提升是当前最核心的结构性趋势。

### 能源层 (Energy)
- **电力供应**: "东数西算"工程持续推进，西部数据中心节点（贵州、内蒙古等）电力富余度超过20%，电价显著低于东部。以GPT-3级别模型单次训练为例，宁夏电力成本约22万元，广东则需近44万元，成本差距约2倍。
- **冷却技术**: 西部自然冷却条件优越（年均气温低），进一步降低数据中心PUE。大型数据中心PUE目标已降至1.2以下。
- **可持续性**: 国家超算互联网联合体持续推进算力统筹调度，目标到2025年底形成一体化算力服务平台。AI大模型高能耗需求正加速算力向西部迁移。
- **投资含义**: 西部数据中心运营商、液冷/冷却设备供应商受益；东部高电价地区中小型IDC面临成本压力。

### 硬件层 (Hardware)
- **芯片 — 国产替代加速**:
  - **阿里巴巴平头哥镇武M890**: 2026年5月19日正式发布，为第三代AI加速器。配备96GB+ HBM3内存，训练吞吐量为前代镇武810E的3倍，推理性能超越Nvidia H20，综合性能约为H100的0.75倍（自报数据，待第三方验证）。支持CUDA兼容软件层，PyTorch工作负载无需重写即可运行。截至2026年5月，平头哥已累计出货**56万颗镇武芯片**（含810E和M890），覆盖**400+企业客户、20个行业**，包括国家电网、中国科学院、小鹏汽车等。平均每家外部客户部署约1,400颗芯片。
  - **华为昇腾910B**: DeepSeek V4系列已深度适配华为昇腾超节点全系列产品，实现V4-Pro 20ms和V4-Flash 10ms低时延推理。这标志着中国在无需Nvidia硬件的情况下开发前沿AI能力取得里程碑式进展。
  - **寒武纪等国产芯片厂商**: 面临阿里巴巴平头哥的强力竞争，后者凭借阿里云生态和应用场景优势，出货量已超越寒武纪。
- **美国出口管制动态**:
  - H20芯片于2026年3月被正式禁止对华出口。
  - H200芯片虽于2026年1月获美国政府许可（附加25%关税和第三方安全检测要求），但截至4月底仍未实际发货。字节跳动、阿里巴巴、腾讯已下单超过40万颗H200，但交付受阻。
  - 2026年6月1日，美国进一步将禁令扩展至中国企业在海外设立的子公司。
  - **核心结论**: 出口管制实际效果与预期相反——管制创造了受保护的国内市场，保障了国企采购，为平头哥提供了持续研发三代芯片的收入确定性。
- **服务器与数据中心**: 万卡集群成为国产AI芯片部署标配，镇武M890已在阿里云上以万卡集群运行。华为昇腾超节点支持大规模推理部署。
- **投资含义**: 国产AI芯片产业链（平头哥/阿里生态、华为昇腾生态）是最大受益方向；传统Nvidia分销商和依赖进口芯片的算力租赁商面临结构性风险。

### 软件层 (Software)
- **云平台**: 阿里云凭借镇武芯片形成"芯片+云"垂直整合优势，提供端到端的国产AI算力解决方案。华为云依托昇腾生态构建全栈AI能力。腾讯云、字节火山引擎在模型服务层竞争激烈。
- **开发框架**: 平头哥镇武M890提供CUDA兼容软件层，大幅降低迁移成本。DeepSeek通过自研CUDA等效内核、MoE架构优化和基础设施级批处理改进，在华为昇腾上大幅缩小推理性能差距。
- **企业渗透**: 镇武芯片已进入20个行业、400+企业客户，表明国产AI芯片的企业渗透正在从试点走向规模化。DeepSeek V4 API已集成Claude Code、OpenClaw、OpenCode等主流AI Agent框架。
- **投资含义**: 阿里云（芯片+云一体化）、华为云（昇腾+全栈）受益于国产替代趋势；第三方独立云厂商面临差异化竞争压力。

### 模型层 (Models)
- **能力演进 — DeepSeek V4引领开源前沿**:
  - **DeepSeek V4-Pro**: 2026年4月24日正式发布并开源。总参数1.6T/激活参数49B。性能比肩全球顶级闭源模型。三大核心优势：(1) Agent能力大幅提升，开源SOTA；(2) 世界知识领先所有开源模型，仅次于Gemini-3.1-Pro；(3) 推理性能超越所有已公开评测的开源模型，在数学/STEM/竞赛代码领域媲美顶级闭源模型。
  - **DeepSeek V4-Flash**: 总参数284B/激活参数13B。推理能力接近V4-Pro，在简单Agent任务上表现持平。更小参数带来更快响应和更低API成本。
  - **技术创新**: 新型注意力机制（Token-wise压缩 + DeepSeek Sparse Attention），实现世界领先的长上下文效率。**100万token上下文成为所有官方服务的默认配置**。
  - **国产化落地**: 华为昇腾超节点全系列支持DeepSeek V4，实现低时延推理。DeepSeek估值或超200亿美元。
- **其他国产大模型动态**:
  - **智谱AI (Z.ai, 02513.HK)**: 已港股上市，发布GLM-5模型。产品矩阵包括ChatGLM、AutoGLM（Agent）、AutoClaw等。
  - **阿里巴巴通义千问 (Qwen)**: 持续迭代，与镇武芯片形成"模型+芯片"协同。
  - **字节跳动豆包 (Doubao)**: 依托抖音生态，在消费端AI应用占据领先地位。
  - **月之暗面 (Moonshot/Kimi)**: 专注长上下文能力。
  - **百度文心一言 (ERNIE)**: 依托搜索和自动驾驶生态。
  - **科大讯飞星火**: 深耕教育、医疗等垂直场景。
  - 其他重要玩家: MiniMax、百川智能、零一万物、阶跃星辰、昆仑天工。
- **成本趋势**: DeepSeek V4-Flash以极低API成本提供接近旗舰模型的推理能力，推动模型API价格持续下行。DeepSeek将于2026年7月24日全面退役旧版deepseek-chat和deepseek-reasoner API。
- **商业化**: 模型层竞争格局从"参数竞赛"转向"Agent能力+成本效率+国产化适配"三维竞争。
- **投资含义**: DeepSeek生态（算力供应商、应用开发商）受益于开源领先地位；智谱AI作为港股上市标的值得关注；模型API价格下行利好应用层，但对纯模型厂商毛利率形成压力。

### 应用层 (Applications)
- **企业AI**: 镇武芯片覆盖20个行业400+企业客户，表明企业级AI部署正在从互联网行业向传统行业（电力、制造、汽车）扩散。DeepSeek V4已深度集成主流AI Agent框架（Claude Code、OpenClaw、OpenCode），推动Agentic Coding在企业场景落地。
- **消费AI**: 字节豆包依托抖音生态在C端占据领先；DeepSeek App提供免费访问，持续扩大用户基础；Kimi以长文档分析差异化竞争。
- **垂直应用**:
  - **自动驾驶**: 百度Apollo/萝卜快跑持续推进robotaxi商业化；小鹏汽车已采用镇武芯片进行车载AI研发。
  - **AI Agent**: DeepSeek V4的Agent能力大幅提升，智谱AutoGLM实现跨app、跨设备Agent操作。Agent从"概念验证"进入"工程化落地"阶段。
  - **AI编程**: DeepSeek V4已在内部驱动Agentic Coding，CodeGeeX等国产编程助手持续迭代。
- **投资含义**: AI Agent平台和工具链是下一阶段增长最快的细分方向；自动驾驶robotaxi商业化进入加速期；消费AI应用关注用户留存和变现能力。

### 政策趋势
- **产业支持**:
  - 国家超算互联网联合体持续推进，构建全国一体化算力服务平台。
  - "东数西算"工程加速算力向西部迁移，政策端持续发力。
  - 地方政府AI支持政策密集出台，中关村自主大模型产业联盟等行业组织推动生态建设。
  - 国家大基金持续投入半导体和AI芯片领域。
- **监管方向**:
  - 美国对华芯片出口管制持续升级：H20被禁（2026年3月）→ H200许可但未发货 → 禁令扩展至海外子公司（2026年6月）。
  - 中国数据安全法和算法推荐管理规定持续完善，AI生成内容监管框架逐步细化。
  - 国产替代和自主可控上升为国家战略高度，芯片自给率目标持续推进。
- **关键判断**: 美国出口管制的持续升级正在反向加速中国AI芯片自主化进程。每一轮管制升级→Nvidia设计降级芯片→中国大规模部署→美国再禁→中国国产替代加速，这一循环已推动平头哥在不到三年内完成三代芯片迭代。

### 产业成熟度评估
| 产业层 | 当前阶段 | 阶段特征 | 趋势 |
|--------|----------|----------|------|
| 能源 | 成长期 | 东数西算推动西部算力中心建设，电力成本优势明显，PUE持续优化 | 加速 |
| 硬件 | 成长期（加速国产替代） | 国产AI芯片从试点走向规模化（56万颗出货），万卡集群商用，但性能仍落后H100约25% | 加速 |
| 软件 | 成长期 | 国产芯片CUDA兼容层降低迁移成本，云平台垂直整合加速，但生态完善度仍不及Nvidia CUDA | 稳定 |
| 模型 | 成长期（向成熟期过渡） | DeepSeek V4开源领先全球，国产模型能力比肩顶级闭源模型，华为昇腾适配完成，API价格持续下行 | 加速 |
| 应用 | 成长期早期 | AI Agent从概念验证进入工程化落地，企业AI向传统行业扩散，但规模化收入和盈利模式仍在验证中 | 加速 |

### 投资含义
- **周期定位**: 中国AI产业处于成长期中段向成熟期过渡阶段。硬件层和模型层的国产替代是最核心的结构性驱动力，预计将持续2-3年。
- **受益板块**:
  - **国产AI芯片产业链**: 阿里巴巴（平头哥镇武芯片+阿里云垂直整合）、华为昇腾生态合作伙伴
  - **国产大模型龙头**: DeepSeek生态相关算力供应商和应用开发商；智谱AI（港股02513.HK）
  - **西部数据中心**: 受益于东数西算和AI算力需求爆发
  - **AI Agent/应用工具链**: 受益于模型能力提升和Agent工程化落地
  - **自动驾驶**: 百度Apollo/萝卜快跑商业化加速
- **风险板块**:
  - Nvidia芯片分销商和依赖进口GPU的算力租赁商（结构性替代风险）
  - 缺乏差异化优势的中小模型厂商（API价格战和开源模型冲击）
  - 东部高电价地区中小型IDC（成本劣势）
- **主题机会**:
  - 近期催化剂: DeepSeek V4正式版发布（Preview后续）、美国出口管制进一步动态、国产AI芯片第三方性能验证报告
  - 中长期主题: 国产AI芯片从推理向训练全面替代、AI Agent规模化商用、自动驾驶robotaxi全面落地

### 数据来源
- [Alibaba Group — Zhenwu M890 official announcement, May 2026](https://www.alibabagroup.com/en-US/document-1994119844504535040) — 镇武M890芯片规格和出货数据
- [CNBC — Alibaba reveals more powerful Zhenwu AI chip, May 19 2026](https://www.cnbc.com/2026/05/19/alibaba-reveals-more-powerful-zhenwu-ai-chip-new-llm.html) — 镇武M890发布报道
- [South China Morning Post — Alibaba AI chip push hits 100,000 mark](https://www.scmp.com/tech/article/3341860/alibaba-ai-chip-push-hits-100000-mark-beating-local-rival-cambricon-sources) — 镇武芯片出货里程碑
- [Caixin Global — Alibaba processor shows applications are key to AI chip success](https://www.caixinglobal.com/2026-02-03/analysis-alibabas-new-processor-shows-applications-are-key-to-ai-chip-success-102411054.html) — 应用生态对AI芯片成功的关键作用
- [CSIS — China's localization drive in semiconductors](https://www.csis.org/analysis/chinas-localization-drive-semiconductors-gains-impetus-allied-chip-export-controls) — 中国半导体国产化趋势
- [Al Jazeera — US says ban on AI chip shipments applies to Chinese firms outside China](https://www.aljazeera.com/economy/2026/6/1/us-says-ban-on-ai-chip-shipments-applies-to-chinese-firms-outside-china) — 美国禁令扩展至海外子公司
- [DeepSeek V4 Preview Release — API Docs](https://api-docs.deepseek.com/news/news260424) — DeepSeek V4技术规格和性能数据
- [DeepSeek V4 Tech Report](https://huggingface.co/deepseek-ai/DeepSeek-V4-Pro/blob/main/DeepSeek_V4.pdf) — DeepSeek V4技术报告
- [21经济网 — DeepSeek V4深度报道](https://www.21jingji.com/article/20260425/herald/38a014751923bdfd9a0c000b1948254c.html) — DeepSeek V4发布及估值报道
- [ABHS — Alibaba Ships 560,000 Zhenwu AI Chips](https://www.abhs.in/blog/alibaba-zhenwu-m890-560000-chips-china-nvidia-alternative-2026) — 镇武芯片综合分析
- [Hudson Institute — AI American Dream](https://www.hudson.org/technology/ai-american-dream-promoting-innovation-affordability-american-dominance-david-feith) — 美国对华芯片出口管制政策分析
- [Nvidia Q1 FY2027 Earnings Analysis](https://www.currentaffair.today/blog/finance-9/nvidia-q1-fy2027-earnings-816b-revenue-752b-data-center-80b-buyback-and-why-the-stock-fell-on-a-beat-743) — Nvidia中国H20/H200出货状态
- [格隆汇 — 东数西算与AI算力分析](https://m.gelonghui.com/p/613832) — 东数西算电力成本对比
- [智谱AI官网](https://www.zhipuai.cn/en) — 智谱AI产品矩阵和港股上市信息
- [DeepSeek官网](https://www.deepseek.com/en/) — DeepSeek V4产品信息
- [Build Fast with AI — Best AI Models April 2026](https://www.buildfastwithai.com/blogs/best-ai-models-april-2026) — GLM-5模型信息
- [Editorialge — DeepSeek allegedly used smuggled Nvidia chips](https://editorialge.com/deepseek-allegedly-used-smuggled-nvidia-chips/) — 美国芯片管制历史
- [Network Switch — AI Hardware Outlook April 2026](https://network-switch.com/blogs/news/what-comes-next-ai-hardware-outlook-april-2026) — H200中国出货状态