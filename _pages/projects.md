---
layout: page
title: Projects
permalink: /projects/
description: A nerd's playground.
nav: true
---

#### At Facebook
* **Improving Disassembly Database Support in ThreatData**<br/>
*Facebook, Menlo Park, CA*
    * Created EntDisassemblerDatabase, a schema to represent disassembly databases and associated it with existing ThreatData graph.
    * Modified ThreatData UI to upload disassembly databases using FB upload service and preview related intel source reports.
    * Designed and implemented TDSync, an IDA plugin to enable annotation sync between local instances and Disassembly UI.
    * Reduced redundant data in a GraphQL mutation by utilizing diffs between consecutive annotation states.

#### At NYU

* **Automated Vulnerability Localization and Non-Intrusive Hotpatching in ICS**<br/>
*MoMA Lab, NYU*
    * Developed ICSPatch to localize vulnerabilities in control logic using Data Dependence Graph, non-intrusively hotpatch it using an LKM patcher and tested on a synthetic dataset with 24 vulnerable control applications.
    * Successfully localized and hotpatched OOB write/read, OS command injection, and improper input validation, incurring latency of 222ms and 332ms for patch generation and deployment, respectively.<br/>
    [[Code](https://github.com/momalab/ICSPatch)] [[Paper](https://arxiv.org/abs/2212.04229)]

* **Non-Intrusive Malware Detection based on Hardware Root-of-Trust**<br/>
*MoMA Lab, NYU*
    * Proposed an out-of-the-device non-intrusive malware detection methodology utilizing high and low-level information collected by JTAG using Lauterbach PowerDebug PRO.
    * Demonstrated an accuracy increase to 99.75% by utilizing semantic and microarchitectural information with an SVM model for malware detection.
    * Utilized integrity verification of critical static Linux kernel data structures for rootkit detection and OCSVM trained on static analysis information of shared libraries for user-level rootkits, achieving an accuracy of 96.3%.<br/>
    [[Code](https://github.com/momalab/orris)] [[Paper](https://ieeexplore.ieee.org/document/9581272)] [[Presentation](/assets/documents/talks/EuroS&P_2021.pdf)] [[Video](https://www.youtube.com/watch?v=G7pNAAnnJr0)]

* **Platform Agnostic Remote Static Analysis Malware Detection for ICS**<br/>
*MoMA Lab, NYU*
    * Implemented external non-intrusive static analysis malware detection leveraging out-of-the-device virtual to physical address translation with JTAG.
    * Performed static analysis of process text section for extracting entropy values for a 32-byte sliding window, string, and syscall histograms, to be utilized as platform-agnostic features.
    * Achieved 98%, 95% malware detection accuracy for ARM and x86_64 architecture, respectively, with an SVM model.<br/>
    [[Code](https://github.com/momalab/amaya)] [[Paper](https://ieeexplore.ieee.org/document/9474121)] [[Poster](/assets/documents/talks/date_2021.pdf)] [[Video](https://www.youtube.com/watch?v=yZPgoWMN4AA)]

* **Process-Aware Cyberattacks for Thermal Desalination Plants**<br/>
*Center for Cyber Security, NYUAD*
    * Performed process-aware security assessment of desalination plants to identify attack entry points, categorize the attacks, estimate the corresponding financial loss, and mechanical damage.
    * Computed the resultant thermal shocks and pressure surges during water hammer in the piping system on sudden valve closure in MATLAB.
    * Quantified the detrimental effects of water hammering during such attacks in terms of Maximum induced von Mises stresses (340 MPa) and maximum displacement (19.94mm) with ANSYS.<br/>
    [[Code](https://github.com/momalab/msf-thermal-desalination-plant)] [[Paper](https://dl.acm.org/doi/abs/10.1145/3321705.3329805)] [[Presentation](/assets/documents/talks/asiaccs_2019.pdf)]

#### At UCLA

* **Phish Muzzle**<br/>
*UCLA*
    * Proposed and developed a metadata based approach for defending against email spear phishing attack.
    * Extended Levenshtein Distance and MySQL queries for identifying suspicious emails.
    * Optimized the solution by reducing search space using additional MySQL query.<br/>
    [[Code](https://github.com/starlordphr/PhishArmor)] [[Thesis](https://escholarship.org/content/qt2ks9x26r/qt2ks9x26r.pdf)]

* **Automated NFV Deployment**<br/>
*Wireless Networking Group (WiNG)*
    * Developed a command line tool to automatically deploy OAI components using OpenStack.
    * Implemented automated scripts for OAI configuration based on user specified modular SLA files.
    * Introduced simple interactive functionality to deploy, delete and check status of the spawned VMs.<br/>
    [[Code](https://github.com/starlordphr/Automated_NFV_Deployment)]

* **ASCII Transliteration Format (ATF) Parser**<br/>
*CDLI*
    * Developed a parser to validate ATF texts using PLY in Python.
    * Enhanced and adopted the parser for online use by connecting PHP front with Python backend.
    * Implemented rules for automatically detecting structural and semantic defects in the texts.<br/>
    [[Code](https://github.com/starlordphr/ATF-Checker)]

* **Secure Code Analysis**<br/>
*Software Evolution and Analysis Laboratory*
    * Proposed a novel technique to detect violations of secure coding techniques using abstract symbol tree in Java.
    * Extended Google’s Error Prone to analyse the code for security vulnerabilities during compile time.
    * Detected vulnerabilities such as weak random number generation and return value ignored in open source projects.<br/>
    [[Code](https://github.com/starlordphr/Secure_Code_Analysis)]

* **Machine Learning for Cancer Treatment Prediction**<br/>
*Center for Smart Health*
    * Proposed a novel technique using clinical data for predicting best treatment option for cancer patients.
    * Implemented multiple machine learning techniques using TensorFlow and scikit library in Python.
    * Modified the algorithm to obtain an accuracy of upto 85%.<br/>
    [[Code](https://github.com/starlordphr/Cancer_Treatment_Prediction)] [[Presentation](/assets/documents/projects/cancer-prediction.pdf)]

* **Software Development for Personal Cloud File Sync**<br/>
*Wireless Networking Group (WiNG)*
    * Implemented automated personal cloud system using Python.
    * Improved the software to incorporate SSL protocol for secure transfer of data.
    * Achieved significantly less meta data transfer by using delta based approach.
    * Shifted from master based architecture to semi-master based approach, where data is transferred peer-to-peer and master is used only for meta data transfer.<br/>
    [[Code](https://github.com/cmuthapp/CS219_FileSync)] [[Report](/assets/documents/projects/cloud-sync.pdf)]

* **Breaking Location Stream Privacy**<br/>
*Network Research Lab*
    * Studied different neural network configurations for understanding its effect on location stream data.
    * Applied feed forward neural network for mobility pattern classification on location stream data.
    * Extended the solution to recurrent neural network for minimizing error to a maximum of 1.

#### Open Source Projects

* Lauterbach Python Library [[Code](https://github.com/starlordphr/lauterbach-python)]
* Development of Android Application for CDLI Lab [[Code](https://github.com/starlordphr/CDLI-Android-Application)]
