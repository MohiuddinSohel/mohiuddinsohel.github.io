---
layout: single
classes: wide
title: "Research and Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /resume
---
<br>
<div style="text-align: justify">
<b>Scalable-Hunter</b> [August 2020 - December, 2023], Distributed Hierarchical Event Monitoring System for Attack Diagnosis through Active 
Investigation of Attacker Activities. Designed and implemented distributed hierarchical event monitoring system to reduce attack
 detection time, communication overhead and resource usages. Designed and developed low-level log collecting agents for windows 
 system (ETW, event logs, syslog, NetFlow). Developed detectors to map low-level traces to MITRE ATT&CK technique and evidential 
 reasoing framework which performs passive reasoning and active investigation on reported observables.
</div>
  - Development Language/Tools: Python, Java, RabbitMQ, ElasticSearch, Virtualbox, Docker.<br>
  - [Paper1](https://link.springer.com/chapter/10.1007/978-3-031-37963-5_88), [Paper2](https://link.springer.com/chapter/10.1007/978-3-030-00305-0_11), [Paper3](https://dl.acm.org/doi/abs/10.1145/3289239.3289244)
  - [Github](https://github.com/MohiuddinSohel/Attack-on-Mining-Pool)
<br> 
<br> 

<div style="text-align: justify">
<b>CIS Critical Security Control (CSC) Assessment</b> [August 2018 - March 2024],  This project aims to determine what to measure (observables), 
how to measure (tools required), and metrics to evaluate the enforcement of CSCs. I used prompt engineering (Few-shot learning, 
Chain-of-Thought, Tree-of-Though) with LLM (ChatGPT, LLAMA) to extract that information from the CIS CSC guidelines. Later, The CIS reviewed and 
published our proposed approach as guidelines for the industry to assess CSCs. I also published my works at HOTSOS 2018 as a novel way to develop 
measures and metrics for CIS CSC assessment.
</div>
  - Development Language: Python, Java, NLP, Prompt Engineering, gpt-3.5-turbo, LangChain.<br>
  - [Paper1](https://dl.acm.org/doi/abs/10.1145/3314058.3317730)
<br> 
<br> 

<div style="text-align: justify">
<b>TTPDrill</b> [January 2017 - July 2018],  Automatic and Accurate Extraction of Threat Actions from Unstructured Text of 
CTI Sources and mapping of threat actions to  MITRE ATT&CK techniques. Extracted threat action from CTI reports using NLP and
 mapped the extracted threat actions to MITRE ATT&CK techniques and tactics using document similarity measures TF-IDF.
 </div>
  - Development Language: Java.<br>
  - [Paper1](https://dl.acm.org/doi/abs/10.1145/3134600.3134646)
  - [Github1](https://github.com/MohiuddinSohel/Subject-Verb-Object-Extractor), [Github2](https://github.com/MohiuddinSohel/Cyber-Attack-Analyzer)
<br> 
<br>

<div style="text-align: justify">
<b>
FAKE-CTI: Automated generation of plausible fake CTI report using retrofitted word vector</b> [August 2019 - December 2019],  The lack of enough text data containing attacker actions and sematic meaning difference of a cyber security term when used in non-cyber security context make the generation of word embedding for cyber security text is a tough task. However, the retrofitting technique makes the word embedding generation for cyber security texts plausible. The generated word embedding can be used to generate an automated plausible fake cyber threat intelligence report (CTI report) given some keywords for the corresponding CTI report. 
In this project, All threat actions for each MITRE attack framework technique are extracted using an ontology as proposed in TTPDrill, which consists of the attacker action, object (cyber object), and intent of the attacker. Later, Semantic relations like synonyms of each attacker action and the cyber object will be extracted from Wordnet or thesaurus using scripting. In the end, each synonym list will be automatically examined to discard the synonyms that are not used in cyber security based on our common knowledge about commonly used cyber security terms.
Using the extracted relationship and pre-trained word vector, a retrofitting technique will be used to generate a retrofitted word vector. After generating the refitted word embedding, A sentence can be generated based on the co-occurrence possibility of cyber security terms from the retrofitted word vector. The same task can be achieved in BERT using the Word Making model. After generating multiple sentences based on the provided keywords, we can consider a CTI report is generated.
 </div>
  - Development Language: Python, ML.<br>
  - [Github](https://github.com/MohiuddinSohel/Natural-Language-Processing)
<br> 
<br> 


<div style="text-align: justify">
<b>PKI-Middleware</b> [May 2014 - December 2015], a <a href="http://www.cryptsoft.com/pkcs11doc/v220/">PKCS#11</a> dynamic library developed 
for Windows, Linux, MAC and Android platform which complies <a href="https://en.wikipedia.org/wiki/Korea_Internet_%26_Security_Agency">KISA</a> 
and <a href="https://en.wikipedia.org/wiki/Federal_Information_Processing_Standards">FIPS</a> standards. Implemented Multithreading and Multiprocessing, Smart Card Profile Initialization, key operation (RSA key, Secret key (DES3, AES, MAC, SEED) and Random Number Generation), and sign operation (Signature generation and verification, Symmetric and Asymmetric key encryption and decryption, MAC Generation and verification).
</div>
  - Development Language: C++, JNI.<br>
<br> 


<div style="text-align: justify">
<b>Custom CSP</b> [January 2016 - April 2016], Cryptographic Service Provider is a MSDN Compatible library that 
implements the Microsoft's CryptoAPI <a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa380239">CAPI</a>. 
This CSP is used to enable NFC-based smart card authentication in Windows OS. CSP implements encoding and decoding functions, which MSDN application may use, for example, to implement strong user authentication or for secure email.
CSPs are independent modules that can be used by different applications. A user program calls CryptoAPI functions and these are redirected to CSP's functions. Since CSPs are responsible for implementing cryptographic algorithms and standards, applications do not need to be concerned about security details. Furthermore, one application can define which CSP it is going to use on its calls to CryptoAPI. In fact, all cryptographic activity is implemented in CSPs. CryptoAPI only works as a bridge between the application and the CSP.
</div>
  - Development Language: C++, Windows API, Cryptography, OpenSSL. <br>
<br> 

   
 <div style="text-align: justify">
 <b>PKI-Middleware Wrapper</b>, [January 2015 - March 2015] is a Java wrapper to 
 use <a href="http://www.cryptsoft.com/pkcs11doc/v220/">PKCS#11</a> middleware library in Java Application. It reduces maintenance  
 complexity of <it>JNI</it>, so that application developer  don't have to write core C code to handle function call 
 of <a href="http://www.cryptsoft.com/pkcs11doc/v220/">PKCS#11</a> library.
 </div>
  - Development Language: Java. <br>
<br> 

    
<div style="text-align: justify">
<b>CMS</b>,  [May 2015 - June 2015] (Cryptographic Message Syntax), a <a href="https://tools.ietf.org/html/rfc2315">PKCS#7</a> based toolkit 
developed to support <a href="https://en.wikipedia.org/wiki/Certificate_authority">CA System</a> during certificate Issue that supports 
all data types (Signed, Enveloped, SignedAndEnveloped, data) of <a href="https://tools.ietf.org/html/rfc2315">PKCS#7</a> and their operations.
</div>
  - Development Language: Java. 
  
  
  
  
        

    
