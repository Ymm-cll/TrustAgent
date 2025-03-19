# TrustAgent: A Survey on Trustworthy LLM Agents

## 📌 Introduction
With the rapid evolution of Large Language Models (LLMs), LLM-based agents and Multi-agent Systems (MAS) have significantly expanded the capabilities of AI ecosystems. However, this advancement has introduced more complex trustworthiness issues. This repository provides an overview of our survey paper **"A Survey on Trustworthy LLM Agents: Threats and Countermeasures"** and offers insights into threats, defenses, and evaluation techniques for LLM agents.

## 📄 Survey
**Title:** A Survey on Trustworthy LLM Agents: Threats and Countermeasures  
**Authors:** Miao Yu, Fanci Meng, Xinyun Zhou, Shilong Wang, et al.  
**Institution:** Squirrel AI Learning, Salesforce, The University of North Carolina, Nanyang Technological University, Rutgers University  
**Link:** [arXiv / Paper URL](https://arxiv.org/pdf/2503.09648)

## 💎 Table of Contents
- [📌 Introduction](#-introduction)
- [📄 Survey](#-survey)
- [💎 Table of Contents](#-table-of-contents)
- [✨ Paper Supplement](#-paper-supplement)
- [🚀 Highlights](#-highlights)
- [🏗️ TrustAgent Framework](#%EF%B8%8F-trustagent-framework)
- [📌 Key Topics](#-key-topics)
  - [1️⃣ Intrinsic Trustworthiness](#1️⃣-intrinsic-trustworthiness)
  - [2️⃣ Extrinsic Trustworthiness](#2️⃣-extrinsic-trustworthiness)
- [📖 Papers](#-papers)
  - [Intrinsic Trustworthiness](#intrinsic-trustworthiness)
    - [Brain (LLM)](#brain-llm)
    - [Memory](#memory)
    - [Tool](#tool)
  - [Extrinsic Trustworthiness](#extrinsic-trustworthiness)
    - [Agent-to-Agent](#agent-to-agent)
    - [Agent-to-Environment](#agent-to-environment)
    - [Agent-to-User](#agent-to-user)
- [🔍 Comparison with Previous Surveys](#-comparison-with-previous-surveys)
- [📥 Citation](#-citation)
- [📢 Contributing](#-contributing)
- [📧 Contact](#-contact)

## ✨ Paper Supplement
If you have additional articles, please:  

👉 [Click here to submit your article](https://forms.gle/bcSnvKganXyoLFi56)  

We will continuously update the survey and appreciate your support and contribution! 

## 🚀 Highlights
- Introduces **TrustAgent**, a modular framework for analyzing the trustworthiness of LLM-based agents.
- Categorizes trust issues into **intrinsic (brain, memory, tools)** and **extrinsic (user, agent, environment)** aspects.
- Surveys **attacks, defenses, and evaluation techniques** in multi-agent systems.
- Provides a taxonomy of threats, including **adversarial hijacking, unsafe action chains, privacy leakage, hallucinations, and fairness biases**.

## 🏗️ TrustAgent Framework
![TrustAgent Framework](./figure/trustagent_intro.png)  
## 📌 Key Topics
### 1️⃣ Intrinsic Trustworthiness
- **Brain (LLM Reasoning Module)**: Jailbreak, Prompt Injection, Backdoor Attacks.
- **Memory**: Memory Poisoning, Privacy Leakage, Short-Term Memory Misuse.
- **Tools**: Tool Manipulation, Tool Abuse, Malicious API Calls.

### 2️⃣ Extrinsic Trustworthiness
- **Agent-to-Agent**: Cooperative Attacks, Infectious Attacks, MAS Security.
- **Agent-to-User**: Personalized Attacks, Transparency Issues, Trust Calibration.
- **Agent-to-Environment**: Safety in Robotics, Autonomous Driving, Digital Threats.

# We will finish this part *very soon*!
## 📖 Papers
### Intrinsic Trustworthiness
#### Brain (LLM)
##### Attack
1. **"Describe, explain, plan and select: interactive planning with llms enables open-world multi-task agents"** (2023)  
    *Zihao Wang et al.*  [Paper](https://arxiv.org/abs/2302.01560)
   
3. **"Certifying llm safety against adversarial prompting"** (arxiv 2023)  
    *Kumar et al.*  [Paper](https://arxiv.org/abs/2309.02705)

4. **"Universal and transferable adversarial attacks on aligned language models"** (arxiv 2023)  
    *Zou et al.*  [Paper](https://arxiv.org/abs/2307.15043)

5. **"Improved techniques for optimization-based jailbreaking on large language models"** (arxiv 2024)  
    *Jia et al.*  [Paper](https://arxiv.org/abs/2405.21018)

6. **"AttnGCG: Enhancing jailbreaking attacks on LLMs with attention manipulation"** (arxiv 2024)  
    *Wang et al.*  [Paper](https://arxiv.org/abs/2410.09040)

7. **"Mrj-agent: An effective jailbreak agent for multi-round dialogue"** (arxiv 2024)  
    *Wang et al.*  [Paper](https://arxiv.org/abs/2411.03814)

8. **"PrivAgent: Agentic-based Red-teaming for LLM Privacy Leakage"** (arxiv 2024)  
    *Nie et al.*  [Paper](https://arxiv.org/abs/2412.05734)

9. **"Evil geniuses: Delving into the safety of llm-based agents"** (arxiv 2023)  
    *Tian et al.*  [Paper](https://arxiv.org/abs/2311.11855)

10. **"Pandora: Detailed llm jailbreaking via collaborated phishing agents with decomposed reasoning"** (ICLR 2024)  
    *Chen et al.*  [Paper](https://openreview.net/forum?id=9o06ugFxIj)

11. **"Agent smith: A single image can jailbreak one million multimodal llm agents exponentially fast"** (ICML 2024)  
    *Gu et al.*  [Paper](https://arxiv.org/abs/2402.08567)

12. **"The wolf within: Covert injection of malice into mllm societies via an mllm operative"** (arxiv 2024)  
    *Tan et al.*  [Paper](https://arxiv.org/html/2402.14859v1)

13. **"Prompt Injection attack against LLM-integrated Applications"** (arxiv 2023)  
    *Liu et al.*  [Paper](https://arxiv.org/abs/2306.05499)

14. **"Ignore previous prompt: Attack techniques for language models"** (arxiv 2022)  
    *Perez et al.*  [Paper](https://arxiv.org/abs/2211.09527)

15. **"Not what you've signed up for: Compromising real-world llm-integrated applications with indirect prompt injection"** (ACM Workshop on Artificial Intelligence and Security 2023)  
    *Greshake et al.*  [Paper](https://arxiv.org/abs/2302.12173)

16. **"Automatic and universal prompt injection attacks against large language models"** (arxiv 2024)  
    *Liu et al.*  [Paper](https://arxiv.org/abs/2403.04957)

17. **"Optimization-based prompt injection attack to llm-as-a-judge"** (ACM SIGSAC 2024)  
    *Shi et al.*  [Paper](https://arxiv.org/abs/2403.17710)

18. **"Abusing images and sounds for indirect instruction injection in multi-modal LLMs"** (arxiv 2023)  
    *Bagdasaryan et al.*  [Paper](https://arxiv.org/abs/2307.10490)

19. **"Breaking agents: Compromising autonomous llm agents through malfunction amplification"** (arxiv 2024)  
    *Zhang et al.*  [Paper](https://arxiv.org/abs/2407.20859)

20. **"A Survey on Backdoor Threats in Large Language Models (LLMs): Attacks, Defenses, and Evaluations"** (arxiv 2025)  
    *Zhou et al.*  [Paper](https://arxiv.org/abs/2502.05224)

21. **"Watch out for your agents! investigating backdoor threats to llm-based agents"** (arxiv 2024)  
    *Yang et al.*  [Paper](https://arxiv.org/abs/2402.11208)

22. **"DemonAgent: Dynamically Encrypted Multi-Backdoor Implantation Attack on LLM-based Agent"** (arxiv 2025)  
    *Zhu et al.*  [Paper](https://arxiv.org/abs/2502.12575)

23. **"BLAST: A Stealthy Backdoor Leverage Attack against Cooperative Multi-Agent Deep Reinforcement Learning based Systems"** (arxiv 2025)  
    *Yu et al.*  [Paper](https://arxiv.org/abs/2501.01593)


##### Defense
1. **"Moral Alignment for LLM Agents"** (arxiv 2024)  
    *Tennant et al.*  [Paper](https://arxiv.org/abs/2410.01639)

2. **"LLM agents in interaction: Measuring personality consistency and linguistic alignment in interacting populations of large language models"** (arxiv 2024)  
    *Frisch et al.*  [Paper](https://arxiv.org/abs/2402.02896)

3. **"Self-alignment of large language models via multi-agent social simulation"** (ICLR 2024)  
    *Pang et al.*  [Paper](https://arxiv.org/abs/2402.05699)

4. **"Aligning llm agents by learning latent preference from user edits"** (arxiv 2024)  
    *Gao et al.*  [Paper](https://arxiv.org/abs/2404.15269)

5. **"Large Language Model Assissted Multi-Agent Dialogue for Ontology Alignment"** (AAMAS 2024)  
    *Zhang et al.*  [Paper](https://dl.acm.org/doi/abs/10.5555/3635637.3663238)

6. **"Embedding-based classifiers can detect prompt injection attacks"** (arxiv 2024)  
    *Ayub et al.*  [Paper](https://arxiv.org/abs/2410.22284)

7. **"SLM as Guardian: Pioneering AI Safety with Small Language Models"** (arxiv 2024)  
    *Kwon et al.*  [Paper](https://arxiv.org/abs/2405.19795)

8. **"Struq: Defending against prompt injection with structured queries"** (arxiv 2024)  
    *Chen et al.*  [Paper](https://arxiv.org/abs/2402.06363)

9. **"Shieldlm: Empowering llms as aligned, customizable and explainable safety detectors"** (arxiv 2024)  
    *Zhang et al.*  [Paper](https://arxiv.org/abs/2402.16444)

10. **"Guardagent: Safeguard llm agents by a guard agent via knowledge-enabled reasoning"** (arxiv 2024)  
    *Xiang et al.*  [Paper](https://arxiv.org/abs/2406.09187)

11. **"AgentGuard: Repurposing Agentic Orchestrator for Safety Evaluation of Tool Orchestration"** (arxiv 2025)  
    *Chen et al.*  [Paper](https://arxiv.org/abs/2502.09809)

12. **"Improving factuality and reasoning in language models through multiagent debate"** (ICML 2023)  
    *Du et al.*  [Paper](https://arxiv.org/abs/2305.14325)

13. **"Good Parenting is all you need--Multi-agentic LLM Hallucination Mitigation"** (arxiv 2024)  
    *Kwartler et al.*  [Paper](https://arxiv.org/abs/2410.14262)

14. **"Autodefense: Multi-agent llm defense against jailbreak attacks"** (arxiv 2024)  
    *Zeng et al.*  [Paper](https://arxiv.org/abs/2403.04783)

##### Evaluation

1. **"Injecagent: Benchmarking indirect prompt injections in tool-integrated large language model agents"** (arxiv 2024)  
    *Zhan et al.*  [Paper](https://arxiv.org/abs/2403.02691)

2. **"Agentdojo: A dynamic environment to evaluate prompt injection attacks and defenses for LLM agents"** (NeurIPS 2025)  
    *Debenedetti et al.*  [Paper](https://arxiv.org/abs/2406.13352)

3. **"DemonAgent: Dynamically Encrypted Multi-Backdoor Implantation Attack on LLM-based Agent"** (arxiv 2025)  
    *Zhu et al.*  [Paper](https://arxiv.org/abs/2502.12575)

4. **"Redagent: Red teaming large language models with context-aware autonomous language agent"** (arxiv 2024)  
    *Xu et al.*  [Paper](https://arxiv.org/abs/2407.16667)

5. **"Riskawarebench: Towards evaluating physical risk awareness for high-level planning of llm-based embodied agents"** (arxiv 2024)  
    *Zhu et al.*  [Paper](https://arxiv.org/html/2408.04449v1)

6. **"RedCode: Risky Code Execution and Generation Benchmark for Code Agents"** (NeurIPS 2024)  
    *Guo et al.*  [Paper](https://arxiv.org/abs/2411.07781)

7. **"S-eval: Automatic and adaptive test generation for benchmarking safety evaluation of large language models"** (arxiv 2024)  
    *Yuan et al.*  [Paper](https://arxiv.org/abs/2405.14191)

8. **"Bells: A framework towards future proof benchmarks for the evaluation of llm safeguards"** (arxiv 2024)  
    *Dorn et al.*  [Paper](https://arxiv.org/abs/2406.01364)

9. **"Agent-SafetyBench: Evaluating the Safety of LLM Agents"** (arxiv 2024)  
    *Zhang et al.*  [Paper](https://arxiv.org/abs/2412.14470)

10. **"Agent security bench (asb): Formalizing and benchmarking attacks and defenses in llm-based agents"** (arxiv 2024)  
    *Zhang et al.*  [Paper](https://arxiv.org/abs/2410.02644)

11. **"Agentharm: A benchmark for measuring harmfulness of llm agents"** (arxiv 2024)  
    *Andriushchenko et al.*  [Paper](https://arxiv.org/abs/2410.09024)

12. **"R-judge: Benchmarking safety risk awareness for llm agents"** (arxiv 2024)  
    *Yuan et al.*  [Paper](https://arxiv.org/abs/2401.10019)

#### Memory
##### Attack

1. **“Certifiably Robust RAG against Retrieval Corruption”**  (arxiv 2024)  
​	    *Chong Xiang et al.* [Paper](https://arxiv.org/pdf/2405.15556)


2. **“AGENTPOISON: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases”**  (NIPS 2025)  
​	  *Zhaorun Chen et al.* [Paper](https://arxiv.org/pdf/2407.12784)


3. **“PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models”**  (arxiv 2024)  
​	  *Wei Zou et al.* [Paper](https://arxiv.org/pdf/2402.07867)


4. **“Poisoning Retrieval Corpora by Injecting Adversarial Passages”**  (arxiv 2023)  
​	  *Zexuan Zhong et al.* [Paper](https://arxiv.org/pdf/2310.19156)


5. **“AGENT-SAFETYBENCH: Evaluating the Safety of LLM Agents”**  (arxiv 2024)  
​	  *Zhexin Zhang et al.* [Paper](https://arxiv.org/pdf/2412.14470)


6. **“Agent Smith: A Single Image Can Jailbreak One Million Multimodal LLM Agents Exponentially Fast”**  (arxiv 2024)  
​	  *Xiangming Gu et al.* [Paper](https://arxiv.org/pdf/2402.08567)


7. **“Typos that Broke the RAG’s Back: Genetic Attack on RAG Pipeline by Simulating Documents in the Wild via Low-level Perturbations”**  (arxiv 2024)  
​	  *Sukmin Cho et al.* [Paper](https://arxiv.org/pdf/2404.13948)


8. **“ Commercial LLM Agents Are Already Vulnerable to Simple Yet Dangerous Attacks”**  (arxiv 2025)  
​	  *Ang Li et al.* [Paper](https://arxiv.org/pdf/2502.08586)


9. **“The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)”**  (arxiv 2024)  
​	  *Shenglai Zeng et al.* [Paper](https://arxiv.org/pdf/2402.16893)


10. **“ Is My Data in Your Retrieval Database? Membership Inference Attacks Against Retrieval Augmented Generation”**  (arxiv 2024)  
​	  *Maya Anderson et al.* [Paper](https://arxiv.org/pdf/2405.20446)


11. **“RAG-Thief: Scalable Extraction of Private Data from Retrieval-Augmented Generation Applications with Agent-based Attacks”**  (arxiv 2024)  
​	  *Changyue Jiang et al.* [Paper](https://arxiv.org/pdf/2411.14110)


12. **“Text Embeddings Reveal (Almost) As Much As Text”**  (arxiv 2023)  
​	  *John X Morris et al.* [Paper](https://arxiv.org/pdf/2310.06816)


13. **“Sentence Embedding Leaks More Information than You Expect: Generative Embedding Inversion Attack to Recover the Whole Sentence”**  (arxiv 2023)  
​	  *Haoran Li et al.* [Paper](https://arxiv.org/pdf/2305.03010)


14. **“Great, Now Write an Article About That: The Crescendo Multi-Turn LLM Jailbreak Attack”**  (arxiv 2024)  
​	  *Mark Russinovich et al.* [Paper](https://arxiv.org/pdf/2404.01833)


15. **“LLM Defenses Are Not Robust to Multi-Turn Human Jailbreaks Yet”**  (arxiv 2024)  
​	  *Nathaniel Li et al.* [Paper](https://arxiv.org/pdf/2408.15221)


16. **“LEVERAGING THE CONTEXT THROUGH MULTI-ROUND INTERACTIONS FOR JAILBREAKING ATTACKS”**  (arxiv 2024)  
​	  *Yixin Cheng et al.* [Paper](https://arxiv.org/pdf/2402.09177)


17. **“FRACTURED-SORRY-Bench: Framework for Revealing Attacks in Conversational Turns Undermining Refusal Efficacy and Defenses over SORRY-Bench (Automated Multi-shot Jailbreaks)”**  (arxiv 2024)  
​	  *Aman Priyanshu et al.* [Paper](https://arxiv.org/pdf/2408.16163)


18. **“Prompt Leakage effect and defense strategies for multi-turn LLM interactions”**  (arxiv 2024)  
​	  *Divyansh Agarwal et al.* [Paper](https://arxiv.org/pdf/2404.16251)


19. **“Securing Multi-turn Conversational Language Models From Distributed Backdoor Triggers”**  (arxiv 2024)  
​	  *Terry Tong et al.* [Paper](https://arxiv.org/pdf/2407.04151)

##### Defense

1. **“TrustRAG: Enhancing Robustness and Trustworthiness in RAG”**  (arxiv 2025)   
​	*Huichi Zhou et al.* [Paper](https://arxiv.org/pdf/2501.00879)


2. **“On the Vulnerability of Applying Retrieval-Augmented Generation within Knowledge-Intensive Application Domains”**  (arxiv 2024)  
​	*Xun Xian et al.* [Paper](https://arxiv.org/pdf/2409.17275)


3. **“Prompt Leakage effect and defense strategies for multi-turn LLM interactions”**  (arxiv 2024)  
​	*Divyansh Agarwal et al.* [Paper](https://arxiv.org/pdf/2404.16251)


4. **“AGENT-SAFETYBENCH: Evaluating the Safety of LLM Agents”**  (arxiv 2024)  
​	*Zhexin Zhang et al.* [Paper](https://arxiv.org/pdf/2412.14470)


5. **““Ghost of the past”: Identifying and Resolving Privacy Leakage of LLM’s Memory Through Proactive User Interaction”**  (arxiv 2024)  
​	*Shuning Zhang et al.* [Paper](https://arxiv.org/pdf/2410.14931)


6. **“ Is My Data in Your Retrieval Database? Membership Inference Attacks Against Retrieval Augmented Generation”**  (arxiv 2024)  
​	*Maya Anderson et al.* [Paper](https://arxiv.org/pdf/2405.20446)


7. **“Certifiably Robust RAG against Retrieval Corruption”**  (arxiv 2024)  
​	*Chong Xiang et al.* [Paper](https://arxiv.org/pdf/2405.15556)


8. **“Understanding Multi-Turn Toxic Behaviors in Open-Domain Chatbots”**  (RAID 2023)  
​	*Bocheng Chen et al.* [Paper](https://arxiv.org/pdf/2307.09579)

##### Evaluation

1. **“PoisonedRAG: Knowledge Corruption Attacks to Retrieval-Augmented Generation of Large Language Models”**  (arxiv 2024)  
​	*Wei Zou et al.* [Paper](https://arxiv.org/pdf/2402.07867)


2. **“AGENTPOISON: Red-teaming LLM Agents via Poisoning Memory or Knowledge Bases”**  (NIPS 2025)  
​	*Zhaorun Chen et al.* [Paper](https://arxiv.org/pdf/2407.12784)


3. **“The Good and The Bad: Exploring Privacy Issues in Retrieval-Augmented Generation (RAG)”**  (arxiv 2024)  
​	*Shenglai Zeng et al.* [Paper](https://arxiv.org/pdf/2402.16893)


4. **“RAG-Thief: Scalable Extraction of Private Data from Retrieval-Augmented Generation Applications with Agent-based Attacks”**  (arxiv 2024)  
​	*Changyue Jiang et al.* [Paper](https://arxiv.org/pdf/2411.14110)

#### Tool
##### Attack
1. **"An Evaluation Mechanism of LLM-based Agents on Manipulating APIs"** (EMNLP 2024)  
    *Liu et al.*  [Paper](https://aclanthology.org/2024.findings-emnlp.267/)

2. **"AI-and LLM-driven search tools: A paradigm shift in information access for education and research"** (Journal of Information Science 2024)  
    *Chowdhury et al.*  [Paper](https://journals.sagepub.com/doi/10.1177/01655515241284046)

3. **"Ufo: A UI-focused agent for Windows OS interaction"** (arxiv 2024)  
    *Zhang et al.*  [Paper](https://arxiv.org/abs/2402.07939)

4. **"Easytool: Enhancing LLM-based agents with concise tool instruction"** (arxiv 2024)  
    *Yuan et al.*  [Paper](https://arxiv.org/abs/2401.06201)

5. **"LLM with tools: A survey"** (arxiv 2024)  
    *Shen et al.*  [Paper](https://arxiv.org/abs/2409.18807)

6. **"ToolQA: A dataset for LLM question answering with external tools"** (NeurIPS 2023)  
    *Zhuang et al.*  [Paper](https://arxiv.org/abs/2306.13304)

7. **"Agent-SafetyBench: Evaluating the Safety of LLM Agents"** (arxiv 2024)  
    *Zhang et al.*  [Paper](https://arxiv.org/abs/2412.14470)

8. **"Security Attacks on LLM-based Code Completion Tools"** (arxiv 2024)  
    *Cheng et al.*  [Paper](https://arxiv.org/abs/2408.11006)

9. **"Imprompter: Tricking LLM Agents into Improper Tool Use"** (arxiv 2024)  
    *Fu et al.*  [Paper](https://arxiv.org/abs/2410.14923)

10. **"Misusing tools in large language models with visual adversarial examples"** (arxiv 2023)  
    *Fu et al.*  [Paper](https://arxiv.org/abs/2310.03185)

11. **"Breaking agents: Compromising autonomous LLM agents through malfunction amplification"** (arxiv 2024)  
    *Zhang et al.*  [Paper](https://arxiv.org/abs/2407.20859)

12. **"From Allies to Adversaries: Manipulating LLM Tool-Calling through Adversarial Injection"** (arxiv 2024)  
    *Wang et al.*  [Paper](https://arxiv.org/abs/2412.10198)

13. **"Mimicking the Familiar: Dynamic Command Generation for Information Theft Attacks in LLM Tool-Learning System"** (arxiv 2025)  
    *Jiang et al.*  [Paper](https://arxiv.org/abs/2502.11358)

14. **"Attacks on third-party APIs of large language models"** (arxiv 2024)  
    *Zhao et al.*  [Paper](https://arxiv.org/abs/2404.16891)

15. **"LLM agents can autonomously exploit one-day vulnerabilities"** (arxiv 2024)  
    *Fang et al.*  [Paper](https://arxiv.org/abs/2404.08144)

16. **"BadAgent: Inserting and activating backdoor attacks in LLM agents"** (arxiv 2024)  
    *Wang et al.*  [Paper](https://arxiv.org/abs/2406.03007)

17. **"Refusal-trained LLMs are easily jailbroken as browser agents"** (arxiv 2024)  
    *Kumar et al.*  [Paper](https://arxiv.org/abs/2410.13886)

##### Defense
##### Evaluation

### Extrinsic Trustworthiness
#### Agent-to-Agent
##### Attack
##### Defense
##### Evaluation

#### Agent-to-Environment
##### Physical Environment
##### Digital Environment

#### Agent-to-User

## 🔍 Comparison with Previous Surveys
| Survey             | Object      | Multi-Dimension | Modular | Technique      | MAS |
|:--------------------:|:-------------:|:-----------------:|:---------:|:-----------------:|:------:|
| [Liu et al.](https://arxiv.org/pdf/2308.05374)  | LLM         | ✅              | ❌       | Atk/Eval        | ❌    |
| [Huang et al.](https://mosis.eecs.utk.edu/publications/lichao2024trustllm.pdf)   | LLM         | ✅              | ❌       | Eval            | ❌    |
| [He et al.](https://arxiv.org/pdf/2407.19354)   | Agent       | ❌              | ❌       | Atk/Def         | ❌    |
| [Li et al.](https://arxiv.org/pdf/2401.05459)    | Agent       | ✅              | ❌       | Atk             | ❌    |
| [Wang et al.](https://arxiv.org/pdf/2409.14457)   | Agent       | ❌              | ❌       | Atk             | ❌    |
| [Deng et al.](https://dl.acm.org/doi/pdf/10.1145/3716628)   | Agent       | ❌              | ✅       | Atk/Def         | ✅    |
| [Gan et al.](https://arxiv.org/pdf/2411.09523?)    | Agent       | ✅              | ❌       | Atk/Def/Eval    | ❌    |
| **TrustAgent (Ours)**  | LLM + Agent | ✅              | ✅       | Atk/Def/Eval    | ✅    |

## 📥 Citation
If you find this survey useful for your research, please cite us:
```bibtex
@article{yu2025survey,
  title={A Survey on Trustworthy LLM Agents: Threats and Countermeasures},
  author={Yu, Miao and Meng, Fanci and Zhou, Xinyun and Wang, Shilong and Mao, Junyuan and Pang, Linsey and Chen, Tianlong and Wang, Kun and Li, Xinfeng and Zhang, Yongfeng and others},
  journal={arXiv preprint arXiv:2503.09648},
  year={2025}
}
```

## 📢 Contributing
We welcome contributions! Feel free to submit **issues** or **pull requests** to improve the repository.

## 📧 Contact
For any questions or discussions, please reach out to the authors:
- **Miao Yu**: fishthreewater@gmail.com
- **Xinfeng Li**: lxfmakeit@gmail.com
- **Qingsong Wen**: qingsongedu@gmail.com
