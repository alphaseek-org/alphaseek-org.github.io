---
layout: page
title: "AI产业趋势：证据台账（2026-11-03）"
permalink: /data/reports/2026-11-03/industry-trend-evidence/
---
[← A股AI产业分析：综合评分排名](/2026/11/03/a-share-ai-pick)

**声明：** AI生成内容，仅供参考，不构成投资建议。市场有风险，入市需谨慎。

<div style="overflow-x:auto" markdown="1">

# AI产业趋势证据账本

**report_date:** 2026-11-03  
**timezone:** UTC  
**报告截止时点:** 2026-11-03T09:07:16Z  
**window:** 2025-11-03 至 2026-11-03，按四个季度近似：Q1=2025-12~2026-02，Q2=2026-03~05，Q3=2026-06~08，Q4=2026-09~11*（11月仅1-3日）  
**regions:** 美国、中国，政策项加入欧盟  
**layers:** 能源和电力、硬件、软件/平台、模型、应用  
**retrieved_at:** 2026-11-03 UTC

> 说明：每行给出URL、日期、摘录和“Says”。HF月度API在网页抓取仍失败，但同一脚本可读取HF daily papers月度端点，已补足3个月top papers；OpenAI官网仍403，OpenAI行保留为搜索/替代来源候选。

## 研究论文：arXiv月度计数与HF daily papers

数据来源：论文计数来自arXiv API，热门论文来自Hugging Face每日论文接口。

| ID | 类型 | URL | 日期 | 层 | 类别/事项 | 值 | Tier | 验证 | 摘录 | Says |
|---|---|---|---|---|---|---:|---|---|---|---|
| P01 | fact | <https://export.arxiv.org/api/query> | 2025-12~2026-11 | 模型 | cs.AI quarterly submissions | Q1 12041; Q2 17130; Q3 15302; Q4* 12851 | P1 | verified | cs.AI 2026-05 7055; cs.AI 2026-10 6506 | cs.AI论文量在Q2高点后仍维持高位。 |
| P02 | fact | <https://export.arxiv.org/api/query> | 2025-12~2026-11 | 模型 | cs.CL quarterly submissions | Q1 5565; Q2 7691; Q3 6966; Q4* 6354 | P1 | verified | cs.CL 2026-05 3066; cs.CL 2026-10 3306 | NLP/LLM相关投稿Q2后维持高位。 |
| P03 | fact | <https://export.arxiv.org/api/query> | 2025-12~2026-11 | 模型 | cs.LG quarterly submissions | Q1 11704; Q2 15192; Q3 13326; Q4* 12905 | P1 | verified | cs.LG 2026-05 6879; cs.LG 2026-10 6813 | 机器学习投稿Q2和Q4高，说明模型方法关注仍强。 |
| P04 | fact | <https://export.arxiv.org/api/query> | 2025-12~2026-11 | 模型/应用 | cs.CV quarterly submissions | Q1 8030; Q2 11328; Q3 9656; Q4* 7871 | P1 | verified | cs.CV 2026-03 4063; cs.CV 2026-10 3990 | 视觉与多模态相关投稿Q2冲高。 |
| P05 | fact | <https://export.arxiv.org/api/query> | 2025-12~2026-11 | 应用 | cs.RO quarterly submissions | Q1 2581; Q2 3718; Q3 3878; Q4* 4529 | P1 | verified | cs.RO 2026-09 2191; cs.RO 2026-10 2240 | 机器人投稿逐季上升，Q4*已超过前三季。 |
| P06 | fact | <https://huggingface.co/api/daily_papers?month=2026-01&limit=10> | 2026-01 | 模型/软件 | HF top papers | top: Agentic Reasoning for LLMs; GDPO; LTX-2 | P1 | verified | “Agentic Reasoning for Large Language Models”; “GDPO”; “LTX-2” | 1月top papers集中在agentic reasoning、RL优化和音视频生成。 |
| P07 | fact | <https://huggingface.co/api/daily_papers?month=2026-05&limit=10> | 2026-05 | 应用/软件 | HF top papers | top: MolmoAct2; SkillOpt; Code as Agent Harness; Qwen-VLA | P1 | verified | “Code as Agent Harness”; “Qwen-VLA”; “Action Reasoning Models for Real-world Deployment” | 5月top papers显示智能体工具执行、机器人VLA和agent技能优化升温。 |
| P08 | fact | <https://huggingface.co/api/daily_papers?month=2026-10&limit=10> | 2026-10 | 软件/应用 | HF top papers | top: BizAgentBench; Trajectory2Gym; Self-Retrospection Distillation | P1 | verified | “BizAgentBench”; “Trajectory2Gym”; “Self-Retrospection Distillation” | 10月top papers转向长程业务agent、工具轨迹合成和RL/蒸馏效率。 |
| P09 | fact | <https://export.arxiv.org/api/query?id_list=2601.12538,2605.18747,2605.30280,2610.20424,2610.33568,2610.05608> | 2026-01~10 | 软件/应用 | arXiv abstracts for selected HF papers | 6 abstracts read | P1 | verified | “LLMs as autonomous agents that plan, act”; “code… operational substrate”; “single vision-language-action” | 被抽查论文摘要支持“agent、VLA、长程执行、多模态生成”主题归类。 |

## 公司发布与产品/平台动态

| ID | 类型 | URL | 日期 | 公司 | 层 | 事项 | Tier | 验证 | 摘录 | Says |
|---|---|---|---|---|---|---|---|---|---|---|
| C01 | fact | <https://www.anthropic.com/claude-haiku-5-5> | 2026-10-07 | Anthropic | 模型/应用 | Claude Haiku 5.5小模型、降本 | P1 | verified | “Haiku 5.5 is available at a much lower price… around 75% less to run.” | Anthropic把小模型定位为高频、低成本、子智能体工作负载。 |
| C02 | fact | <https://www.anthropic.com/news/series-h> | 2026-05-28 | Anthropic | 硬件/模型 | Series H扩算力 | P1 | verified | “raised $65 billion in Series H… valuing the company at $965 billion post-money” | Anthropic融资主要用于安全研究、扩算力和产品伙伴关系。 |
| C03 | fact | <https://qwenlm.github.io/blog/qwen3> | 2026-04-29 | Alibaba/Qwen | 模型 | Qwen3开源MoE和dense模型 | P1 | verified | “two MoE models… Qwen3-235B-A22B… six dense models… Apache 2.0” | Qwen继续以开权模型扩大模型层供给。 |
| C04 | fact | <https://qwenlm.github.io/blog/qwen3-coder> | 2026-07-22 | Alibaba/Qwen | 模型/应用 | Qwen3-Coder与Qwen Code | P1 | verified | “480B-parameter Mixture-of-Experts… 256K tokens natively and 1M tokens… Qwen Code” | Qwen把模型发布接到智能体编码工具链。 |
| C05 | fact | <https://api-docs.deepseek.com/news/news260424> | 2026-04-24 | DeepSeek | 模型 | DeepSeek V4开源预览、1M上下文 | P1 | verified | “DeepSeek-V4 Preview is officially live & open-sourced… cost-effective 1M context length.” | DeepSeek把长上下文和低成本作为模型差异化。 |
| C06 | fact | <https://api-docs.deepseek.com/news/news260910> | 2026-09-10 | DeepSeek | 模型/软件平台 | V4.1-Flash更低KV缓存与价格 | P1 | verified | “KV cache needs just: 1/4 the HBM; 1/8 the SSD storage… Off-peak rates are 50%” | DeepSeek将架构优化转化为推理成本下降。 |
| C07 | fact | <https://blogs.nvidia.com/blog/dgx-superpod-rubin/> | 2026-01-05 | NVIDIA | 硬件/能源 | Rubin/DGX SuperPOD | P1 | verified | “Vera CPU, Rubin GPU, NVLink 6 Switch… reduce the cost of inference token generation.” | NVIDIA硬件叙事从单GPU转向AI工厂全栈和token成本。 |
| C08 | fact | <https://blogs.microsoft.com/blog/2026/03/09/introducing-the-first-frontier-suite-built-on-intelligence-trust> | 2026-03-09 | Microsoft | 软件/平台/应用 | M365 Copilot Wave 3、Agent 365 | P1 | candidate | “General availability of Agent 365 on May 1… Copilot is model diverse by design.” | Microsoft把企业智能体治理、Copilot和多模型选择合为套件。 |
| C09 | fact | <https://blogs.microsoft.com/blog/2026/10/28/introducing-the-microsoft-copilot-harness> | 2026-10-28 | Microsoft/GitHub | 软件/平台 | Copilot harness through Foundry | P1 | candidate | “harness available through Microsoft Foundry… build agents that reason, use tools” | Microsoft把多模型agent harness产品化。 |
| C10 | fact | <https://ai.meta.com/blog/llama-4-multimodal-intelligence/> | 2026 | Meta | 模型 | Llama 4多模态 | P1 | candidate | “The Llama 4 herd: The beginning of a new era of natively multimodal AI innovation” | Meta继续把开源模型方向推向原生多模态。 |
| C11 | fact | <https://aws.amazon.com/blogs/aws/get-started-with-openai-gpt-5-5-gpt-5-4-models-and-codex-on-amazon-bedrock/> | 2026-06-01 | AWS/OpenAI | 软件/平台/模型 | OpenAI模型与Codex上Bedrock | P1 | candidate | “availability of OpenAI GPT-5.5, GPT-5.4 models, and Codex on Amazon Bedrock” | AWS Bedrock强化多模型平台与编码agent分发。 |
| C12 | fact | <https://aws.amazon.com/blogs/aws/anthropic-claude-fable-5-on-aws-mythos-class-capabilities-with-built-in-safeguards-now-available/> | 2026-06-09 | AWS/Anthropic | 模型/平台 | Claude Fable 5 on AWS | P1 | candidate | “Claude Fable 5 makes Mythos-level capabilities available… with strong safeguards” | 前沿模型通过云平台分级分发，并绑定安全机制。 |
| C13 | fact | <https://openai.com/index/gpt-5-6> | 2026-07-09 | OpenAI | 模型 | GPT-5.6发布 | P2 | candidate | “More intelligence from every token, stronger performance per dollar” | OpenAI官网403；搜索索引显示其叙事也是每token智能和性价比。 |
| C14 | fact | <https://seed.bytedance.com/en/blog/seed-2-0-official-launch> | 2026-02-14 | ByteDance/Seed | 模型/应用 | Seed 2.0 | P1 | verified | “Seed2.0 series… optimized… to help tackle complex real-world tasks” | 字节Seed强化复杂任务、长内容、多模态与生产部署。 |
| C15 | fact | <https://ernie.baidu.com/blog/posts/ernie-5.1-0508-release> | 2026-05-09 | Baidu/ERNIE | 模型 | ERNIE 5.1 | P1 | verified | “compresses total parameters… achieving… performance… only about 6% of the pre-training cost” | 百度强调参数效率、训练成本和agent后训练。 |
| C16 | fact | <https://tencentcloud.com/techpedia/144773?lang=en> | 2026-07-06 | Tencent/Hunyuan | 模型/软件 | Hy3 | P1 | verified | “295B total params · 21B active · 256K context · MoE fast/slow thinking · Apache 2.0” | 腾讯Hunyuan以MoE、开权、agentic coding和成本效率竞争。 |
| C17 | fact | <https://www.minimax.io/blog/minimax-m31f> | 2026-10-19 | MiniMax | 模型/应用 | M3.1 Flash | P1 | verified | “nearly three times faster and reducing usage costs by 70%” | MiniMax把agent、computer use、coding与低成本推理结合。 |
| C18 | fact | <https://platform.moonshot.cn/docs/models> | 2026-10-31 | Moonshot/Kimi | 模型/平台 | Kimi K3.1 Pro迁移 | P1 | verified | “K2系列模型将于2026年10月31日起停止向新注册用户开放… 使用最新模型 kimi-k3.1-pro” | Moonshot平台向K3.1 Pro迁移，长上下文/编程模型继续迭代。 |
| C19 | fact | <https://z.ai/blog/glm-5.2> | 2026-06-16 | Zhipu/Z.ai | 模型/软件 | GLM-5.2 | P2 | candidate | “solid 1M-token context… reducing per-token FLOPs by 2.9×” | Z.ai页面网页抓取空白，搜索索引用作候选：长程任务和1M上下文是主线。 |

## 并购、投资、上市与算力/能源承诺

| ID | 类型 | URL | 日期 | 交易方 | 层 | 金额 | 阶段 | Tier | 验证 | 摘录 | Says |
|---|---|---|---|---|---|---:|---|---|---|---|---|
| D01 | fact | <https://openai.com/index/accelerating-the-next-phase-ai> | 2026-03-31 | OpenAI; SoftBank/a16z等 | 模型/硬件 | US$122B | closed | P2 | candidate | “closed our latest funding round with $122 billion… post money valuation of $852 billion” | OpenAI官网网页抓取 403；搜索索引用作候选。 |
| D02 | fact | <https://www.anthropic.com/news/series-h> | 2026-05-28 | Anthropic; Altimeter/Dragoneer等 | 模型/硬件 | US$65B | closed | P1 | verified | “raised $65 billion in Series H… valuing the company at $965 billion post-money” | Anthropic融资集中在扩算力和Claude商业化。 |
| D03 | fact | <https://siliconangle.com/2026/09/08/open-source-ai-developer-mistral-closes-e3b-funding-round/> | 2026-09-08 | Mistral; Samsung等 | 模型/平台 | €3B (~US$3.49B) | announced | P2 | verified | “raised €3 billion, or about $3.49 billion… Samsung Electronics… led” | 欧洲模型公司继续获得战略资本。 |
| D04 | fact | <https://www.anthropic.com/news/series-h> | 2026-05-28 | Amazon→Anthropic | 硬件/模型 | US$5B (included) | committed | P1 | verified | “includes $15 billion… from hyperscalers, including $5 billion from Amazon.” | 云厂商资本与模型公司绑定。 |
| D05 | fact | <https://imerit.ai/press/exl-to-acquire-imerit/> | 2026-06-24 | EXL→iMerit | 软件/平台 | up to US$310M | definitive agreement | P1 | verified | “$310 million acquisition… upfront consideration of $170 million” | 数据标注/评测/RLHF能力被企业AI服务商收购。 |
| D06 | fact | <https://ir.amd.com/news-events/press-releases/detail/1299/amd-to-acquire-world-labs-to-advance-the-future-of-ai-compute> | 2026-09-28 | AMD→World Labs | 硬件/模型 | US$8.2B stock | definitive agreement | P1 | verified | “all-stock transaction is valued at approximately $8.2 billion” | 芯片厂商收购空间智能模型团队。 |
| D07 | fact | <https://www.biocatch.com/press-release/biocatch-to-join-visa> | 2026-08-03 | Visa→BioCatch | 应用 | US$2.4B cash | definitive agreement | P1 | verified | “acquire BioCatch… for $2.4 billion in cash” | 支付/风控应用层AI资产出现大额并购。 |
| D08 | fact | <https://proscia.com/press-release/agilent-to-acquire-proscia-advancing-ai-enabled-digital-pathology-and-scientific-intelligence> | 2026-10-13 | Agilent→Proscia | 应用 | US$240M + up to US$30M | definitive agreement | P1 | verified | “all-cash transaction valued at $240 million… up to an additional $30 million” | 医疗病理AI软件并入仪器公司。 |
| D09 | fact | <https://www.prnewswire.com/news-releases/rezolve-ai-acquires-reward-for-230m-to-accelerate-innovation-in-ai-powered-banking-and-commerce-302684199.html> | 2026-02-11 | Rezolve AI→Reward | 应用 | US$230M cash | acquired | P2 | verified | “acquires Reward for $230 million all-cash” | 商业/银行会话式AI应用层整合。 |
| D10 | fact | <https://www.crowdstrike.com/en-us/press-releases/crowdstrike-to-acquire-fiddler-to-deliver-agent-observability/> | 2026-11-03 | CrowdStrike→Fiddler AI | 软件/平台 | undisclosed | signed | P1 | verified | “signed a definitive agreement to acquire Fiddler AI… AI agent observability” | Agent可观测性成为安全平台收购方向；不计入金额最低数。 |
| D11 | fact | <https://capitaltimes.asia/tech/startups/asia-startup-funding-third-quarter-ai-china> | 2026-07 | Moonshot AI | 模型 | US$3.5B | reported | P2 | candidate | “Moonshot AI… raised a $3.5 billion Series F in July” | 中国模型公司大额融资仅取得新闻源。 |
| D12 | fact | <https://capitaltimes.asia/tech/startups/asia-startup-funding-third-quarter-ai-china> | 2026-Q2 | DeepSeek | 模型 | US$7.4B | reported | P2 | candidate | “lifted by a $7.4 billion financing for DeepSeek” | DeepSeek融资金额未官方确认。 |
| D13 | fact | <https://aechelon.com/press-releases/shield-ai-to-acquire-software-simulation-company-aechelon-and-raise-2b-at-12-7b-valuation/> | 2026-03-26 | Shield AI→Aechelon | 应用/软件 | US$2B raise incl. US$1.5B Series G + US$500M preferred | announced | P1 | verified | “raising $1.5 billion in Series G… and $500 million in fixed-return preferred equity financing” | 防务自治/仿真AI获得大额资本并并购仿真软件。 |
| D14 | fact | <https://www.pathos.com/pathos-ai-secures-237-million-in-series-e-financing-to-scale-agentic-ai-drug-development-platform-and-advance-oncology-pipeline> | 2026-10-23 | Pathos AI | 应用 | US$237M | closed | P1 | verified | “closing of a $237 million Series E financing round” | AI药物研发平台融资，应用层继续吸金。 |
| D15 | fact | <https://deepgram.com/learn/press-release-deepgram-raises-series-c> | 2026-01-13 | Deepgram | 软件/应用 | US$130M | closed | P1 | verified | “raised $130 million in Series C funding at a $1.3 billion valuation” | 语音AI API平台融资并收购OfOne。 |
| D16 | fact | <https://sima.ai/press-release/sima-ai-reaches-1-45b-valuation-with-500-million-in-total-funding-to-scale-physical-ai-in-humanoids-automotive-and-drones/> | 2026-09-28 | SiMa.ai | 硬件/应用 | US$150M | closed | P1 | verified | “announced $150 million in Series C financing… valuing the company at $1.45 billion” | 物理AI芯片/软件栈融资服务机器人、汽车和无人机。 |
| D17 | fact | <https://www.fonoa.com/company/news/fonoa-raises-110m-funding-and-acquires-edge> | 2026-05-28 | Fonoa→PwC Edge | 软件/应用 | US$110M | closed/acquired | P1 | verified | “acquisition of Indirect Tax Edge… and a $110 million Series C” | 企业税务AI平台融资并整合合规工作流。 |
| D18 | fact | <https://blogs.microsoft.com/blog/2026/06/22/powering-the-next-wave-of-ai-expanding-capacity-with-our-new-datacenter-in-pecos/> | 2026-06-22 | Microsoft | 能源/硬件 | ~2GW capacity; multibillion-dollar | announced | P1 | verified | “new datacenter campus… expanding… capacity by approximately 2 gigawatts (GW)” | 直接证据显示AI/云需求推动电力和数据中心容量扩张。 |
| D19 | fact | <https://www.constellationenergy.com/news/2026/10/google-and-constellation-announce-landmark-agreement-to-bring-890-mw-of-new-nuclear-capacity-to-pjm-grid.html> | 2026-10-06 | Google; Constellation | 能源/硬件 | 890MW new nuclear + 2700MW supply; >US$4.3B investment | PPA | P1 | verified | “bring 890 megawatts… 20-year power purchase agreement… more than $4.3 billion” | hyperscaler AI需求转化为长期电力和核电增容协议。 |

## 政策与监管

| ID | 类型 | URL | 日期 | 地区/机构 | 层 | 工具/状态 | 方向 | Tier | 验证 | 摘录 | Says |
|---|---|---|---|---|---|---|---|---|---|---|---|
| G01 | fact | <https://whitehouse.gov/presidential-actions/2026/06/promoting-advanced-artificial-intelligence-innovation-and-security> | 2026-06-02 | 美国白宫 | 模型/应用/安全 | Executive Order 14409, in force | mixed/support | P1 | verified | “voluntary framework with AI developers… access to covered frontier models… up to 30 days before” | 美国以自愿框架和网络安全为主，而非强制模型许可。 |
| G02 | fact | <https://whitehouse.gov/presidential-actions/2026/06/national-security-presidential-memorandum-nspm-11?cst=&query-11-page=101> | 2026-06 | 美国白宫 | 应用/模型 | NSPM-11, in force | support/restrict | P1 | verified | “accelerate the use of AI across intelligence and warfighting domains” | 美国推动国安领域AI采用，同时要求责任链。 |
| G03 | fact | <https://whitehouse.gov/releases/2026/03/president-donald-j-trump-unveils-national-ai-legislative-framework> | 2026-03 | 美国白宫 | 应用/模型 | legislative framework | support/mixed | P1 | verified | “national policy framework… enables American industry to innovate and thrive” | 美国提出全国AI立法框架以避免碎片化监管。 |
| G04 | fact | <https://media.bis.gov/sites/default/files/documents/05.07%20Recission%20of%20AI%20Diffusion%20Press%20Release.pdf> | 2026-05-12 | 美国商务部/BIS | 硬件/模型 | export-control guidance | restrict | P1 | verified | “rescission… AI Diffusion Rule… strengthen export controls on semiconductors worldwide” | 美国撤销AI Diffusion规则但强化芯片与Huawei Ascend相关限制。 |
| G05 | fact | <https://www.federalregister.gov/api/v1/documents/2026-21447.json> | 2026-10-20 | 美国DHS | 应用/模型 | procurement exclusion, adopted | restrict | P1 | verified | “excluding… DeepSeek… from federal civilian agency procurements; … removing all DeepSeek” | Federal Register API确认DHS排除DeepSeek产品的通知。 |
| G06 | fact | <https://www.cac.gov.cn/2026-04/10/c_1777558395078289.htm> | 2026-04-10 / 2026-07-15生效 | 中国网信办等 | 应用 | 暂行办法，in force | mixed/restrict | P1 | verified | “自2026年7月15日起施行… 拟人化互动服务… 适用本办法” | 中国对拟人化情感互动AI设定边界、提醒和安全责任。 |
| G07 | fact | <https://www.cac.gov.cn/2026-09/14/c_1791136833136332.htm> | 2026-09-14 | 中国网信办 | 应用/模型 | 备案公告 | mixed | P1 | verified | “新增124款… 截至8月31日，累计有1112款…完成备案” | 中国生成式AI备案常态化，备案数继续上升。 |
| G08 | fact | <https://www.miit.gov.cn/zwgk/zcwj/wjfb/tz/art/2026/art_ba07e09d40834ec992615490fd2ccd18.html> | 2026-04-28 | 中国工信部/国家数据局 | 软件/平台/应用 | “模数共振”行动 | support | P1 | verified | “推动人工智能模型与数据资源协同互促… 赋能新型工业化” | 中国以行业数据集、行业模型和智能体推动工业应用。 |
| G09 | fact | <https://www.miit.gov.cn/zwgk/zcwj/wjfb/tz/art/2026/art_49783ce685f042029111c8b6e94f0f30.html> | 2026-09-11 | 中国工信部 | 软件/平台 | “人工智能+软件”专项行动 | support | P1 | verified | “《‘人工智能+软件’专项行动实施方案》印发给你们” | 中国政策继续推动软件行业AI化。 |
| G10 | fact | <https://digital-strategy.ec.europa.eu/en/policies/european-approach-artificial-intelligence> | 2026-08-02起 | 欧盟 | 模型/应用 | AI Act enforcement | restrict/support | P1 | verified | “From 2 August 2026, the AI Office and national authorities started to enforce the AI Act.” | 欧盟AI法进入执行阶段，同时推进AI工厂和投资设施。 |
| G11 | fact | <https://www.federalregister.gov/api/v1/documents.json?conditions%5Bterm%5D=artificial%20intelligence&conditions%5Bpublication_date%5D%5Bgte%5D=2025-11-03&conditions%5Bpublication_date%5D%5Blte%5D=2026-11-03&per_page=20&order=newest> | 2025-11-03~2026-11-03 | 美国Federal Register | 多层 | AI documents search | mixed | P1 | verified | “Documents matching 'artificial intelligence'… count 322” | API可用，窗口内AI相关联邦文件共322条；用于替代网页CAPTCHA。 |

## 计算派生表

### arXiv季度合计

| 类别 | Q1 2025-12~2026-02 | Q2 2026-03~05 | Q3 2026-06~08 | Q4 2026-09~11* |
|---|---:|---:|---:|---:|
| cs.AI | 12041 | 17130 | 15302 | 12851 |
| cs.CL | 5565 | 7691 | 6966 | 6354 |
| cs.LG | 11704 | 15192 | 13326 | 12905 |
| cs.CV | 8030 | 11328 | 9656 | 7871 |
| cs.RO | 2581 | 3718 | 3878 | 4529 |

### HF top-paper主题样本（每月top 10，按标题/摘要人工归类）

| 主题 | 2026-01 | 2026-05 | 2026-10 | 支撑证据 |
|---|---:|---:|---:|---|
| 智能体/工具使用/编码 | 4 | 4 | 5 | P06-P09 |
| 高效推理/RL/蒸馏 | 2 | 1 | 2 | P06-P09 |
| 多模态/音视频 | 3 | 3 | 1 | P06-P09 |
| 机器人/VLA/具身 | 0 | 2 | 2 | P07-P09 |
| 安全/评测/基准 | 1 | 2 | 3 | P07-P09 |

### 资金按季度（披露/报道金额，粗略，不做投资建议）

| 季度 | 金额交易数 | 披露金额合计（约，美元） | 主要层 |
|---|---:|---:|---|
| Q1 | 4 | 124.36B | 模型、应用、软件 |
| Q2 | 6 | 137.92B | 模型、硬件、平台、能源 |
| Q3 | 5 | 17.74B | 模型、应用、硬件 |
| Q4* | 4 | 4.81B+未披露 | 能源、应用、平台 |

## 缺口

- Hugging Face daily papers API 对网页抓取仍为network unreachable；脚本成功取得2026-01、2026-05、2026-10三个月top papers，因此最低项已满足但留有可复现环境差异。
- OpenAI官网仍对网页抓取返回403；OpenAI发布和融资行仍为candidate，未作为唯一关键证据。
- Z.ai GLM页面网页抓取返回空内容，仅搜索索引候选；不计入强验证发布数。
- 中国DeepSeek、Moonshot私募融资缺少公司公告或监管文件；保留candidate。
- 能源/电力已补Microsoft和Google/Constellation直接证据，但中国AI算力电力合同仍缺可验证来源。

</div>
