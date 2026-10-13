# Awesome Economics of AI

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg)](CONTRIBUTING.md)

A curated guide to the costs, markets, adoption, and economic effects of AI.

Explore how AI is produced, how businesses earn money from it, how organizations use it, and how it changes work and growth. For researchers, builders, investors, and policy readers.

This list brings together research, datasets, and analysis scattered across academic, policy, and industry sources.

Resources are grouped by the economic question they help answer. Each entry includes a short description and a source label. Contributions are welcome through the [contribution guide](CONTRIBUTING.md).

## Contents

- [Compute and infrastructure](#compute-and-infrastructure)
  - [Chips and hardware economics](#chips-and-hardware-economics)
  - [Cloud markets and capacity pricing](#cloud-markets-and-capacity-pricing)
  - [Data centers and capital investment](#data-centers-and-capital-investment)
  - [Financing and investment risk](#financing-and-investment-risk)
  - [Energy and grid constraints](#energy-and-grid-constraints)
  - [Cooling, water, and environmental costs](#cooling-water-and-environmental-costs)
  - [Training costs and scaling](#training-costs-and-scaling)
  - [Inference costs and serving efficiency](#inference-costs-and-serving-efficiency)
- [Models and applications](#models-and-applications)
  - [Model pricing and price-performance](#model-pricing-and-price-performance)
  - [Margins and business models](#margins-and-business-models)
  - [Competition and market power](#competition-and-market-power)
  - [Open models and barriers to entry](#open-models-and-barriers-to-entry)
  - [Data markets and intellectual property](#data-markets-and-intellectual-property)
  - [AI agents and transaction costs](#ai-agents-and-transaction-costs)
- [Adoption and productivity](#adoption-and-productivity)
  - [Adoption rates and diffusion](#adoption-rates-and-diffusion)
  - [Enterprise returns and measurement](#enterprise-returns-and-measurement)
  - [Deployment costs and reliability](#deployment-costs-and-reliability)
  - [Organizational change and teamwork](#organizational-change-and-teamwork)
  - [Customer service and knowledge work](#customer-service-and-knowledge-work)
  - [Software development](#software-development)
- [Labor, growth, and policy](#labor-growth-and-policy)
  - [Task exposure and automation](#task-exposure-and-automation)
  - [Employment and wages](#employment-and-wages)
  - [Skills and new tasks](#skills-and-new-tasks)
  - [Inequality and distribution](#inequality-and-distribution)
  - [Economic growth and transformative AI](#economic-growth-and-transformative-ai)
  - [Innovation and research productivity](#innovation-and-research-productivity)
  - [Trade and economic development](#trade-and-economic-development)
  - [Taxation and social protection](#taxation-and-social-protection)
  - [Sovereign AI and industrial policy](#sovereign-ai-and-industrial-policy)
  - [Regulation and competition policy](#regulation-and-competition-policy)
- [Courses and learning materials](#courses-and-learning-materials)
- [Related collections](#related-collections)
- [Contributing](#contributing)

## Reading the labels

[![Study][study-badge]](#reading-the-labels) means empirical research. [![Theory][theory-badge]](#reading-the-labels) means a model or conceptual framework. [![Survey][survey-badge]](#reading-the-labels) means a review of research. [![Data][data-badge]](#reading-the-labels) means a dataset or benchmark. [![Report][report-badge]](#reading-the-labels) means institutional analysis. [![Industry][industry-badge]](#reading-the-labels) means practitioner or investor analysis. [![Course][course-badge]](#reading-the-labels), [![Book][book-badge]](#reading-the-labels), [![Overview][overview-badge]](#reading-the-labels), and [![Collection][collection-badge]](#reading-the-labels) describe the format.

Labels describe the source, not a quality ranking or publication status. Dates identify the linked edition or initial working paper; later publication is noted when useful. [![Living][living-badge]](#reading-the-labels) resources change over time. Some publisher versions require payment, even when an abstract or working version is public.

[study-badge]: https://img.shields.io/badge/Study-2563eb?style=flat
[theory-badge]: https://img.shields.io/badge/Theory-7c3aed?style=flat
[survey-badge]: https://img.shields.io/badge/Survey-0891b2?style=flat
[data-badge]: https://img.shields.io/badge/Data-087f5b?style=flat
[report-badge]: https://img.shields.io/badge/Report-475569?style=flat
[industry-badge]: https://img.shields.io/badge/Industry-a15c00?style=flat
[course-badge]: https://img.shields.io/badge/Course-4f46e5?style=flat
[book-badge]: https://img.shields.io/badge/Book-9333ea?style=flat
[overview-badge]: https://img.shields.io/badge/Overview-0369a1?style=flat
[collection-badge]: https://img.shields.io/badge/Collection-6d28d9?style=flat
[living-badge]: https://img.shields.io/badge/Living-238636?style=flat
[videos-badge]: https://img.shields.io/badge/Videos-64748b?style=flat
[slides-badge]: https://img.shields.io/badge/Slides-64748b?style=flat
[exercises-badge]: https://img.shields.io/badge/Exercises-64748b?style=flat

## Start here

- [Economics of the AI Supercycle](https://mse435.stanford.edu/) - Stanford MS&E 435. A practitioner seminar on the economics of the AI stack. Start here for the industry perspective. [![Course][course-badge]](#reading-the-labels)
- [The Economics of Generative AI](https://www.nber.org/reporter/2024number1/economics-generative-ai) - NBER Reporter (2024). An accessible introduction to workplace evidence and the delay between adoption and measured productivity. [![Overview][overview-badge]](#reading-the-labels)
- [AI Index: Economy](https://hai.stanford.edu/ai-index/2026-ai-index-report/economy) - Stanford HAI (2026). Charts and source references on investment, adoption, productivity, and labor markets. [![Report][report-badge]](#reading-the-labels)

**Choose a path:** For business economics, start with compute and models. For deployment decisions, start with adoption and productivity. For research and policy, start with labor and growth, then use the courses below.

## Compute and infrastructure

### Chips and hardware economics

*What determines the amount of useful computation a dollar can buy?*

- [Trends in GPU Price-Performance](https://epoch.ai/publications/trends-in-gpu-price-performance) - Epoch AI (2022). Historical estimates of hardware performance per dollar. Useful for separating chip improvements from changes in model design. [![Data][data-badge]](#reading-the-labels)
- [AI Chip Component Cost Shares](https://epoch.ai/data-insights/ai-chip-component-cost-shares) - Epoch AI (2026). Estimates the costs of memory, logic, packaging, and other chip components, with downloadable data. Component cost estimates differ from accelerator sale prices. [![Data][data-badge]](#reading-the-labels)

### Cloud markets and capacity pricing

*How do access, commitments, and switching costs affect compute buyers?*
- [Cloud Services Market Investigation](https://www.gov.uk/cma-cases/cloud-services-market-investigation) - UK Competition and Markets Authority (final decision, 2025). Evidence on cloud pricing, profitability, switching barriers, and licensing. Covers cloud infrastructure broadly. [![Report][report-badge]](#reading-the-labels)
- [State of Cloud Costs](https://www.datadoghq.com/state-of-cloud-costs/) - Datadog (May 2023 to April 2024 data). Customer billing evidence on GPU spending, idle capacity, data transfer, and commitment discounts. Covers a sample of AWS customers using Datadog, not the whole cloud market. [![Report][report-badge]](#reading-the-labels)
- [Who Is Buying & Selling AI Compute?](https://ramp.com/data/who-is-buying-and-selling-gpu-compute) - Cara Santone, Ramp (September 2026). Maps compute buyers, provider types, and purchasing terms using customer transactions. Covers Ramp customers that buy SaaS; the provider adoption breakdown excludes hyperscalers because bundled GPU spending is hard to isolate. [![Industry][industry-badge]](#reading-the-labels)
- [GPU Cloud Economics Explained: The Hidden Truth](https://newsletter.semianalysis.com/p/gpu-cloud-economics-explained-the) - Dylan Patel and Daniel Nishball, SemiAnalysis (December 2023). Explains how hardware purchase costs, financing, and hosting costs shape GPU rental economics. A historical framework whose hardware and pricing assumptions need updating. Free preview; full article requires a subscription. [![Industry][industry-badge]](#reading-the-labels)

### Data centers and capital investment

*Where is capacity built, who owns it, and what revenue could support the investment?*

- [GPU Clusters](https://epoch.ai/data/gpu-clusters) - Epoch AI. Downloadable records of cluster ownership, hardware, estimated cost, and power. Coverage is incomplete, and planned systems have greater uncertainty. [![Data][data-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)
- [AI’s $600B Question](https://sequoiacap.com/article/ais-600b-question) - David Cahn, Sequoia Capital (2024). An investor framework connecting infrastructure spending to required downstream revenue. Read its assumptions as a historical scenario, not a current industry balance sheet. [![Industry][industry-badge]](#reading-the-labels)
- [The Macro Implications of the AI Capex Boom](https://www.bridgewater.com/_document/the-macro-implications-of-the-ai-capex-boom?id=0000019b-b947-d0c5-addb-bf4f46590000) - Bridgewater Associates (2026). An investor analysis of capital spending, growth, supply constraints, inflation, and financing. Its projections are scenarios to assess against later evidence. [![Industry][industry-badge]](#reading-the-labels)

### Financing and investment risk

*How are AI investments funded, and who bears the risk if demand falls short?*

- [Hyperscaler Capital Spending versus Operating Cash Flow](https://epoch.ai/data-insights/hyperscaler-capex-vs-cash-flow) - Epoch AI (June 2026). Uses company filings to compare capital spending with operating cash flow. Separates historical data from trend extrapolation; the spending series includes non-AI investment. [![Data][data-badge]](#reading-the-labels)
- [Straight Talk About Circular Deals in AI](https://www.acadian-asset.com/investment-insights/owenomics/straight-talk-about-circular-deals-in-ai) - Owen Lamont, Acadian (2025). A skeptical view of claims that supplier investments and customer agreements alone establish a bubble. Focuses on leverage, equity issuance, and reported fundamentals. [![Industry][industry-badge]](#reading-the-labels)
- [Venture Capital Investments in Artificial Intelligence through 2025](https://www.oecd.org/en/publications/venture-capital-investments-in-artificial-intelligence-through-2025_a13752f5-en.html) - OECD (2026). Tracks AI venture funding using Preqin data, including geographic concentration and large deals. Coverage and missing deal values affect comparisons; venture funding is not total AI capital spending. [![Report][report-badge]](#reading-the-labels)
- [Are We in an AI Bubble?](https://ramp.com/data/are-we-in-ai-bubble) - Ara Kharazian, Ramp (October 2025). Uses paid adoption, customer retention, and contract sizes to assess the durability of AI demand. A dated industry argument with forecasts; spending trends alone do not establish investment returns or rule out a bubble. [![Industry][industry-badge]](#reading-the-labels)

### Energy and grid constraints

*How do electricity supply, location, and emissions affect AI expansion?*

- [Energy and AI](https://www.iea.org/reports/energy-and-ai) - International Energy Agency (2025). A global account of data-center electricity demand, supply options, and wider energy effects. Distinguishes scenarios from observed demand. [![Report][report-badge]](#reading-the-labels)
- [Electricity Rate Designs for Large Loads: Evolving Practices and Opportunities](https://eta-publications.lbl.gov/sites/default/files/2025-01/electricity_rate_designs_for_large_loads_evolving_practices_and_opportunities_final.pdf) - Berkeley Lab, The Brattle Group, and U.S. Department of Energy (January 2025). Explains how electricity contracts allocate infrastructure costs and demand risk between large customers and other ratepayers. Examples reflect their status at publication. [![Report][report-badge]](#reading-the-labels)
- [Key Questions on Energy and AI](https://www.iea.org/reports/key-questions-on-energy-and-ai) - International Energy Agency (2026). Updates the 2025 report with new evidence on data-center demand, electricity supply, grid constraints, and affordability. [![Report][report-badge]](#reading-the-labels)
- [United States Data Center Energy Usage Report: 2025 Update](https://eta-publications.lbl.gov/publications/united-states-data-center-energy-2025) - Smith and coauthors, Berkeley Lab (published June 2026). Builds electricity-demand scenarios from equipment shipments, device energy use, and cooling models. Covers all U.S. data centers; results are model estimates and projections. [![Report][report-badge]](#reading-the-labels)
- [Queued Up: 2025 Edition](https://emp.lbl.gov/publications/queued-2025-edition-characteristics) - Berkeley Lab (2025; data through 2024). Project data and analysis of proposed power plants and storage seeking grid connections. Useful for studying electricity supply delays; these are not data-center connection queues. [![Data][data-badge]](#reading-the-labels)
- [AI Datacenter Energy Dilemma: Race for AI Datacenter Space](https://newsletter.semianalysis.com/p/ai-datacenter-energy-dilemma-race) - Patel, Nishball, and Ontiveros, SemiAnalysis (March 2024). Connects accelerator shipments to power demand, grid limits, location choices, and data-center construction. Includes dated forecasts and cost assumptions. Free first half; full article requires a subscription. [![Industry][industry-badge]](#reading-the-labels)

### Cooling, water, and environmental costs

*How do cooling needs and environmental effects change the costs of AI infrastructure?*

- [AI and Climate Change](https://www.iea.org/reports/energy-and-ai/ai-and-climate-change) - International Energy Agency (2025). Examines emissions from AI infrastructure alongside potential emissions reductions from AI applications. [![Report][report-badge]](#reading-the-labels)

### Training costs and scaling

*How do model size, data, and compute budgets change training economics?*

- [Trends in the Dollar Training Cost of Machine Learning Systems](https://epoch.ai/publications/trends-in-the-dollar-training-cost-of-machine-learning-systems) - Ben Cottier, Epoch AI (2023). Explains how training-cost estimates are constructed and where their uncertainty comes from. Final-run compute cost is not total development cost. [![Study][study-badge]](#reading-the-labels)
- [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556) - Hoffmann and coauthors (2022). The Chinchilla paper studies how to allocate a fixed training budget between model size and training data. Technical background for cost comparisons. [![Study][study-badge]](#reading-the-labels)
- [DeepSeek Debates: Chinese Leadership On Cost, True Training Cost, Closed Model Margin Impacts](https://newsletter.semianalysis.com/p/deepseek-debates) - Dylan Patel and coauthors, SemiAnalysis (January 2025). Distinguishes a final training run from broader research, staffing, and infrastructure spending. Hardware and spending figures are industry estimates. Free preview; full article requires a subscription. [![Industry][industry-badge]](#reading-the-labels)

### Inference costs and serving efficiency

*What changes the cost of producing useful model outputs?*

- [Efficient Memory Management for Large Language Model Serving with PagedAttention](https://arxiv.org/abs/2309.06180) - Kwon and coauthors (2023). Explains the serving design behind vLLM and how memory use affects throughput. Connects systems engineering to delivery cost. [![Study][study-badge]](#reading-the-labels)
- [MLPerf Inference: Datacenter](https://mlcommons.org/benchmarks/inference-datacenter/) - MLCommons. Standardized performance results, with power measurements for participating submissions. Compare matched workloads and quality targets; benchmark speed alone is not a dollar-cost measure. [![Data][data-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)
- [Beyond Per-Token Pricing: A Concurrency-Aware Methodology for LLM Infrastructure Cost Estimation](https://arxiv.org/abs/2606.11690) - Chitral Patil (2026 preprint). Benchmarks how request traffic and hardware utilization change serving cost, with a linked cost-measurement tool. Results depend on the tested models, hardware, and traffic patterns. [![Study][study-badge]](#reading-the-labels)
- [Position: LLM Inference Should Be Evaluated as Energy-to-Token Production](https://arxiv.org/abs/2605.11733) - Liu and coauthors (2026 position paper). A framework connecting useful model output to power, cooling, utilization, and quality constraints. Proposes evaluation measures; listed API prices are not measurements of marginal cost. [![Theory][theory-badge]](#reading-the-labels)
- [AgentX - InferenceXv3: Does the CUDA Moat Hold Up in Agentic Inferencing?](https://inferencex.semianalysis.com/blog/agentx-inferencexv3-does-cuda-moat) - SemiAnalysis (August 2026). Explains how long conversations, cache reuse, and response speed change serving performance and cost per token. Includes open benchmark data; cost comparisons depend on workload and hardware assumptions. Public article excerpt; full article requires a subscription. [![Industry][industry-badge]](#reading-the-labels)

## Models and applications

### Model pricing and price-performance

*How much capability does a buyer obtain for a given price?*

- [Model Comparison](https://artificialanalysis.ai/models/) - Artificial Analysis. Compares model quality, prices, speed, and latency. A useful starting point for evaluating trade-offs, with methodology and task fit still important. [![Data][data-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)

- [Cracks in the AI Thesis Part 2](https://ramp.com/data/ai-index-sept-2026) - Ara Kharazian, Ramp (September 2026). Examines how falling token prices, model choice, and spending per employee affect model-company revenue prospects. A dated analysis of platform data; estimates for the largest spenders are volatile and subject to revision. [![Industry][industry-badge]](#reading-the-labels)

For deployment costs, also see [inference costs and serving efficiency](#inference-costs-and-serving-efficiency). A token price does not capture retries, long outputs, human review, or integration costs.

### Margins and business models

*Which parts of the AI stack can retain revenue after paying their costs?*

- [Who Owns the Generative AI Platform?](https://a16z.com/who-owns-the-generative-ai-platform/) - Bornstein, Appenzeller, and Casado, Andreessen Horowitz (2023). An early investor view of applications, models, infrastructure, and defensible businesses. Useful as a framework rather than a current market map. [![Industry][industry-badge]](#reading-the-labels)
- [The Economics of Generative AI: Two Years Later](https://tailwinds.substack.com/p/the-economics-of-generative-ai-two) - Apoorv Agrawal (2026). Estimates revenue and gross-profit distribution across semiconductors, infrastructure, and applications. An investor model with estimated private-company figures, rather than audited industry accounts. [![Industry][industry-badge]](#reading-the-labels)
- [AI Value Capture - The Shift To Model Labs](https://newsletter.semianalysis.com/p/ai-value-capture-the-shift-to-model) - Daniel Nishball and coauthors, SemiAnalysis (May 2026). Examines how profits are divided among chip suppliers, GPU clouds, inference providers, and model labs. A dated industry argument based on estimated costs and margins. Free preview; full article requires a subscription. [![Industry][industry-badge]](#reading-the-labels)

### Competition and market power

*What allows AI suppliers to set prices above costs?*

- [Market Power in Artificial Intelligence](https://www.nber.org/papers/w32270) - Joshua Gans (2024 working paper; published 2026). Reviews competition in training data, input data, and AI predictions. [![Survey][survey-badge]](#reading-the-labels)
- [Artificial Intelligence, Competition, and Welfare](https://www.nber.org/papers/w34444) - Susan Athey and Fiona Scott Morton (2025 working paper). Models how upstream AI pricing affects downstream adoption, workers, and welfare. [![Theory][theory-badge]](#reading-the-labels)
- [OpenRouter LLM Rankings](https://openrouter.ai/rankings) - OpenRouter. Tracks model usage on its routing platform. Useful for studying demand shifts and model substitution within that platform; token shares are not industry revenue shares. [![Data][data-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)
- [Businesses Are Changing AI Model Providers More Often](https://ramp.com/data/businesses-are-changing-ai-model-providers-more-often) - Ryan Stevens, Ramp (October 2026). Tracks supplier switching around model releases and price cuts. Useful evidence on customer mobility within Ramp data; it does not directly estimate switching costs or prove that models are commodities. [![Industry][industry-badge]](#reading-the-labels)

### Open models and barriers to entry

*When does openness help new firms compete?*

- [Old Moats for New Models](https://www.nber.org/papers/w32474) - Azoulay, Krieger, and Nagaraj (2024 working paper; published 2025). Explains how control over complementary assets, such as infrastructure and distribution, can shape competition even when models are open. [![Theory][theory-badge]](#reading-the-labels)
- [Open Source Technology in the Age of AI](https://www.mckinsey.com/capabilities/quantumblack/our-insights/open-source-technology-in-the-age-of-ai) - McKinsey, Mozilla Foundation, and Patrick J. McGovern Foundation (2025). Surveys technology leaders and developers on model choice, implementation costs, and time to value. Reports respondent perceptions; included models have different license terms. [![Report][report-badge]](#reading-the-labels)

When comparing resources, distinguish open weights from rights to use, modify, and redistribute a model. These are separate economic choices.

### Data markets and intellectual property

*Who supplies training data, who gets paid, and how do rights affect entry?*


### AI agents and transaction costs

*What happens when software searches, negotiates, and buys for people?*

- [The Coasean Singularity? Demand, Supply, and Market Design with AI Agents](https://www.nber.org/papers/w34468) - Shahidi and coauthors (2025 working paper). Examines how agents could reduce search and contracting costs while creating new market frictions. [![Theory][theory-badge]](#reading-the-labels)

## Adoption and productivity

### Adoption rates and diffusion

*Who uses AI, how often, and for which tasks?*

- [The Rapid Adoption of Generative AI](https://www.nber.org/papers/w32966) - Bick, Blandin, and Deming (2024 working paper; revised 2025). Representative U.S. surveys of use at work and at home. Separates having used AI from the intensity of use. [![Study][study-badge]](#reading-the-labels)
- [Business Trends and Outlook Survey: Downloads and Documentation](https://www.census.gov/hfp/btos/data_downloads) - U.S. Census Bureau. Business adoption data and AI supplements by sector, firm size, and location. Check questionnaires before comparing periods because the AI-use wording changed. [![Data][data-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)
- [Use of Artificial Intelligence in Enterprises](https://ec.europa.eu/eurostat/statistics-explained/index.php?title=Use_of_artificial_intelligence_in_enterprises) - Eurostat. Official EU adoption statistics by country, business size, technology, and use case, with links to source tables. Covers selected sectors and enterprises with at least 10 people employed. [![Data][data-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)
- [2025: The State of Generative AI in the Enterprise](https://menlovc.com/perspective/2025-the-state-of-generative-ai-in-the-enterprise/) - Menlo Ventures (2025). Survey and market estimates of enterprise spending, model choices, and applications. Respondents already use AI; spending definitions exclude chips and inference serving. [![Industry][industry-badge]](#reading-the-labels)
- [The Adoption of Artificial Intelligence in Firms: New Evidence for Policymaking](https://www.oecd.org/en/publications/the-adoption-of-artificial-intelligence-in-firms_f9ef33c3-en.html) - OECD, BCG, and INSEAD (2025). Surveys AI-adopting firms in the G7 and Brazil on barriers, skills, and policy support. The core survey predates widespread generative AI use and does not measure population adoption rates. [![Report][report-badge]](#reading-the-labels)
- [Ramp AI Index](https://ramp.com/data/ai-index) - Ramp Economics Lab. Monthly paid AI adoption by business size, sector, and vendor, based on corporate card and bill payments. The sample skews toward growing, technology-oriented firms and misses free or personally funded use. See [How Ramp Data Works](https://ramp.com/data/how-ramp-data-works) for coverage and sample limits. [![Data][data-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)
- [How Senior Employees Carry Software Between Firms](https://ramp.com/data/am-i-just-a-teck-stack-to-you-how-senior-employees-carry-software-between-firms) - Ryan Stevens, Ramp (August 2026). Links spending and Revelio Labs employment data to study AI adoption following technical hires. Associations depend on observing both employers and can reflect workers moving within the same industry. [![Industry][industry-badge]](#reading-the-labels)

### Enterprise returns and measurement

*When do task gains translate into firm output and financial returns?*

- [Firm Data on AI](https://www.nber.org/papers/w34836) - Yotzov and coauthors (2026 working paper). Executive surveys across four countries distinguish reported past effects from expectations about future productivity, output, and employment. [![Study][study-badge]](#reading-the-labels)
- [The Productivity J-Curve](https://www.nber.org/papers/w25148) - Brynjolfsson, Rock, and Syverson (2018 working paper; published 2021). Explains how investment in processes and skills can delay measured gains from a general-purpose technology. [![Theory][theory-badge]](#reading-the-labels)
- [The Rise of Industrial AI in America: Microfoundations of the Productivity J-curve(s)](https://mackinstitute.wharton.upenn.edu/wp-content/uploads/2025/04/McElheran-et-al.-Industrial_AI_April-20-2025.pdf) - McElheran and coauthors (April 2025 working paper). Studies manufacturing adoption, adjustment costs, and productivity using U.S. Census-linked data. Covers industrial AI before the current generative AI wave. [![Study][study-badge]](#reading-the-labels)

Reported time savings are one input to a return calculation. Implementation, review, training, and operating costs also matter. Survey expectations and causal estimates answer different questions.

### Deployment costs and reliability

*What does it cost to turn a model into a dependable production system?*

- [State of AI Engineering](https://www.datadoghq.com/state-of-ai-engineering/) - Datadog (2026 edition). Customer usage data on model portfolios, context size, caching, and failures. Shows operational drivers of cost and reliability, with a sample drawn from Datadog customers. [![Report][report-badge]](#reading-the-labels)
- [State of Agent Engineering](https://www.langchain.com/state-of-agent-engineering) - LangChain (November to December 2025 survey). Practitioner responses on deployment, evaluation, latency, quality, and cost barriers. The voluntary sample is concentrated in technology firms. [![Report][report-badge]](#reading-the-labels)

### Organizational change and teamwork

*How does AI change the way expertise and work are organized?*

- [The Cybernetic Teammate](https://www.nber.org/papers/w33641) - Dell’Acqua and coauthors (2025 working paper; published 2026). A randomized field experiment at Procter & Gamble comparing individuals and teams with and without AI. [![Study][study-badge]](#reading-the-labels)
- [Artificial Intelligence and Human Capital: Challenges for Central Banks](https://www.bis.org/publications/bulletin-100-artificial-intelligence-and-human-capital-challenges-central-banks) - Bell and coauthors, BIS (2025). Uses central banking to examine staff skills, workflow redesign, oversight, and possible differences between assistants and agents. Combines current practice with future scenarios. [![Report][report-badge]](#reading-the-labels)

### Customer service and knowledge work

*Where have deployments produced measured gains, and where do results vary?*

- [Generative AI at Work](https://www.nber.org/papers/w31161) - Brynjolfsson, Li, and Raymond (2023 working paper). Studies an AI assistant in customer support and differences in productivity effects across workers. [![Study][study-badge]](#reading-the-labels)
- [Navigating the Jagged Technological Frontier](https://aiinstitute.hbs.edu/navigating-the-jagged-technological-frontier/) - Dell’Acqua and coauthors (2023). Harvard’s research summary links to a field experiment on consultants, task performance, and the limits of AI assistance. [![Study][study-badge]](#reading-the-labels)
- [Experimental Evidence on the Productivity Effects of Generative Artificial Intelligence](https://pubmed.ncbi.nlm.nih.gov/37440646/) - Noy and Zhang (2023, Science). A preregistered experiment on professional writing tasks measures completion time and output quality. An online task experiment, with limits to generalizing to full jobs or firm returns. [![Study][study-badge]](#reading-the-labels)

### Software development

*How do AI tools affect completion time on real software tasks?*

- [Early-2025 AI and Experienced Open-Source Developer Productivity](https://metr.org/blog/2025-07-10-early-2025-ai-experienced-os-dev-study/) - Becker and coauthors, METR (2025). A randomized study of experienced developers working in familiar repositories. Reports a slowdown in that setting and explains limits to generalization. [![Study][study-badge]](#reading-the-labels)
- [Changing the Developer Productivity Experiment Design](https://metr.org/blog/2026-02-24-uplift-update/) - METR (2026). Explains why participation and task-selection changes limit conclusions from its follow-up experiment. Read alongside the 2025 study. [![Study][study-badge]](#reading-the-labels)
- [How Much Does AI Impact Development Speed? An Enterprise-Based Randomized Controlled Trial](https://arxiv.org/abs/2410.12944) - Paradis and coauthors (2024 preprint). An experiment with Google engineers finds faster completion of a complex task using internal AI tools. The authors caution that results may differ across tools, tasks, and settings. [![Study][study-badge]](#reading-the-labels)

## Labor, growth, and policy

### Task exposure and automation

*Which tasks could AI affect, and how is exposure measured?*

- [GPTs Are GPTs](https://arxiv.org/abs/2303.10130) - Eloundou, Manning, Mishkin, and Rock (2023). Estimates occupational exposure to language models using task descriptions. Exposure is not a forecast of job losses. [![Study][study-badge]](#reading-the-labels)
- [Generative AI and Jobs: A Refined Global Index of Occupational Exposure](https://www.ilo.org/publications/generative-ai-and-jobs-refined-global-index-occupational-exposure) - International Labour Organization and NASK (2025). A global framework for comparing task exposure across occupations and countries. [![Study][study-badge]](#reading-the-labels)
- [Working with AI: Measuring the Applicability of Generative AI to Occupations](https://arxiv.org/abs/2507.07935) - Tomlinson and coauthors (2025 preprint; revised December 2025). Maps Bing Copilot conversations to work activities and occupations. Measures applicability in observed use, rather than job displacement or economy-wide adoption. [![Study][study-badge]](#reading-the-labels)
- [Nine Raters, One Index: Carrying LLM Disagreement into Labour-Market Estimates](https://arxiv.org/abs/2507.22748) - Henseke and coauthors (2025 preprint; revised August 2026). Shows how the choice of language model used to rate tasks changes exposure measures and downstream estimates. Useful for judging uncertainty in occupation rankings. [![Study][study-badge]](#reading-the-labels)

### Employment and wages

*What changes in earnings, hours, and work are visible in observed data?*

- [Still Waters, Rapid Currents: Early Labor Market Transformation under Generative AI](https://www.nber.org/papers/w33777) - Humlum and Vestergaard (2025 working paper, subsequently revised). Links Danish adoption surveys to administrative labor records. Previously titled *Large Language Models, Small Labor Market Effects*. [![Study][study-badge]](#reading-the-labels)
- [Companies Hire More after AI Adoption](https://ramp.com/data/heavy-ai-adopters-hire-more) - Ara Kharazian, Ramp (June 2026). An accessible summary of a working paper linking AI spending to Revelio Labs workforce data, with a link to the study. Separates adoption intensity and entry-level hiring; adopters differ from other firms before adoption, so the headline is not a general causal conclusion. [![Industry][industry-badge]](#reading-the-labels)

### Skills and new tasks

*How do new tasks offset displacement, and which skills become more valuable?*

- [Automation and New Tasks](https://www.nber.org/papers/w25684) - Acemoglu and Restrepo (2019). A framework for displacement, new task creation, and labor demand, supported by historical evidence. [![Theory][theory-badge]](#reading-the-labels)
- [Unpacking Skill Bias: Automation and New Tasks](https://www.nber.org/papers/w26681) - Acemoglu and Restrepo (2020). Connects changes in task allocation to skill demand and wage inequality. [![Theory][theory-badge]](#reading-the-labels)

### Inequality and distribution

*Who receives the gains from AI, and who may lose income?*

- [Artificial Intelligence and Its Implications for Income Distribution and Unemployment](https://www.nber.org/papers/w24174) - Korinek and Stiglitz (2017 working paper; chapter published 2019). Models innovation gains, changes in returns to labor and capital, and possible compensation for those who lose. [![Theory][theory-badge]](#reading-the-labels)
- [Artificial Intelligence and the Skill Premium](https://www.iza.org/publications/dp/16972/artificial-intelligence-and-the-skill-premium) - Bloom, Prettner, Saadaoui, and Veruete (2024 discussion paper). Models how AI and robots affect wage differences between skill groups. Results depend on how readily technology substitutes for different workers. [![Theory][theory-badge]](#reading-the-labels)

### Economic growth and transformative AI

*Under which assumptions does AI produce modest gains or much faster growth?*

- [The Simple Macroeconomics of AI](https://www.nber.org/papers/w32487) - Daron Acemoglu (2024 working paper; published 2025). Connects affected tasks and cost savings to aggregate productivity. Useful for examining the assumptions behind modest growth estimates. [![Theory][theory-badge]](#reading-the-labels)
- [Artificial Intelligence and Economic Growth](https://www.nber.org/papers/w23928) - Aghion, Jones, and Jones (2017 working paper; chapter published 2019). Studies automation, research, bottlenecks, and possible growth paths. [![Theory][theory-badge]](#reading-the-labels)
- [The Economics of Transformative AI](https://www.nber.org/books-and-chapters/economics-transformative-ai) - Agrawal, Brynjolfsson, and Korinek, editors (2026). A research volume spanning agents, measurement, competition, innovation, and broader economic change. [![Book][book-badge]](#reading-the-labels)
- [Forecasting the Economic Effects of AI](https://forecastingresearch.org/research/economic-effects-of-ai) - Karger, Kuusela, and coauthors (2026 working paper). Compares economic forecasts from economists, AI experts, forecasters, and the public under alternative capability scenarios. Measures beliefs and disagreement, not realized effects. [![Study][study-badge]](#reading-the-labels)
- [Macroeconomic Productivity Gains from Artificial Intelligence in G7 Economies](https://www.oecd.org/en/publications/macroeconomic-productivity-gains-from-artificial-intelligence-in-g7-economies_a5319ab5-en.html) - Filippucci and coauthors, OECD (2025). Connects task-level gains, sector composition, and adoption assumptions to growth scenarios across G7 economies. Useful for comparing why projected gains differ by country. [![Report][report-badge]](#reading-the-labels)

### Innovation and research productivity

*Can AI accelerate discovery, and what still limits research?*

- [Artificial Intelligence in Research and Development](https://www.nber.org/papers/w34312) - Benjamin Jones (2025 working paper). Models how task coverage, AI productivity, and bottlenecks determine returns to research investment. [![Theory][theory-badge]](#reading-the-labels)

### Trade and economic development

*How could AI change the advantages of countries and their development paths?*

- [Artificial Intelligence, Globalization, and Strategies for Economic Development](https://www.nber.org/papers/w28453) - Korinek and Stiglitz (2021). Examines labor-saving technology, global concentration, and policy choices for developing economies. [![Theory][theory-badge]](#reading-the-labels)
- [What Did US Export Controls Mean for China’s AI Capabilities?](https://epoch.ai/gradient-updates/us-export-controls-china-ai) - Ege Erdil, Epoch AI (December 2024). Explains how chip restrictions can affect training and inference costs differently. A dated analytical essay about the rules then in place, not a guide to current restrictions. [![Overview][overview-badge]](#reading-the-labels)

### Taxation and social protection

*How can governments distribute gains and support workers during the transition?*

- [Broadening the Gains from Generative AI: The Role of Fiscal Policies](https://www.imf.org/en/Publications/Staff-Discussion-Notes/Issues/2024/06/11/Broadening-the-Gains-from-Generative-AI-The-Role-of-Fiscal-Policies-549639) - Brollo and coauthors, IMF (2024). Discusses tax design, social protection, and public investment under different AI scenarios. [![Report][report-badge]](#reading-the-labels)
- [Economic Policy for AGI](https://institute.deepmind.com/essays/economic-policy-for-agi/) - Julian Jacobs and Alex Imas, Google DeepMind (September 2026). Compares 11 policies, including wage support, retraining, income guarantees, and capital ownership, across possible AGI futures. Policy scores use simulated economist personas alongside literature reviews and surveys; they are not observed policy effects. [![Overview][overview-badge]](#reading-the-labels)

### Sovereign AI and industrial policy

*What can public investment achieve, and which foreign dependencies remain?*

- [Sovereign AI Index](https://interactives.cnas.org/reports/sovereign-ai-index/) - Center for a New American Security (2026). Tracks government-backed compute, model, and data projects, including status, partners, and disclosed investment. Announcements and commitments do not establish completed capacity. [![Data][data-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)
- [Is AI Sovereignty Possible? Balancing Autonomy and Interdependence](https://www.brookings.edu/articles/is-ai-sovereignty-possible-balancing-autonomy-and-interdependence/) - Tanner and coauthors, Brookings and CEPS (2026). Examines the costs, dependencies, and trade-offs of national AI strategies, including risks of duplicated or underused public investment. [![Report][report-badge]](#reading-the-labels)

### Regulation and competition policy

*Which market rules could support entry, innovation, and consumer welfare?*

- [AI Foundation Models: Update Paper](https://www.gov.uk/government/publications/ai-foundation-models-update-paper) - UK Competition and Markets Authority (2024). An institutional analysis of foundation-model markets, partnerships, and competition risks, with a detailed technical report. [![Report][report-badge]](#reading-the-labels)

Related material: [cloud market investigation](#cloud-markets-and-capacity-pricing), [AI competition and welfare](#competition-and-market-power), and [copyright and licensing](#data-markets-and-intellectual-property).

## Courses and learning materials

- [The Economics of Transformative AI](https://digitaleconomy.stanford.edu/about/education/the-economics-of-transformative-ai/) - Stanford Digital Economy Lab (2025 materials). Lectures, slides, readings, and exercises on growth, automation, distribution, and governance. Best for readers comfortable with economic theory. [![Course][course-badge]](#reading-the-labels) [![Videos][videos-badge]](#reading-the-labels) [![Slides][slides-badge]](#reading-the-labels) [![Exercises][exercises-badge]](#reading-the-labels)
- [The Economics of AI](https://www.coursera.org/learn/economics-of-ai/) - Anton Korinek, University of Virginia. A structured introduction to AI, growth, labor markets, and economic policy. Access to materials and assessments depends on Coursera enrollment terms. [![Course][course-badge]](#reading-the-labels)

For the practitioner seminar, see [Economics of the AI Supercycle](#start-here). Its public page describes the seminar and speakers; it does not establish that a full lecture archive is available.

## Related collections

- [Economics of AI Literature Atlas](https://www.benkimuva.com/projects/ai-economics-atlas) - A searchable map of economic research on AI, with links to source records. [![Collection][collection-badge]](#reading-the-labels)
- [Ramp Economics Lab](https://ramp.com/data) - Research archive on business spending, including AI adoption, supplier competition, compute demand, and hiring. Based mainly on Ramp customer data; selected AI readings appear in the relevant sections above. [![Collection][collection-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)
- [SemiAnalysis](https://newsletter.semianalysis.com/) - Research archive on chips, GPU clouds, data centers, and AI business economics, with additional tools and models on the [main site](https://semianalysis.com/). Selected articles appear in the relevant sections above. Many full articles and institutional models require paid access. [![Collection][collection-badge]](#reading-the-labels) [![Living][living-badge]](#reading-the-labels)

## Contributing

Suggest a resource, improve an annotation, or report a broken link. Read [CONTRIBUTING.md](CONTRIBUTING.md) for scope, entry format, and review criteria.

Prefer an original paper, dataset, course page, official report, or clearly attributed industry analysis. Explain the economic question the resource helps answer. Keep distinct findings and competing explanations visible.

Currently maintained by [Gautam Jajoo](https://github.com/gautamjajoo).
