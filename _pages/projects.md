---
layout: page
title: Projects
permalink: /projects/
description: This nerd's playground.
---

#### At NYU

* **Non-Intrusive Malware Detection based on Hardware Root-of-Trust** <span style="float: right">New York, NY</span><br/>
*MoMA Lab, NYU* *<span style="float: right">Jan 2020 - Jan 2021</span>*
    * Proposed an out-of-the-device non-intrusive malware detection methodology utilizing high and low-level information collected by JTAG using Lauterbach PowerDebug PRO.
    * Demonstrated an accuracy increase to 99.75% by utilizing semantic and microarchitectural information with an SVM model for malware detection.
    * Utilized integrity verification of critical static Linux kernel data structures for rootkit detection and OCSVM trained on static analysis information of shared libraries for user-level rootkits, achieving an accuracy of 96.3%.

* **Platform Agnostic Remote Static Analysis Malware Detection for ICS** <span style="float: right">New York, NY</span><br/>
*MoMA Lab, NYU* *<span style="float: right">April 2019 - Dec 2019</span>*
    * Implemented external non-intrusive static analysis malware detection leveraging out-of-the-device virtual to physical address translation with JTAG.
    * Performed static analysis of process text section for extracting entropy values for a 32-byte sliding window, string, and syscall histograms, to be utilized as platform-agnostic features.
    * Achieved 98%, 95% malware detection accuracy for ARM and x86_64 architecture, respectively, with an SVM model.<br/>
    [[Code](https://github.com/momalab/amaya)] [[Poster](/assets/documents/talks/date_2021.pdf)]

* **Process-Aware Cyberattacks for Thermal Desalination Plants** <span style="float: right">Abu Dhabi, UAE</span><br/>
*Center for Cyber Security, NYUAD* *<span style="float: right">Dec 2017 - April 2019</span>*
    * Performed process-aware security assessment of desalination plants to identify attack entry points, categorize the attacks, estimate the corresponding financial loss, and mechanical damage.
    * Computed the resultant thermal shocks and pressure surges during water hammer in the piping system on sudden valve closure in MATLAB.
    * Quantified the detrimental effects of water hammering during such attacks in terms of Maximum induced von Mises stresses (340 MPa) and maximum displacement (19.94mm) with ANSYS.<br/>
    [[Code](https://github.com/momalab/msf-thermal-desalination-plant)] [[Paper](https://dl.acm.org/doi/abs/10.1145/3321705.3329805)] [[Presentation](/assets/documents/talks/asiaccs_2019.pdf)]

#### At UCLA

* **Phish Muzzle** <span style="float: right">Los Angeles, CA</span><br/>
*UCLA* *<span style="float: right">2016 - 2018</span>*
    * Proposed and developed a metadata based approach for defending against email spear phishing attack.
    * Extended Levenshtein Distance and MySQL queries for identifying suspicious emails.
    * Optimized the solution by reducing search space using additional MySQL query.<br/>
    [[Code](https://github.com/starlordphr/PhishArmor)] [[Thesis](https://escholarship.org/content/qt2ks9x26r/qt2ks9x26r.pdf)]

* **Automated NFV Deployment** <span style="float: right">Los Angeles, CA</span><br/>
*Wireless Networking Group (WiNG)* *<span style="float: right">April 2017 - Dec 2017</span>*
    * Developed a command line tool to automatically deploy OAI components using OpenStack.
    * Implemented automated scripts for OAI configuration based on user specified modular SLA files.
    * Introduced simple interactive functionality to deploy, delete and check status of the spawned VMs.<br/>
    [[Code](https://github.com/starlordphr/Automated_NFV_Deployment)]

* **ASCII Transliteration Format (ATF) Parser** <span style="float: right">Los Angeles, CA</span><br/>
*CDLI* *<span style="float: right">April 2017 - Dec 2017</span>*
    * Developed a parser to validate ATF texts using PLY in Python.
    * Enhanced and adopted the parser for online use by connecting PHP front with Python backend.
    * Implemented rules for automatically detecting structural and semantic defects in the texts.<br/>
    [[Code](https://github.com/starlordphr/ATF-Checker)]

* **Secure Code Analysis** <span style="float: right">Los Angeles, CA</span><br/>
*Software Evolution and Analysis Laboratory* *<span style="float: right">April 2017 - July 2017</span>*
    * Proposed a novel technique to detect violations of secure coding techniques using abstract symbol tree in Java.
    * Extended Google’s Error Prone to analyse the code for security vulnerabilities during compile time.
    * Detected vulnerabilities such as weak random number generation and return value ignored in open source projects.<br/>
    [[Code](https://github.com/starlordphr/Secure_Code_Analysis)]

* **Machine Learning for Cancer Treatment Prediction** <span style="float: right">Los Angeles, CA</span><br/>
*Center for Smart Health* *<span style="float: right">April 2017 - July 2017</span>*
    * Proposed a novel technique using clinical data for predicting best treatment option for cancer patients.
    * Implemented multiple machine learning techniques using TensorFlow and scikit library in Python.
    * Modified the algorithm to obtain an accuracy of upto 85%.<br/>
    [[Code](https://github.com/starlordphr/Cancer_Treatment_Prediction)] [[Presentation](/assets/documents/projects/cancer-prediction.pdf)]

* **Software Development for Personal Cloud File Sync** <span style="float: right">Los Angeles, CA</span><br/>
*Wireless Networking Group (WiNG)* *<span style="float: right">April 2017 - July 2017</span>*
    * Implemented automated personal cloud system using Python.
    * Improved the software to incorporate SSL protocol for secure transfer of data.
    * Achieved significantly less meta data transfer by using delta based approach.
    * Shifted from master based architecture to semi-master based approach, where data is transferred peer-to-peer and master is used only for meta data transfer.<br/>
    [[Code](https://github.com/cmuthapp/CS219_FileSync)] [[Report](/assets/documents/projects/cloud-sync.pdf)]

* **Breaking Location Stream Privacy** <span style="float: right">Los Angeles, CA</span><br/>
*Network Research Lab* *<span style="float: right">Sept 2016 - Dec 2016</span>*
    * Studied different neural network configurations for understanding its effect on location stream data.
    * Applied feed forward neural network for mobility pattern classification on location stream data.
    * Extended the solution to recurrent neural network for minimizing error to a maximum of 1.

#### Open Source Projects

* Lauterbach Python Library [[Code](https://github.com/starlordphr/lauterbach-python)]
* Development of Android Application for CDLI Lab [[Code](https://github.com/starlordphr/CDLI-Android-Application)]