# **Risk Assessment Framework for Additive Manufacturing**
The risk assessment framework is a proactive approach leveraging cyber threat intelligence tools to identify, analyse, and assess potential threats in the additive manufacturing (AM) supply chain.

<img src="https://user-images.githubusercontent.com/47213565/227068264-6da3ba1f-2914-4395-99af-c37a5f900fb4.jpeg" alt="risk assessment flow" width="400">

# Features
The system identifies seven potential assets and 22 possible threats.




# Threat Impact
Threat impact is estimated based on the following threat characteristics:
* _Targetted precision_: Measures how accurately the threat can focus on specific victims or systems.
* _Area of Impact_: Assesses the extent of systems, networks, or regions affected by the threat.
* _Collateral Damage_: Evaluates unintended consequences affecting non-targeted entities.
* _Stealth_: Determines how well the threat evades detection by security measures.
* _Attack Repeatability_: Gauges how easily the threat can be executed multiple times.


# Threat Likelihood
The following attributes determine threat likelihood:
* trust in the data source 
* the severity of the threat
* threat frequency



# Evaluation
We evaluated the framework using the MITRE CVE dataset to test whether it can prioritize AM-relevant security risks. CVEs are mapped to the framework’s 7 assets and 22 threat types, and each case is scored using Impact (targeted precision, area of impact, collateral damage, stealth, repeatability) and Likelihood (source trust, severity, frequency). The resulting risk ranking highlights the most critical vulnerabilities for AM supply-chain settings and provides interpretable scores to support analyst triage.

## Related Publications

Below are selected publications related to SHIELD-CAN, cyber-physical security, additive manufacturing security, threat intelligence, and trusted AI systems. These give additional background and context around secure architectures, intrusion detection, self-healing, and risk assessment.

### Automotive, VANET & Cyber-Physical / ICS Security

- **[Secure and Anonymous Batch Authentication and Key Exchange Protocols for 6G Enabled VANETs](https://ieeexplore.ieee.org/document/10972137/)**  
  **Mahender Kumar** and Carsten Maple
  *IEEE Transactions on Intelligent Transportation Systems, 2025*

- **[ICSThreatQA: A Knowledge-Graph Enhanced Question Answering Model for Industrial Control System Threat Intelligence](https://www.sciencedirect.com/science/article/abs/pii/S0957417425037959)**  
  Ruby Rani, **Mahender Kumar**, Gregory Epiphaniou and Carsten Maple  
  *Expert Systems with Applications, 2025*.  

- **[Securing connected and autonomous vehicles: analysing attack methods, mitigation strategies, and the role of large language models](https://digital-library.theiet.org/doi/abs/10.1049/icp.2024.2534)**  
  **Mahender Kumar**, Ruby Rani, Gregory Epiphaniou, Carsten Maple
  *IET Conference Proceedings, 2024*.  

### Additive Manufacturing & Industrial Security

- **[Securing additive manufacturing with blockchain-based cryptographic anchoring and dual-lock integrity auditing](https://www.sciencedirect.com/science/article/pii/S0166361525001605)**  
  **Mahender Kumar**, Gregory Epiphaniou, Carsten Maple 
  *Computers in Industry, 173 (2025): 104395*.  

- **[Security of cyber-physical Additive Manufacturing supply chain: Survey, attack taxonomy and solutions](https://www.sciencedirect.com/science/article/pii/S0167404825002469)**  
  **Mahender Kumar**, Gregory Epiphaniou, Carsten Maple
  *Computers & Security, 2025: 104557*.  

- **[SPM-SeCTIS: Severity Pattern Matching for Secure Computable Threat Information Sharing in Intelligent Additive Manufacturing](id.elsevier.com/as/authorization.oauth2?platSite=SD%2Fscience&additionalPlatSites=GH%2Fgeneralhospital%2CMDY%2Fmendeley%2CSC%2Fscopus%2CRX%2Freaxys&scope=openid%20email%20profile%20els_auth_info%20els_idp_info%20els_idp_analytics_attrs%20urn%3Acom%3Aelsevier%3Aidp%3Apolicy%3Aproduct%3Ainst_assoc&response_type=code&redirect_uri=https%3A%2F%2Fwww.sciencedirect.com%2Fuser%2Fidentity%2Flanding&authType=SINGLE_SIGN_IN&prompt=none&client_id=SDFE-v4&state=retryCounter%3D0%26csrfToken%3De0f7da65-4312-406d-b8b1-5d0077a91e35%26idpPolicy%3Durn%253Acom%253Aelsevier%253Aidp%253Apolicy%253Aproduct%253Ainst_assoc%26returnUrl%3D%252Fscience%252Farticle%252Fpii%252FS2542660524002750%26prompt%3Dnone%26cid%3Darp-3211915e-c7b0-4f78-a79d-8fc3c10269d1)**
  **Mahender Kumar, Gregory Epiphaniou, Carsten Maple**  
  *Internet of Things, 28 (2024): 101334*.  

- **[Leveraging Semantic Relationships to Prioritise Indicators of Compromise in Additive Manufacturing Systems](https://link.springer.com/chapter/10.1007/978-3-031-41181-6_18)**  
  **Mahender Kumar**, Gregory Epiphaniou, Carsten Maple
  *International Conference on Applied Cryptography and Network Security, 2023*. 



### Healthcare, IoMT & Blockchain Systems

- **[A Provable Secure and Lightweight Smart Healthcare Cyber-Physical System With Public Verifiability](https://ieeexplore.ieee.org/document/9624169)**  
  **Mahender Kumar**, Satish Chand
  *IEEE Systems Journal, 16(4): 5501–5508, 2022*.  

- **[A Secure and Efficient Cloud-Centric Internet-of-Medical-Things-Enabled Smart Healthcare System With Public Verifiability](https://ieeexplore.ieee.org/document/9131770)**  
  **Mahender Kumar**, Satish Chand
  *IEEE Internet of Things Journal, 7(10): 10457–10465, 2020*.  

- **[MedHypChain: A patient-centered interoperability hyperledger-based medical healthcare system: Regulation in COVID-19 pandemic](https://www.sciencedirect.com/science/article/pii/S1084804521000023)**  
  **Mahender Kumar**, Satish Chand
  *Journal of Network and Computer Applications, 179:102975, 2021*.  

- **[A Lightweight Cloud-Assisted Identity-Based Anonymous Authentication and Key Agreement Protocol for Secure Wireless Body Area Network](https://ieeexplore.ieee.org/document/9099043)**  
  **Mahender Kumar**, Satish Chand
  *IEEE Systems Journal, 15(2): 1646–1657, 2021*.  


### Cryptography, Ontologies & Threat Intelligence Foundations

- **[Science and Technology Ontology: A Taxonomy of Emerging Topics](https://arxiv.org/abs/2305.04055)**  
  **Mahender Kumar**, Ruby Rani, Mirko Botarelli, Gregory Epiphaniou, Carsten Maple
  *arXiv preprint arXiv:2305.04055, 2023*.  

- **[Pairing for Greenhorn: Survey and Future Perspective](https://arxiv.org/abs/2108.12392)**  
  **Mahender Kumar**, Satish Chand
  arXiv preprint, 2021.  

For a complete and up-to-date list of publications, please refer to my full publication list or Google Scholar profile. [Google scholar](https://scholar.google.com/citations?hl=en&user=Ppmct6EAAAAJ&view_op=list_works&sortby=pubdate)

---

## Citing

If you use this framework, please cite the corresponding work:

```bash
@article{kumar2024comprehensive,
  title={Comprehensive threat analysis in additive manufacturing supply chain: a hybrid qualitative and quantitative risk assessment framework},
  author={Kumar, Mahender and Epiphaniou, Gregory and Maple, Carsten},
  journal={Production Engineering},
  volume={18},
  number={6},
  pages={955--973},
  year={2024},
  publisher={Springer}
}
```

## Contributor 
  - [Mahender Kumar](https://scholar.google.com/citations?user=Ppmct6EAAAAJ&hl=en)
  - [Gregory Epiphaniou](https://warwick.ac.uk/fac/sci/wmg/about/our-people/profile/?wmgid=2175)
  - [Carsten Maple](https://warwick.ac.uk/fac/sci/wmg/about/our-people/profile/?wmgid=1102)

