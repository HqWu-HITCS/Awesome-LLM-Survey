# Awesome-LLM-Survey

[![Awesome](https://camo.githubusercontent.com/64f8905651212a80869afbecbf0a9c52a5d1e70beab750dea40a994fa9a9f3c6/68747470733a2f2f617765736f6d652e72652f62616467652e737667)](https://github.com/HqWu-HITCS/Awesome-LLM-Survey) 
![](https://img.shields.io/github/last-commit/HqWu-HITCS/Awesome-LLM-Survey?color=green)
[![GitHub Repo stars](https://img.shields.io/github/stars/HqWu-HITCS/Awesome-LLM-Survey?style=social)](https://github.com/luban-agi/Awesome-Domain-LLM)

This repo aims to record survey of LLM, including instruction tuning, human alignment, LLM agent, hallucination, multi-modal, etc. 

We strongly encourage the researchers that want to promote their fantastic work to the LLM survey community to make pull request to update their paper's information!

- [Awesome-LLM-Survey](#awesome-llm-survey)
  - [General Survey](#general-survey)
  - [Training of LLM](#training-of-llm)
    - [Instruction Tuning](#instruction-tuning)
    - [Human Alignment for LLM](#human-alignment-for-llm)
  - [Prompt of LLM](#prompt-of-llm)
    - [Chain of Thought for LLM](#chain-of-thought-for-llm)
    - [Prompt Engineering for LLM](#prompt-engineering-for-llm)
    - [Retrieval-Augmented LLM](#retrieval-augmented-llm)
  - [Challenge of LLM](#challenge-of-llm)
    - [Hallucination in LLM](#hallucination-in-llm)
    - [Compression for LLM](#compression-for-llm)
    - [Evaluation of LLM](#evaluation-of-llm)
    - [Reasoning with LLM](#reasoning-with-llm)
    - [Explainability for LLM](#explainability-for-llm)
    - [Fairness in LLM](#fairness-in-llm)
    - [Graph for LLM](#graph-for-llm)
    - [Long-Context for LLM](#long-context-for-llm)
    - [Factuality in LLM](#factuality-in-llm)
    - [Knowledge for LLM](#knowledge-for-llm)
    - [Self-Correction for LLM](#self-correction-for-llm)
    - [Attributions for LLM](#attributions-for-llm)
    - [Tool Using of LLM](#tool-using-of-llm)
    - [Calibration of LLM](#calibration-of-llm)
    - [Agent of LLM](#agent-of-llm)
    - [Vulnerabilities of LLM](#vulnerabilities-of-llm)
    - [Efficiency of LLM](#efficiency-of-llm)
    - [Data of LLM](#data-of-llm)
    - [Security and Privacy of LLM](#security-and-privacy-of-llm)
  - [Mulitmodal of LLM](#mulitmodal-of-llm)
    - [Visual LLM](#visual-llm)
    - [Audio LLM](#audio-llm)
    - [Code LLM](#code-llm)
  - [LLM for Domain Application](#llm-for-domain-application)
    - [LLM for Health](#llm-for-health)
    - [LLM for Finance](#llm-for-finance)
    - [LLM for Education](#llm-for-education)
    - [LLM for Law](#llm-for-law)
    - [LLM for Mental Health](#llm-for-mental-health)
    - [LLM for Robotics](#llm-for-robotics)
  - [LLM for Downstream Tasks](#llm-for-downstream-tasks)
    - [LLM for Recommendation](#llm-for-recommendation)
    - [LLM for Information Retrieval](#llm-for-information-retrieval)
    - [LLM for Software Engineering](#llm-for-software-engineering)
    - [LLM for Autonomous Driving](#llm-for-autonomous-driving)
    - [LLM for Time Series](#llm-for-time-series)
    - [Detection of LLMs-Generated Content](#detection-of-llms-generated-content)
    - [LLM for Society](#llm-for-society)
    - [LLM for Citation](#llm-for-citation)
    - [LLM for Text Watermarking](#llm-for-text-watermarking)
    - [LLM for Math](#llm-for-math)
    - [LLM for Environ Disciplines](#llm-for-environ-disciplines)
    - [LLM for Information Extraction](#llm-for-information-extraction)
  - [Star History](#star-history)


---

## General Survey
- A Survey of Large Language Models, 2023.11 [[paper]](https://arxiv.org/abs/2303.18223)[[project]](https://github.com/RUCAIBox/LLMSurvey)

- A Survey of GPT-3 Family Large Language Models Including ChatGPT and GPT-4, 2023.10 [[paper]](https://arxiv.org/pdf/2310.12321.pdf)

- Challenges and Applications of Large Language Models, 2023.07 [[paper]](https://arxiv.org/abs/2307.10169)

- Harnessing the Power of LLMs in Practice: A Survey on ChatGPT and Beyond, 2023.04  [[paper]](https://arxiv.org/abs/2304.13712)[[project]](https://github.com/Mooler0410/LLMsPracticalGuide)

- A Comprehensive Survey on Pretrained Foundation Models: A History from BERT to ChatGPT, 2023.02 [[paper]](https://arxiv.org/abs/2302.09419)

- Large language models: a comprehensive survey of its applications, challenges, limitations, and future prospects, 2023.12 [[paper]](https://www.techrxiv.org/doi/full/10.36227/techrxiv.23589741.v4) [[project]](https://github.com/anas-zafar/LLM-Survey)

- The future of gpt: A taxonomy of existing chatgpt research, current challenges, and possible future directions, 2023.04 [[paper]](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4413921)

- A Review on Large Language Models: Architectures, Applications, Taxonomies, Open Issues and Challenges, 2023.10 [[paper]](https://www.techrxiv.org/doi/full/10.36227/techrxiv.24171183.v1)
- Understanding LLMs: A Comprehensive Overview from Training to Inference, 2024.01 [[paper]](https://arxiv.org/pdf/2401.02038.pdf)
---

## Training of LLM


### Instruction Tuning
- Are Prompts All the Story? No. A Comprehensive and Broader View of Instruction Learning, 2023.03 [[paper]](https://arxiv.org/pdf/2303.10475.pdf) [[project]](https://github.com/RenzeLou/awesome-instruction-learning)
- Vision-Language Instruction Tuning: A Review and Analysis, 2023,11 [[paper]](https://arxiv.org/abs/2311.08172)[[project]](https://github.com/palchenli/VL-Instruction-Tuning)
- Instruction Tuning for Large Language Models: A Survey, 2023.08 [[paper]](https://arxiv.org/abs/2308.10792)

### Human Alignment for LLM
- AI Alignment: A Comprehensive Survey, 2023.10 [[paper]](https://arxiv.org/pdf/2310.19852)[[project]](https://www.alignmentsurvey.com)
  
- Large Language Model Alignment: A Survey, 2023.09 [[paper]](https://arxiv.org/abs/2309.15025)
  
- From Instructions to Intrinsic Human Values -- A Survey of Alignment Goals for Big Model, 2023.08 [[paper]](https://arxiv.org/abs/2308.12014)[[project]](https://github.com/ValueCompass/Alignment-Goal-Survey)
  
- Aligning Large Language Models with Human: A Survey, 2023.07 [[paper]](https://arxiv.org/abs/2307.12966)[[project]](https://github.com/GaryYufei/AlignLLMHumanSurvey)

---

## Prompt of LLM


### Chain of Thought for LLM
- Towards Better Chain-of-Thought Prompting Strategies: A Survey, 2023.10 [[paper]](https://arxiv.org/pdf/2310.04959.pdf)
  
- A Survey of Chain of Thought Reasoning: Advances, Frontiers and Future, 2023.09 [[paper]](https://arxiv.org/abs/2309.06256)[[project]](https://github.com/zchuz/CoT-Reasoning-Survey)
- Igniting Language Intelligence: The Hitchhiker's Guide From Chain-of-Thought Reasoning to Language Agents, 2023.11 [[paper]](https://arxiv.org/pdf/2311.11797.pdf) [[project]](https://github.com/Zoeyyao27/CoT-Igniting-Agent)
  

### Prompt Engineering for LLM
- Prompting Frameworks for Large Language Models: A Survey, 2023.11 [[paper]](https://arxiv.org/pdf/2311.12785.pdf)[[project]](https://github.com/lxx0628/Prompting-Framework-Survey)

- Unleashing the potential of prompt engineering in Large Language Models: a comprehensive review, 2023.10 [[paper]](https://arxiv.org/pdf/2310.14735.pdf)

- Towards Better Chain-of-Thought Prompting Strategies: A Survey, 2023.10 [[paper]](https://arxiv.org/pdf/2310.04959.pdf)

### Retrieval-Augmented LLM
- A Survey on Retrieval-Augmented Text Generation, 2022.02 [[paper]](https://arxiv.org/abs/2202.01110)
- Retrieval-Augmented Generation for Large Language Models: A Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2312.10997.pdf) [[project]](https://github.com/Tongji-KGLLM/RAG-Survey)
---

## Challenge of LLM


### Hallucination in LLM
- Can Knowledge Graphs Reduce Hallucinations in LLMs? : A Survey, 2023.11 [[paper]](https://arxiv.org/pdf/2311.07914)
  
- A Survey on Hallucination in Large Language Models: Principles, Taxonomy, Challenges, and Open Questions, 2023.11 [[paper]](https://arxiv.org/pdf/2311.05232)[[project]](https://github.com/LuckyyySTA/Awesome-LLM-hallucination)
  
- A Survey of Hallucination in “Large” Foundation Models, 2023.09  [[paper]](https://arxiv.org/paper/2309.05922)[[project]](https://github.com/vr25/hallucination-foundation-model-survey)
  
- Siren's Song in the AI Ocean: A Survey on Hallucination in Large Language Models, 2023.09 [[paper]](https://arxiv.org/abs/2309.01219)[[project]](https://arxiv.org/abs/2309.01219)
  
- Cognitive Mirage: A Review of Hallucinations in Large Language Models, 2023.09 [[paper]](https://arxiv.org/paper/2309.06794.paper)[[project]](https://github.com/hongbinye/Cognitive-Mirage-Hallucinations-in-LLMs)

- Augmenting LLMs with Knowledge: A survey on hallucination prevention, 2023.09 [[paper]](https://arxiv.org/pdf/2309.16459.pdf)
- A Comprehensive Survey of Hallucination Mitigation Techniques in Large Language Models, 2024.01 [[paper]](https://arxiv.org/pdf/2401.01313.pdf)

### Compression for LLM
- A Survey on Model Compression for Large Language Models, 2023.08 [[paper]](https://arxiv.org/abs/2308.07633)

### Evaluation of LLM
- Evaluating Large Language Models: A Comprehensive Survey, 2023.10 [[paper]](https://arxiv.org/pdf/2310.19736.pdf)[[project]](https://github.com/tjunlp-lab/Awesome-LLMs-Evaluation-Papers)
  
- A Survey on Evaluation of Large Language Models, 2023.07 [[paper]](https://arxiv.org/abs/2307.03109)[[project]](https://llm-eval.github.io/)

### Reasoning with LLM
- Reasoning with Language Model Prompting: A Survey, 2022.12 [[paper]](https://arxiv.org/abs/2212.09597)[[project]](https://github.com/zjunlp/Prompt4ReasoningPapers)

- A Survey of Reasoning with Foundation Models, 2023.12 [[papaer]](https://arxiv.org/pdf/2312.11562.pdf)[[project]](https://github.com/reasoning-survey/Awesome-Reasoning-Foundation-Models)
### Explainability for LLM
- Explainability for Large Language Models: A Survey, 2023.09 [[paper]](https://arxiv.org/abs/2309.01029)
- The Mystery and Fascination of LLMs: A Comprehensive Survey on the Interpretation and Analysis of Emergent Abilitie, 2023.11 [[paper]](https://arxiv.org/pdf/2311.00237.pdf)
- If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents, 2024.01 [[paper]](https://arxiv.org/pdf/2401.00812.pdf)
### Fairness in LLM
- A Survey on Fairness in Large Language Models, 2023.08 [[paper]](https://arxiv.org/abs/2308.10149)

### Graph for LLM
- A Survey of Graph Meets Large Language Model: Progress and Future Directions, 2023.11 [[paper]](https://arxiv.org/pdf/2311.12399)
- Large Language Models on Graphs: A Comprehensive Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2312.02783.pdf) [[project]](https://github.com/PeterGriffinJin/Awesome-Language-Model-on-Graphs)

### Long-Context for LLM
- Advancing Transformer Architecture in Long-Context Large Language Models: A Comprehensive Survey, 2023.11 [[paper]](https://arxiv.org/pdf/2311.12351)
- Length Extrapolation of Transformers: A Survey from the Perspective of Position Encoding, 2023.12 [[paper]](https://arxiv.org/abs/2312.17044)

### Factuality in LLM
- A Survey on Factuality in Large Language Models: Knowledge, Retrieval and Domain-Specificity, 2023.10 [[paper]](https://arxiv.org/abs/2310.07521)[[project]](https://github.com/wangcunxiang/LLM-Factuality-Survey)
  
- Give Me the Facts! A Survey on Factual Knowledge Probing in Pre-trained Language Models, 2023.10 [[paper]](https://arxiv.org/pdf/2310.16570.pdf)

### Knowledge for LLM
- Knowledge Unlearning for LLMs: Tasks, Methods, and Challenges, 2023.11 [[paper]](https://arxiv.org/pdf/2311.15766)

- Trends in Integration of Knowledge and Large Language Models: A Survey and Taxonomy of Methods, Benchmarks, and Applications, 2023.11 [[paper]](https://arxiv.org/pdf/2311.05876.pdf)
  
- Knowledge Editing for Large Language Models: A Survey, 2023.10 [[paper]](https://arxiv.org/pdf/2310.16218.pdf)
  
- Editing Large Language Models: Problems, Methods, and Opportunities, 2023.05 [[paper]](https://arxiv.org/abs/2305.13172)[[project]](https://github.com/zjunlp/EasyEdit)

- Building trust in conversational ai: A comprehensive review and solution architecture for explainable, privacy-aware systems using llms and knowledge graph, 2023.08 [[paper]](https://arxiv.org/pdf/2308.13534.pdf)

### Self-Correction for LLM
- Automatically Correcting Large Language Models: Surveying the landscape of diverse self-correction strategies, 2023.08 [[paper]](https://arxiv.org/abs/2308.03188)[[project]](https://github.com/teacherpeterpan/self-correction-llm-papers)

### Attributions for LLM
- A Survey of Large Language Models Attribution, 2023.11 [[paper]](https://arxiv.org/pdf/2311.03731)[[project]](https://github.com/HITsz-TMG/awesome-llm-attributions)

### Tool Using of LLM
- Foundation Models for Decision Making: Problems, Methods, and Opportunities, 2023.03 [[paper]](https://arxiv.org/abs/2303.04129)
  
- Augmented Language Models: a Survey, 2023.02 [[paper]](https://arxiv.org/abs/2302.07842)

### Calibration of LLM
- A Survey of Language Model Confidence Estimation and Calibration, 2023.11 [[paper]](https://arxiv.org/pdf/2311.08298.pdf)

### Agent of LLM
- A Survey on Large Language Model based Autonomous Agents, 2023.08 [[paper]](https://arxiv.org/abs/2308.11432)[[project]](https://github.com/Paitesanshi/LLM-Agent-Survey)
- The Rise and Potential of Large Language Model Based Agents: A Survey, 2023.09 [[paper]](https://arxiv.org/abs/2309.07864)[[project]](https://github.com/WooooDyy/LLM-Agent-Paper-List)
- Large Language Models Empowered Agent-based Modeling and Simulation: A Survey and Perspectives, 2023.12 [[paper]](https://arxiv.org/pdf/2312.11970.pdf)

### Vulnerabilities of LLM
- Survey of Vulnerabilities in Large Language Models Revealed by Adversarial Attacks, 2023.10 [[paper]](https://arxiv.org/pdf/2310.10844.pdf)

### Efficiency of LLM
- The Efficiency Spectrum of Large Language Models: An Algorithmic Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2310.10844.pdf)[[project]](https://github.com/tding1/Efficient-LLM-Survey)
- Efficient Large Language Models: A Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2312.03863)[[project]](https://github.com/AIoT-MLSys-Lab/Efficient-LLMs-Survey)
- Parameter-Efficient Fine-Tuning Methods for Pretrained Language Models: A Critical Review and Assessment, 2023.12 [[paper]](https://arxiv.org/pdf/2312.12148.pdf)

### Data of LLM
- Data Management For Large Language Models: A Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2312.01700)[[project]](https://github.com/ZigeW/data_management_LLM)

### Security and Privacy of LLM
- A Survey on Large Language Model (LLM) Security and Privacy: The Good,  the Bad, and the Ugly, 2023.12 [[paper]](https://arxiv.org/pdf/2312.02003)

---

## Mulitmodal of LLM


### Visual LLM
- Vision-Language Instruction Tuning: A Review and Analysis, 2023,11 [[paper]](https://arxiv.org/abs/2311.08172)[[project]](https://github.com/palchenli/VL-Instruction-Tuning)
- How to Bridge the Gap between Modalities: A Comprehensive Survey on Multimodal Large Language Model, 2023.11 [[paper]](https://arxiv.org/pdf/2311.07594.pdf)
  
- A Survey on Multimodal Large Language Models, 2023.06 [[paper]](https://arxiv.org/abs/2306.13549)[[project]](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models)

- Multimodal Large Language Models: A Survey, 2023.11 [[paper]](https://arxiv.org/pdf/2311.13165.pdf)
- Large Language Models Meet Computer Vision: A Brief Survey, 2023.11 [[paper]](https://arxiv.org/pdf/2311.16673.pdf)
- Foundational Models Defining a New Era in Vision: A Survey and Outlook, 2023.07 [[paper]](https://arxiv.org/pdf/2307.13721.pdf)[[project]](https://github.com/awaisrauf/Awesome-CV-Foundational-Models)

- Video Understanding with Large Language Models: A Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2312.17432.pdf) [[project]](https://github.com/yunlong10/Awesome-LLMs-for-Video-Understanding)

### Audio LLM
- Sparks of large audio models: A survey and outlook, 2023.08 [[paper]](https://arxiv.org/pdf/2308.12792.pdf) [[project]](https://github.com/EmulationAI/awesome-large-audio-models)

### Code LLM
- A Survey on Language Models for Code, 2023.11 [[paper]](https://arxiv.org/pdf/2311.07989)[[project]](https://github.com/codefuse-ai/Awesome-Code-LLM)
- Pitfalls in Language Models for Code Intelligence: A Taxonomy and Survey, 2023.10 [[paper]](https://arxiv.org/pdf/2310.17903.pdf)[[project]](https://github.com/yueyueL/ReliableLM4Code)
- Large Language Models Meet NL2Code: A Survey, 2022.12 [[paper]](https://arxiv.org/abs/2212.09420)
- A Prompt Learning Framework for Source Code Summarization, 2023.12 [[paper]](https://arxiv.org/pdf/2312.16066.pdf)
- If LLM Is the Wizard, Then Code Is the Wand: A Survey on How Code Empowers Large Language Models to Serve as Intelligent Agents, 2024.01 [[paper]](https://arxiv.org/abs/2401.00812)

---

## LLM for Domain Application


### LLM for Health
- A Survey of Large Language Models in Medicine: Progress, Application, and Challenge, 2023.11 [[paper]](https://arxiv.org/pdf/2311.05112)[[project]](https://github.com/AI-in-Health/MedLLMsPracticalGuide)
  
- Large Language Models Illuminate a Progressive Pathway to Artificial  Healthcare Assistant: A Review, 2023.10 [[paper]](https://arxiv.org/pdf/2311.01918)[[project]](https://github.com/mingze-yuan/Awesome-LLM-Healthcare)
  
- Large AI Models in Health Informatics: Applications, Challenges, and the Future, 2023.03 [[paper]](https://arxiv.org/abs/2303.11568)[[project]](https://github.com/Jianing-Qiu/Awesome-Healthcare-Foundation-Models)
  
- A SWOT (Strengths, Weaknesses, Opportunities, and Threats) Analysis of ChatGPT in the Medical Literature: Concise Review, 2023.11 [[paper]](https://www.jmir.org/2023/1/e49368/PDF)

- ChatGPT in Healthcare: A Taxonomy and Systematic Review, 2023.03 [[paper]](https://www.medrxiv.org/content/10.1101/2023.03.30.23287899v1)

### LLM for Finance
- Large Language Models in Finance: A Survey, 2023.09 [[paper]](https://arxiv.org/abs/2311.10723)

### LLM for Education
- ChatGPT and Beyond: The Generative AI Revolution in Education, 2023.11 [[paper]](https://arxiv.org/pdf/2311.15198)

### LLM for Law
- Large Language Models in Law: A Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2312.03718)

### LLM for Mental Health
- A review of the explainability and safety of conversational agents for mental health to identify avenues for improvement, 2023.10 [[paper]](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10601652/)
- Towards a Psychological Generalist AI: A Survey of Current Applications of Large Language Models and Future Prospects, 2023.12 [[paper]](https://arxiv.org/pdf/2312.04578.pdf)
- Large Language Models in Mental Health Care: a Scoping Review, 2024.01 [[paper]](https://arxiv.org/pdf/2401.02984.pdf)

### LLM for Robotics
-  Large Language Models for Robotics: A Survey, 2023.11 [[paper]](https://arxiv.org/pdf/2311.07226.pdf)
---

## LLM for Downstream Tasks


### LLM for Recommendation
- User Modeling in the Era of Large Language Models: Current Research and Future Directions, 2023.12 [[paper]](https://doi.org/10.48550/arXiv.2312.11518)[[project]](https://github.com/TamSiuhin/LLM-UM-Reading)
- A Survey on Large Language Models for Personalized and Explainable  Recommendations, 2023.11 [[paper]](https://arxiv.org/pdf/2311.12338)
- Large Language Models for Generative Recommendation: A Survey and Visionary Discussions, 2023.09 [[paper]](https://arxiv.org/abs/2309.01157)
- A Survey on Large Language Models for Recommendation, 2023.08 [[paper]](https://arxiv.org/abs/2305.19860)[[project]](https://github.com/WLiK/LLM4Rec-Awesome-Papers)
- How Can Recommender Systems Benefit from Large Language Models: A Survey, 2023.06 [[paper]](https://arxiv.org/abs/2306.05817)[[project]](https://github.com/CHIANGEL/Awesome-LLM-for-RecSys)

### LLM for Information Retrieval
- Large Language Models for Information Retrieval: A Survey, 2023.08 [[paper]](https://arxiv.org/abs/2308.07107)[[project]](https://github.com/RUC-NLPIR/LLM4IR-Survey)

### LLM for Software Engineering
- Large Language Models for Software Engineering: Survey and Open Problems, 2023.10 [[paper]](https://arxiv.org/abs/2310.03533)
- Large Language Models for Software Engineering: A Systematic Literature Review, 2023.08 [[paper]](https://arxiv.org/abs/2308.10620)

### LLM for Autonomous Driving
- A Survey on Multimodal Large Language Models for Autonomous Driving, 2023.11 [[paper]](https://arxiv.org/pdf/2311.12320.pdf)
- A Survey of Large Language Models for Autonomous Driving, 2023.11 [[paper]](https://arxiv.org/pdf/2311.01043)[[project]](https://github.com/Thinklab-SJTU/Awesome-LLM4AD)

### LLM for Time Series
- Large Models for Time Series and Spatio-Temporal Data: A Survey and Outlook, 2023.10 [[paper]](https://arxiv.org/abs/2310.10196)[[project]](https://github.com/qingsongedu/Awesome-TimeSeries-SpatioTemporal-LM-LLM)

### Detection of LLMs-Generated Content
- A Survey on Detection of LLMs-Generated Content, 2023.10 [[paper]](https://arxiv.org/abs/2310.15654)[[project]](https://github.com/Xianjun-Yang/Awesome_papers_on_LLMs_detection)
- A Survey on LLM-generated Text Detection: Necessity, Methods, and Future Directions, 2023.10 [[paper]](https://arxiv.org/pdf/2310.14724.pdf)
[[project]](https://github.com/NLP2CT/LLM-generated-Text-Detection)
- Detecting ChatGPT: A Survey of the State of Detecting ChatGPT-Generated Text, 2023.09 [[paper]](https://arxiv.org/pdf/2309.07689.pdf)
### LLM for Society
- Large Language Models as Subpopulation Representative Models: A Review, 2023.10 [[paper]](https://arxiv.org/ftp/arxiv/papers/2310/2310.17888.pdf)

### LLM for Citation
- When Large Language Models Meet Citation: A Survey, 2023.09 [[paper]](https://arxiv.org/pdf/2309.09727.pdf)

### LLM for Text Watermarking
- A Survey of Text Watermarking in the Era of Large Language Models, 2023.12 [[paper]](https://arxiv.org/pdf/2312.07913.pdf)

### LLM for Math
- Mathematical Language Models: A Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2312.07622.pdf)

### LLM for Environmental Disciplines
- Recent applications of AI to environmental disciplines: A review, 2023.10 [[paper]](https://www.sciencedirect.com/science/article/abs/pii/S0048969723063325)
- Opportunities and Challenges of Applying Large Language Models in Building Energy Efficiency and Decarbonization Studies: An Exploratory Overview, 2023.12 [[paper]](https://arxiv.org/ftp/arxiv/papers/2312/2312.11701.pdf)

### LLM for Information Extraction
- Large Language Models for Generative Information Extraction: A Survey, 2023.12 [[paper]](https://arxiv.org/pdf/2312.17617.pdf) [[project]](https://github.com/quqxui/Awesome-LLM4IE-Papers)
## Star History

<a href="https://star-history.com/#HqWu-HITCS/Awesome-LLM-Survey&Date">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=HqWu-HITCS/Awesome-LLM-Survey&type=Date&theme=dark" />
    <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=HqWu-HITCS/Awesome-LLM-Survey&type=Date" />
    <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=HqWu-HITCS/Awesome-LLM-Survey&type=Date" />
  </picture>
</a>
