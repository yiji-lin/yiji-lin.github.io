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

I am a third-year Master’s student in Cyberspace Institute of Advanced Technology (headed by [Academician Binxing Fang](https://wyy.gzhu.edu.cn/info/1036/1459.htm)) at Guangzhou University([3rd in China for Cybersecurity](https://www.shanghairanking.cn/rankings/bcsr/2025/0839)), advised by [Prof. Yuan Liu](https://www.blockchain-neu.com/). Prior to that, I received my Bachelor’s degree in Computer Science and Technology from Jiaying University. My research interests lie in network security, adversarial defense, and intelligent security systems. To date, I have completed three academic papers and hold several patents.

My research interest includes:
- Game Theory and Mechanism Design 
- Reputation Systems
- Multi Agent Reinforcement Learning
- Network Security

# Education Background
- *2023.09 - present*, Cyberspace Institute of Advanced Technology (CIAT), Guangzhou University, Guangzhou, China. 
- *2020.09 - 2022.06*, School of Computer Science, Jiaying University, Meizhou, China. 

# Publications
<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Under Review at SCIS 2025 JCR:Q1 IF:7.6 CCF-A</div>
        <div style="width:100%;height:500px; background:white;">
          <img src="images/paper3.png" alt="sym" 
              style="width:100%; height:100%; object-fit:contain; background:white;">
        </div>
      </div>
    </div>
<div class='paper-box-text' markdown="1">

**No Answer Puzzle: A Curiosity-Driven Attacker Model and Motivation Inference for APT in Cybersecurity of Major Events**

Chenlu Zhuansun$^&dagger;$, **Yiji Lin$^&dagger;$**(Co-First author), Yuan Liu$^\*$, Binxing Fang, Zhihong Tian$^\*$.

**Abstract**: Major events such as the Olympic Games pose unique cybersecurity challenges due to their high visibility, short duration, and complex system environments, making them prime targets for nation-state–level Advanced Persistent Threats (APTs). With sufficient preparation time, attackers often conduct early reconnaissance, among which large-scale password guessing against event-related systems is a recurrent preparatory behavior frequently observed before and during major events. Traditional defense mechanisms such as firewalls and honeypots can capture direct intrusion attempts but often overlook these pre-attack behaviors, missing valuable opportunities for early detection. 
To address this gap, we propose a No-Answer Puzzle scheme, a lightweight and non-loginable password-interaction system tailored for major-event scenarios to capture pre-attack preparations from attackers.
Based on motivational psychology, the persistent and covert behaviors of APT attacks are all driven by a strong curiosity towards the target  systems.
Therefore, by the captured interaction data, we define an attacker curiosity metric,
design a computational update mechanism, and develop a fuzzy-logic–based model for inferring attacker motivation. 
The system was successfully deployed during the cybersecurity missions of the 2025 9th Asian Winter Games (Harbin) and the 137th China Import and Export Fair (Canton Fair), and real-world results demonstrate that it effectively captures and identifies potential attackers at an early stage without affecting normal system operations, thereby contributing substantially to achieving zero-incident security for major events.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">In Revision at IEEE TCSS 2025 JCR:Q1 IF:4.9 CCF-C</div>        <div style="width:100%;height:500px; background:white;">
          <img src="images/paper1_full.png" alt="sym" 
              style="width:100%; height:100%; object-fit:contain; background:white;">
        </div></div></div>
<div class='paper-box-text' markdown="1">

**HoneyCenter: A Honeypoint IP Mutation Strategy Optimization Based on Multi-Agent Reinforcement Learning**

Pengdeng Li$^&dagger;$, **Yiji Lin$^&dagger;$**(Co-First author), Chenlu Zhuansun, Binxing Fang, Yuan Liu$^\*$, Zhihong Tian$^\*$.

**Abstract**: APTs (Advanced Persistent Threats) on critical infrastructure such as smart grids and industrial control systems are growing increasingly severe. Although honeypoints, such as honeypots and honeybaits, have been widely adopted in cybersecurity, they still struggle to counter APTs as they can intelligently adjust strategies based on the current state of the system. Mutating the IP addresses of honeypoints has been recognized as an effective method for defending against various cyber attacks. However, in critical infrastructure, mutating the IP addresses requires careful design since improper strategy could lead to system instability or high costs such as service delay or interruption. Consequently, the defender needs to design a cost-effective honeypoint IP mutation strategy under the consideration of rational and smart APT attackers who can also adjust their attack strategies adaptively. To this end, first, we propose a dynamic two-player zero-sum game model HoneyCenter to characterize the strategic interaction between the defender and the attacker, where, in each state, the defender determines which host the honeypoint IP address should transition to, while the attacker selects one of the hosts to attack. Then, we leverage the Minimax Q-learning algorithm to derive the optimal mutation strategy to maximize the defender's utility in capturing the attacker. Finally, through extensive experiments, we demonstrate that the proposed game model and the derived IP mutation strategy can significantly enhance the security of the critical infrastructure in a cost-effective manner.

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Accepted by IEEE DSC 2025</div>        <div style="width:100%;height:500px; background:white;">
          <img src="images/paper2.png" alt="sym" 
              style="width:100%; height:100%; object-fit:contain; background:white;">
        </div></div></div>
<div class='paper-box-text' markdown="1">

**When Reputation Meets Auction: A Dual Incentive Mechanism for Mitigating Clean Label Attack in Data Trading Markets**

Qingyuan Li$^&dagger;$, Chenlu Zhuansun$^&dagger;$,**Yiji Lin**, Qingling Yang, Pengdeng Li, Yuan Liu$^\*$, Zhihong Tian.

**Abstract**: The data trading markets are increasingly vulnerable to clean-label attacks, where attackers provide poisoned data through manipulating the feature space of a target object instead of directly altering the target object labels such that trained models make undesirable decisions about the target object. Existing defenses whether high-precision poisoning filters or adversarial-training pipelines are locked in the same asymmetric arms race: attackers can refine perturbations at near zero marginal cost, while defenders must continually retrain, revalidate, and redeploy. Finally, escalating resource burden erodes market trust and resulting in the failure of the whole data markets. To overcome the challenges, we propose a dual incentive mechanism that integrates reputation systems with multi-attribute reverse auctions to mitigate the clean-label attack, where the attackers are less likely to be selected and their data price is also discounted. Specifically, we construct the reputation of data providers based on their clean-attack verification history, which is designed in a hard-to-build but easy-to-crush manner to capture long-term attacking behavior. Then, we formulate the optimal auction problem based on reputation. Furthermore, we design a multi-attribute reverse auction mechanism to effectively incentivize and penalize, thereby preventing clean label attack behaviors. Finally, theoretical analyses and simulations quantitatively demonstrate that the proposed dual incentive mechanism can create a safer data trading markets.
</div>
</div>


# Patents

- Yuan Liu; **Yiji Lin** et al. A Method for IP Reputation Assessment Integrating Macro- and Micro-Level TTP Behaviors (Translated from Chinese), 2025-08-27. submited.

- Zhihong Tian, Yuan Liu; **Yiji Lin** et al. Offline Reinforcement Learning-Based Optimization of Deception Defense Strategies(Translated from Chinese), Patent No.202511144907.X, 2025-08-15. Application acceptance.

- Yuan Liu; **Yiji Lin** et al. [Graph Inference for Malicious Entity Detection Based on Subjective Logic Reputation Propagation (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=3ruWTMGvziUAFHZZa8RBX8W19v-BFNglIs7upxMr74FgEjWv6x2RCYm7gNAq_83oo4dxR-vS8TEqFs1z4riV0sO-Bz9IKZnfYsAyS1mntt7CqbVxa8u2tvYsnnyV2CfFiWc_X64jGkQnOJTaIQ0I33DR_b1nMpFQcJspohedlbvyPcxfVRRPrA==&uniplatform=NZKPT&language=CHS), 2025-09-05. Disclosed.

- Yuan Liu; **Yiji Lin** et al. [Early Detection of Cyberattack on Critical Activities (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=3ruWTMGvziUAFHZZa8RBX8W19v-BFNglIs7upxMr74FgEjWv6x2RCZKfJyuyQ8vKqNdmh_n_Az25WbTjdQiBuS__C62dXjO8SzQadTjvTp0EYH1OkWXIJG6B4bOVQLvpf4F7zCQ-t5bd3ySLaqSBQ7cu4riwV03XlUJC-2zwt48f7TRh4kiLxQ==&uniplatform=NZKPT&language=CHS), No.CN120785661A, 2025-10-14. Disclosed.


 
- Yuan Liu; Qingyuan Li; **Yiji Lin** et al. [An Incentive Method for Data Trading Markets Integrating Reputation and Auction Strategies (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=hEVkP-djbGxRrj3qPQD86WQUczkO1Tg7fYbDn8FwVi8R0_MSAflakis09BxAATj3uU0ntIpssLBsLh3xXkqDt_l7VHEbK2_omf1VsZT4rYsfT-MG3oYAvlIGr5z5rdu-hpHN2uWd2FEWWOUPJpIl8aT_de8uwWhIj3kH4gMrHYEHhi9ngKp8sw==&uniplatform=NZKPT&language=CHS), No.CN120410697A, 2025-08-01. Disclosed.



- Zhihong Tian; Yuan Liu; **Yiji Lin** et al.[Honeypot Address Mutation Decision Method, System, and Computer-Readable Storage Medium (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=hEVkP-djbGz1YK4DqxzC0NH_eQ_ZaO4KyZwfy5UgeTmikxBFqsbHqS7d_89WMRbYKwrFySKWtAPc3i6sb0XdIU1aLS41WohXl1kKhEcRZTdG888L23PE9T4tFocs2y9bV1jadxa6AiortgzE8w7uAMeX-DyCyphW_YWxnPhVpfCxRQ5WtwYVgQ==&uniplatform=NZKPT&language=CHS), No.CN120090879A, 2025-06-03. Disclosed.



- Yuan Liu; Zhihong Tian; **Yiji lin**; Qingyuan Li et al.[Network Defense Method, System, and Computer-Readable Storage Medium Based on Game-Theoretic Models (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=hEVkP-djbGz1YK4DqxzC0NH_eQ_ZaO4KyZwfy5UgeTmikxBFqsbHqS7d_89WMRbYKwrFySKWtAPc3i6sb0XdIU1aLS41WohXl1kKhEcRZTdG888L23PE9T4tFocs2y9bV1jadxa6AiortgzE8w7uAMeX-DyCyphW_YWxnPhVpfCxRQ5WtwYVgQ==&uniplatform=NZKPT&language=CHS), No.CN119011243A, 2024-11-22. Granted.

	
- Zhihong Tian; Binxing Fang; Yuan Liu; Longyu sun; **Yiji Lin** et al. [A Network Security Protection Method Based on Signaling Games (Translated from Chinese)](https://kns.cnki.net/kcms2/article/abstract?v=hEVkP-djbGz1YK4DqxzC0NH_eQ_ZaO4KyZwfy5UgeTmikxBFqsbHqUwBv-3pd9pKEEvCZGR5o-Zt2v1rl-TqyUC_eNVVTlcCmf7z1GSiYqQdLownzErH4H9v5xpjzyBmgl2eAMz_KQHMTx8dCWUoD3Bn4PzDyrsBFY9Tq5Cor_TDhLGCf1Maiw==&uniplatform=NZKPT&language=CHS), No.CN118764267A, 2024-10-11. Disclosed.

# Project
- **Reputation System in DunLiFang** (Core Developer)

   Designed and implemented the Reputation System in DunLiFang. DunLiFang led by Academician Binxing Fang, has been deployed in critical events (such as Canton Fair, Asian Games, Winter Asian Games, etc.) and leading enterprises(such as China Southern Power Grid, etc.)
  

# Software Copyright
- Guangzhou University, DunLiFang-Reputation System 2.0(Translated from Chinese), 2025SR1695922, Authorized. 

#  Awards
- *2025.10* China National Scholarship, By Ministry of Education of China. 
- *2024.10* The First Prize Scholarship in Guangzhou University.

#  Research Funding Supports
- National Key R&D Program of Smart Grid, Grant No.2025ZD0805904.
- Guangdong Basic and Applied Basic Research Foundation, Grant No.2025B1515020022.
- National Natural Science Foundation of China, Grant No. T252200258.
- National Key R&D Program of China, Grant No. 2022YFB3102700.
- National Natural Science Foundation of China, Grant No.62172085.
- National Natural Science Foundation of China, Grant No.U20B2046.
- Strategic Research and Consultation Project of the Chinese Academy of Engineering, Grant No.2024-XZ-07.