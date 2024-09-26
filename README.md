# AI empowered incident reporting and learning system 

This site provides the source code of the prototype 'AI-enabled Incident Reporting and Learning System'. This system is being developed by the 'AI for Patient Safety' team led by Dr. Zoie Wong.
There are three phases of reporting, namely: reporting the incident, structuring free-text report, and recommending learning resources. Through the backend BERT model, the system can automatically capture information from unstructured, free-text incident reports and render it as structured data (Japanese text only). 

## What's the purpose of this system?
The aim of our team is to facilitate learning from past patient safety incidents and ultimately improve patient safety.

## What can this system do?
We have been investigating how to automatically capture information from unstructured, free-text incident reports and present it as structured data.
Once an incident report has been 'structured', it can be analyzed automatically with advanced clinical AI, drawing from vast medical databases to provide the user with similar past incidents and relevant learning resources.

## Languages
System interface - Japanese and English. Incident text processing - Japanese
![image](https://github.com/user-attachments/assets/64357423-4bcd-4661-b429-c1d01268307c)
![image](https://github.com/user-attachments/assets/a20cb2aa-4485-46fe-9404-efa82af463c6)


## How does it work?
We use natural language processing to automatically extract named entities, i.e., the 'things' of interest, from incident reports. By extracting and analyzing the named entities, we can infer what type of incident occurred and other relevant details. This allows underlying reasons for medical incidents to be explored automatically on a large scale.

Access system through here (required credentials)- https://www.aiforpatientsafety.com/

## References
Wong ZSY, Waters N, Liu J, Ushiro S. A large dataset of annotated incident reports on medication errors. Sci Data. 2024;11(1):260.

Zhang HK, Sasano R, Takeda K, Wong ZSY, editors. Development of a Medical Incident Report Corpus with Intention and Factuality Annotation. LERC 2020; 2020; Marseille.
