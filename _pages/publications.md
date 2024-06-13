---
layout: archive
classes: wide
permalink: /publications/
author_profile: true
redirect_from:
  - /publication
---
## Publications
<div style="text-align: justify">
<ol>
<li><b>Mohiuddin Ahmed</b>. (2024). Distributed Hierarchical Event Monitoring for Security Analytics. The University of North Carolina at Charlotte ProQuest Dissertations & Theses, 2024.31238031. <a href = "https://www.proquest.com/docview/3047710876/fulltextPDF/663A871EB9DB4724PQ?sourcetype=Dissertations%20&%20Theses">Link</a></li>
<li><b>Mohiuddin Ahmed</b>, Jinpeng Wei, Ehab Al-Shaer. (2024). Prompting LLM to Enforce and Validate CIS Critical Security Control. (ACM SACMAT 2024). <a href = "/../presentation/SACMAT_2024_presentation.pptx">Presentation Slides at ACM SACMAT 2024.</a></li>
<li><b>Mohiuddin Ahmed</b>, Jinpeng Wei, Ehab Al-Shaer. (2023). SCAHunter: Scalable Threat Hunting through Decentralized Hierarchical Monitoring Agent Architecture. (Computing 2023). <a href = "https://doi.org/10.1007/978-3-031-37963-5_88">Link</a></li>
<li>Sharun Akter Khushbu, Nasheen Nur, <b>Mohiuddin Ahmed</b>, Nashtarin Nur. (2023). A Comparison of Traditional to Advanced Linguistic Models to Analyze Sentiment in Bangla Texts. (EMNLP 2023 workshop BLP). <a href = "https://aclanthology.org/2023.banglalp-1.38/">Link</a></li>
<li><b>Mohiuddin Ahmed</b>, Ehab Al-Shaer. (2019). Measures and metrics for the enforcement of critical security controls: a case study of boundary defense. (Poster presentation in HOTSOS 2019). <a href = "https://dl.acm.org/doi/abs/10.1145/3314058.3317730">Link</a></li>
<li><b>Mohiuddin Ahmed</b>, Jinpeng Wei, Yongge Wang and Ehab Al-Shaer. (2018). A Poisoning Attack Against Cryptocurrency Mining Pools. (ESORICS CBT 2018). <a href = "https://link.springer.com/chapter/10.1007/978-3-030-00305-0_11">Link</a></li>
<li>Ghaith Husari, Ehab Al-Shaer, <b>Mohiuddin Ahmed</b>, Bill Chu, and Xi Niu. (2017). TTPDrill: Automatic and Accurate Extraction of Threat Actions from Unstructured Text of CTI Sources. (ACSAC 2017). <a href = "https://dl.acm.org/doi/abs/10.1145/3134600.3134646">Link</a></li>
<li>Rawan Al-Shaer, <b>Mohiuddin Ahmed</b>, Ehab Al-Shaer. (2018). Statistical Learning of APT TTP Chains from MITRE ATT&CK. (Poster presentation in ACSAC 2018).</li>
<li>Mohammed Noraden Alsaleh, Jinpeng Wei, Ehab Al-Shaer and <b>Mohiuddin Ahmed</b>.  (2018). gExtractor: Towards Automated Extraction of Malware Deception Parameters. (SSPREW-8, 2018). <a href = "https://dl.acm.org/doi/abs/10.1145/3289239.3289244">Link</a></li>
</ol>
</div>

## Dissertation Thesis
<br>
[<center>Distributed Hierarchical Event Monitoring for Security Analytics</center>](https://www.proquest.com/docview/3047710876/fulltextPDF/663A871EB9DB4724PQ?sourcetype=Dissertations%20&%20Theses)<br>
<div style="text-align: justify">
In recent years, there has been an increase in attacks, including advanced persistent threats (APTs), and the techniques used by the attacker in these attacks have reached unprecedented sophistication. Threat hunters use various monitoring tools to monitor and collect all these attack actions (which blend in with benign user activities) for cyber threat hunting—the end devices store monitored activities as generated logs/events. Moreover, Organizations like NIST and CIS provide guidelines (CSC) to enforce cyber security and defend against those attacks.

Although the end hosts and networking devices can record all benign user and adversary actions, it is infeasible to monitor everything. In existing approaches, high memory usage and communication overhead to transfer events to the central server create scalability issues on the monitored network. Single event matching on the end-host devices approach to detect attacks generates false alerts, causing the alert fatigue problem. This dissertation presents a distributed hierarchical monitoring agent architecture to overcome those limitations of existing tools and research works.

Additionally, there are no well-defined automated measures and metrics to validate the enforcement of CSC. Manually analyzing and developing measures and metrics to monitor and implementing those monitoring mechanisms are resource-intensive tasks and massively dependent on the security analyst's expertise and knowledge. To tackle those problems, we use LLM as a knowledge base and reasoner to extract measures, metrics, and monitoring mechanism implementation steps from CSC descriptions to reduce the dependency on security analysts with the help of few-shot learning with chain-of-thought prompting. This dissertation presents CSC enforcement assessment with the help of our distributed hierarchical monitoring agent architecture and prompt engineering.
</div>