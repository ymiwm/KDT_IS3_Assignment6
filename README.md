# K-Digital Training Information Security 3rd Assignment 6

### Overview

**Subject: Diamond Model 작성 실습**

**The Dimond Model of Intrusion Analysis**

1. Source Link<a href="#1-source-link"><sup>[1]</sup></a>

2. Diamond Model<a href="#2-dimond-model"><sup>[2]</sup></a>

3. Adversary<a href="#3-adversary"><sup>[3]</sup></a>

4. Capability<a href="#4-capability"><sup>[4]</sup></a>

5. Infrastructure<a href="#5-infrastructure"><sup>[5]</sup></a>

6. Victim<a href="#6-victim"><sup>[6]</sup></a>

7. Meta-Features<a href="#7-meta-features"><sup>[7]</sup></a>

8. WIP<a href="#8-wip"><sup>[8]</sup></a>

9. Review<a href="#9-review"><sup>[9]</sup></a>

10. Ref Links<a href="#10-ref-links"><sup>[10]</sup></a>

---

#### 1. Source Link

[Link - KDT_IS3_Assignment6](https://github.com/ymiwm/KDT_IS3_Assignment6)  
[Link - Report of Operation Golden Axe](http://www.issuemakerslab.com/research3/)

---

#### 2. Diamond Model

![Diamond Model](/Diamond%20Model.png)

---

#### 3. Adversary


1. Activity Group Name: Andariel
2. Nationality: North Korea


---

#### 4. Capability

**Techniques**

1. Watering Hole
2. Malware
3. Bypass Penetration
4. Zero-day Vulnerability 


---

#### 5. Infrastructure

This contents are composed with **Guessed Infrastructures**.  
There is no information about ***Infrastructure*** in the report.  
So replace it with ***MITRE ATT&CK Framework***.

1. gh0st RAT<a href="https://attack.mitre.org/software/S0032/"><sup>[1]</sup></a>

2. Rifdoor<a href="https://attack.mitre.org/software/S0433/"><sup>[2]</sup></a>


---

#### 6. Victim

![Victim-URL](/Victim-URL.png)

**Target**  

1. The Korea Foreign Affairs Association
2. Aerospace Research Institute
3. North Korean Strategic Information Service Center
4. A group of North Korean defectors preparing for reunification
5. Unification Education Council
6. National Union of Public Research Workers
7. The National Council of Councils
8. Woori Bank Branch
9. Sindaeam Hospital
10. Hunjeonghoe of South Korea (former lawmaker)

**Vulnerabilities**

1. Active X (Infection vector)
    - Electronic payments
    - Authentication
    - Encryption
    - Reporting
    - Webmail
    - Groupware
2. Relatively easy association compliant

---

#### 7. Meta-Features

1. Timestamp
    - Jun 2016 to May 2017  

2. Phase
    - **Watering hole** attack was conducted to distribute **Malware** to visitors through.
    - Attack against a **relatively easy association compliant**, and conducted a **bypass penetration**.

3. Result
    - Success (Confidentiality Compromised)

4. Direction
    - Adversary <-> Victim (Bidirectional)

5. Methodology
    - Watering Hole

6. Resources
    - Target system (Active-X)
    - gh0stRat
    - Rifdoor

7. Social-political
    - Hostile country (South Korea <-> North Korea)

8. Technology
    - Malware
    - Bypass penetration


---

#### 8. WIP

1. 단일 Diamond Model 구성은 모양새를 갖추었으나, Activity Attack Graph를 이용한 관계도를 만들기 위해선 복수의 Diamond Model이 필요할 것으로 보임.

2. Andariel을 포함하여 관련성이 높다고 생각되는 Lazarus, Kimsuky 등 다양한 Adversary에 대한 Model을 만들어 Activity Group Steps를 적용해보기.

**Activity Attack Graph**
![Activity Attack Graph](/Activity%20Attack%20Graph.png)

---

#### 9. Review

---

#### 10. _Ref Links_
- Report of Andariel Operation 'Golden Axe'
http://www.issuemakerslab.com/research3/
- MITRE ATT&CK Framework - Andariel(Group)
https://attack.mitre.org/groups/G0138/
- The Diamond Model of Intrusion Analysis
https://www.linkedin.com/pulse/diamond-model-intrusion-analysis-eva-johnson/
- Diamond Model in Cyber Threat Intelligence
https://warnerchad.medium.com/diamond-model-for-cti-5aba5ba5585
---

[_Go to top_ ↑](#k-digital-training-information-security-3rd-assignment-6)
