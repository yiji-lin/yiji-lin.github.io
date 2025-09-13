---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a third-year Master’s student in Cyberspace Institute of Advanced Technology at Guangzhou University, under the supervision of Professor Yuan Liu. Prior to that, I received my Bachelor’s degree in Computer Science and Technology from Jiaying University. My research interests lie in network security, adversarial defense, and intelligent security systems. To date, I have published two academic papers and hold multiple patents.

My research interest includes:
- Multi Agent / offline Reinforcement Learning
- Mechanism Disign (Game Thoery, Incentive Mechanism and Reputation System)
- Network Optimization and Graph Inference
- Cybersecurity application

# Educations
- *2023.09 - present*, Cyberspace Institute of Advanced Technology (CIAT), Guangzhou University, Guangzhou, China. 
- *2020.09 - 2022.06*, School of Computer Science, Jiaying University, Meizhou, China. 

# Papers
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">To be submitted to SCIS 2025 JCR:Q1 IF:7.6 CCF-A</div><img src='images/paper3.png' alt="sym" width="100%" height="500px"></div></div>
<div class='paper-box-text' markdown="1">

**No Answer Puzzle: Curious IP Entrapment Mechanism for Critical Event Protection via Advance Deception**

Chenlu Zhuansun$^&dagger;$, **Yiji Lin$^&dagger;$**(equal contribution), Yuan Liu$^\*$, Binxing Fang, Zhihong Tian$^\*$.

**Abstract**: With the rapid evolution of cyberattack techniques and the increasing level of automation, Major Protection Activities (MPA) are facing escalating and complex cybersecurity challenges. Modern attack behaviors are characterized by high speed, broad-spectrum reconnaissance, and strong stealth, which expose the limitations of traditional defense mechanisms—such as narrow response windows, delayed risk identification, and large system exposure surfaces. MPA demand high availability and openness of key systems, rendering conventional deception strategies insufficient for real-time and high-intensity protection requirements.
In this paper, we propose a preemptive deception defense mechanism based on the mechanism of "No Answer Puzzle". The mechanism deploys a multi-module, high-interaction deceptive system in a cloud environment, leveraging principles from motivational psychology to drive attacker to unknowingly engage in deep, sustained exploration of the deception system. Furthermore, we propose a behavioral modeling approach that quantifies attacker curiosity, thereby enhancing the prediction of potential threats.
The proposed system effectively reduces the exposure risk of real services without interfering with normal business operations. We conducted real-world experiments during the 2025 Asian Winter Games in Harbin, China, and the 137th Canton Fair. The results demonstrate that our method can identify high-risk attackers earlier than official monitoring systems, serving as a valuable and low-risk complement for proactive defense in MPA. This approach offers a novel and incremental strategy that complements existing defenses in constructing cognitively guided cyber defense frameworks.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review TCSS 2025 JCR:Q1 IF:4.9</div><img src='images/paper1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**HoneyCenter: A Honeypoint IP Mutation Strategy Optimization Based on Multi-Agent Reinforcement Learning**

Pengdeng Li$^+$, **Yiji Lin$^+$**(equal contribution), Chenlu Zhuansun, Binxing Fang, Yuan Liu$^\*$, Zhihong Tian$^\*$.

**Abstract**: APTs (Advanced Persistent Threats) on critical infrastructure such as smart grids and industrial control systems are growing increasingly severe. Although honeypoints, such as honeypots and honeybaits, have been widely adopted in cybersecurity, they still struggle to counter APTs as they can intelligently adjust strategies based on the current state of the system. Mutating the IP addresses of honeypoints has been recognized as an effective method for defending against various cyber attacks. However, in critical infrastructure, mutating the IP addresses requires careful design since improper strategy could lead to system instability or high costs such as service delay or interruption. Consequently, the defender needs to design a cost-effective honeypoint IP mutation strategy under the consideration of rational and smart APT attackers who can also adjust their attack strategies adaptively. To this end, first, we propose a dynamic two-player zero-sum game model \textit{HoneyCenter} to characterize the strategic interaction between the defender and the attacker, where, in each state, the defender determines which host the honeypoint IP address should transition to, while the attacker selects one of the hosts to attack. Then, we leverage the Minimax Q-learning algorithm to derive the optimal mutation strategy to maximize the defender's utility in capturing the attacker. Finally, through extensive experiments, we demonstrate that the proposed game model and the derived IP mutation strategy can significantly enhance the security of the critical infrastructure in a cost-effective manner.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Accepted by IEEE DSC 2025</div><img src='images/paper2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**When Reputation Meets Auction: A Dual Incentive Mechanism for Mitigating Clean Label Attack in Data Trading Markets**

Qingyuan Li, Chenlu Zhuansun,**Yiji Lin**(collaboration), Qingling Yang, Pengdeng Li, Yuan Liu$^\*$, Zhihong Tian.

**Abstract**: The data trading markets are increasingly vulnerable to clean-label attacks, where attackers provide poisoned data through manipulating the feature space of a target object instead of directly altering the target object labels such that trained models make undesirable decisions about the target object. Existing defenses whether high-precision poisoning filters or adversarial-training pipelines are locked in the same asymmetric arms race: attackers can refine perturbations at near zero marginal cost, while defenders must continually retrain, revalidate, and redeploy. Finally, escalating resource burden erodes market trust and resulting in the failure of the whole data markets. To overcome the challenges, we propose a dual incentive mechanism that integrates reputation systems with multi-attribute reverse auctions to mitigate the clean-label attack, where the attackers are less likely to be selected and their data price is also discounted. Specifically, we construct the reputation of data providers based on their clean-attack verification history, which is designed in a hard-to-build but easy-to-crush manner to capture long-term attacking behavior. Then, we formulate the optimal auction problem based on reputation. Furthermore, we design a multi-attribute reverse auction mechanism to effectively incentivize and penalize, thereby preventing clean label attack behaviors. Finally, theoretical analyses and simulations quantitatively demonstrate that the proposed dual incentive mechanism can create a safer data trading markets.
</div>
</div>


# Patents

- Yuan Liu; **Yiji Lin** et al. A Method for IP Reputation Assessment Integrating Macro- and Micro-Level TTP Behaviors (Translated from Chinese), 2025-08-27. submited.

- Zhihong Tian, Yuan Liu; **Yiji Lin** et al. Offline Reinforcement Learning-Based Optimization of Deception Defense Strategies(Translated from Chinese), Patent No.202511144907.X, 2025-08-15. Application acceptance.

- Yuan Liu; **Yiji Lin** et al. Graph Inference for Malicious Entity Detection Based on Subjective Logic Reputation Propagation (Translated from Chinese), 2025-08-01. Under examination.

- Yuan Liu; **Yiji Lin** et al. Early Detection of Cyberattack on Critical Activities (Translated from Chinese) , 2025-07-11. Under examination.



- Yuan Liu; Qingyuan Li; **Yiji Lin** et al. [An Incentive Method for Data Trading Markets Integrating Reputation and Auction Strategies (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=hEVkP-djbGxRrj3qPQD86WQUczkO1Tg7fYbDn8FwVi8R0_MSAflakis09BxAATj3uU0ntIpssLBsLh3xXkqDt_l7VHEbK2_omf1VsZT4rYsfT-MG3oYAvlIGr5z5rdu-hpHN2uWd2FEWWOUPJpIl8aT_de8uwWhIj3kH4gMrHYEHhi9ngKp8sw==&uniplatform=NZKPT&language=CHS), No.CN120410697A, 2025-08-01. Disclosed.



- Zhihong Tian; Yuan Liu; **Yiji Lin** et al.[Honeypot Address Mutation Decision Method, System, and Computer-Readable Storage Medium (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=hEVkP-djbGz1YK4DqxzC0NH_eQ_ZaO4KyZwfy5UgeTmikxBFqsbHqS7d_89WMRbYKwrFySKWtAPc3i6sb0XdIU1aLS41WohXl1kKhEcRZTdG888L23PE9T4tFocs2y9bV1jadxa6AiortgzE8w7uAMeX-DyCyphW_YWxnPhVpfCxRQ5WtwYVgQ==&uniplatform=NZKPT&language=CHS), No.CN120090879A, 2025-06-03. Disclosed.



- Yuan Liu; Zhihong Tian; **Yiji lin**; Qingyuan Li et al.[Network Defense Method, System, and Computer-Readable Storage Medium Based on Game-Theoretic Models (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=hEVkP-djbGz1YK4DqxzC0NH_eQ_ZaO4KyZwfy5UgeTmikxBFqsbHqS7d_89WMRbYKwrFySKWtAPc3i6sb0XdIU1aLS41WohXl1kKhEcRZTdG888L23PE9T4tFocs2y9bV1jadxa6AiortgzE8w7uAMeX-DyCyphW_YWxnPhVpfCxRQ5WtwYVgQ==&uniplatform=NZKPT&language=CHS), No.CN119011243A, 2024-11-22. Granted.

	
- Zhihong Tian; Binxing Fang; Yuan Liu; Longyu sun; **Yiji Lin** et al. [A Network Security Protection Method Based on Signaling Games (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=hEVkP-djbGz1YK4DqxzC0NH_eQ_ZaO4KyZwfy5UgeTmikxBFqsbHqUwBv-3pd9pKEEvCZGR5o-Zt2v1rl-TqyUC_eNVVTlcCmf7z1GSiYqQdLownzErH4H9v5xpjzyBmgl2eAMz_KQHMTx8dCWUoD3Bn4PzDyrsBFY9Tq5Cor_TDhLGCf1Maiw==&uniplatform=NZKPT&language=CHS), No.CN118764267A, 2024-10-11. Disclosed.

# Project
- **Reputation System in ShieldCube** (Core Developer)

   Designed and implemented the Reputation System in ShieldCube. ShieldCube led by Academician Binxing Fang, has been deployed in critical events (such as Canton Fair, Asian Games, Winter Asian Games, etc.) and leading enterprises(such as China Southern Power Grid, etc.)
  

# Software Copyright
- Guangzhou University, ShieldCube-Reputation System 2.0(Translated from Chinese), 2025SR1695922, Authorized. 

#  Honors and Awards
- *2024.10* The First Prize Scholarship in Guangzhou University.
- *2025.01* Topsec Academician Fang Binxing Class Scholarship. 

