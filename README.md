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

# cite
_Kumar, Mahender_, Gregory Epiphaniou, and Carsten Maple. "Comprehensive Threat Analysis in Additive Manufacturing Supply Chain: A Hybrid Qualitative and Quantitative Risk Assessment Framework." Production Engineering (2024): 1-19.

# Project Lead
Mahender Kumar(@mahend72)
