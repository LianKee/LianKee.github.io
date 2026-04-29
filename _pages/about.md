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

I am currently leading the WuKong Code Security team at Tencent, Shenzhen. My current research focuses on the intersection of AI and code security, including LLM- and agent-driven vulnerability detection, systematic evaluation of AI/Agents, and secure code generation. I also have broad interests in program analysis, fuzzing, and mobile security.

I received my PhD degree from the [System Software and Security Laboratory](https://secsys.fudan.edu.cn/) at Fudan University in 2024, supervised by Professor [Min Yang](https://secsys.fudan.edu.cn/members/faculty/ym/), Professor [Yuan Zhang](https://yuanxzhang.github.io/), and Assistant Professor [Lei Zhang](https://zxlfd.github.io/).

Up to now, I have published several papers at top-tier conferences in cybersecurity and software engineering, including S&P, USENIX Security, and FSE. One of my papers received the **Distinguished Paper Award at ACM FSE 2024**. Furthermore, I have identified **150+ 0-day vulnerabilities**, with **70+ assigned CVE IDs**, and received acknowledgments from leading mobile manufacturers like Google, Huawei, vivo, Xiaomi, and open-source organizations such as Apache, Eclipse, RedHat, VMWare, and Oracle, etc.


# 🔥 News
- \[2026.04\] &nbsp;🎉 Our A.S.E paper accepted by **ACL Findings 2026**!
- \[2025.07\] &nbsp;🎉 We open-sourced [**A.S.E**](https://github.com/Tencent/AICGSecEval), the first repository-level benchmark for AI-generated code security evaluation!
- \[2025.02\] &nbsp;🎉 Joined **Tencent**.
- \[2025.01\] &nbsp;🎉 One paper accepted by **USENIX Security 2025**!
- \[2024.12\] &nbsp;🎉 Obtained my **Ph.D. degree** from Fudan University!
- \[2024.06\] &nbsp;🎉 Our paper received the **ACM SIGSOFT Distinguished Paper Award** at FSE 2024!
- \[2024.05\] &nbsp;🎉 One paper accepted by **FSE 2024**!
- \[2024.01\] &nbsp;🎉 One paper accepted by **S&P 2024**!

# 📝 Publications 

ACL'26 &nbsp; **A.S.E: A Repository-Level Benchmark for Evaluating Security in AI-Generated Code.**
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Keke Lian**, Bin Wang, Lei Zhang, Libo Chen, Junjie Wang, Ziming Zhao, Yujiu Yang et al.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *In Findings of the Association for Computational Linguistics (ACL Findings).* <span style="color:red">(CCF-A)</span>

ASE'25 &nbsp; **Exploring Static Taint Analysis in LLMs: A Dynamic Benchmarking Framework for Measurement and Enhancement.**
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Haoran Zhao, Lei Zhang, **Keke Lian** et al.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *In Proceedings of the International Conference on Automated Software Engineering (ASE).* <span style="color:red">(CCF-A)</span>

Security'25 &nbsp; **Careless Retention and Management: Understanding and Detecting Data Retention Denial-of-Service Vulnerabilities in Java Web Containers.**
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Keke Lian**, Lei Zhang, Haoran Zhao, Yinzhi Cao, Yongheng Liu, Fute Sun, Yuan Zhang, Min Yang.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *In Proceedings of the USENIX Security Symposium (USENIX Security).* <span style="color:red">(CCF-A)</span>

FSE'24 &nbsp; **Component Security Ten Years Later: An Empirical Study of Cross-Layer Threats in Real-World Mobile Applications.**
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; **Keke Lian**, Lei Zhang, Guangliang Yang, Shuo Mao, Xinjie Wang, Yuan Zhang, Min Yang.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *In Proceedings of the ACM International Conference on the Foundations of Software Engineering (FSE).* <span style="color:red">(CCF-A)</span>
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <span style="color:red">**★ ACM SIGSOFT Distinguished Paper Award**</span>

S&P'24 &nbsp; **Efficient Detection of Java Deserialization Gadget Chains via Bottom-up Gadget Search and Dataflow-aided Payload Construction.**
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Bofei Chen, Lei Zhang, Xinyou Huang, Yinzhi Cao, **Keke Lian**, Yuan Zhang, Min Yang.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *In Proceedings of the IEEE Symposium on Security and Privacy (S&P).* <span style="color:red">(CCF-A)</span>

CCS Workshop'23 &nbsp; **TrustedDomain Compromise Attack in App-in-app Ecosystems.**
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Zhibo Zhang, Zhangyue Zhang, **Keke Lian**, Guangliang Yang, Lei Zhang, Yuan Zhang, Min Yang.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *In Proceedings of the ACM Conference on Computer and Communications Security Workshop (CCS Workshop).*

S&P'22 &nbsp; **Exploit The Last Straw that Breaks Android System.**
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Lei Zhang, **Keke Lian (First Student Author)**, Haoyu Xiao, Zhibo Zhang, Peng Liu, Yuan Zhang, Min Yang, Haixin Duan.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *In Proceedings of the IEEE Symposium on Security and Privacy (S&P).* <span style="color:red">(CCF-A)</span>

S&P'20 &nbsp; **TextExerciser: Feedback-driven Text Input Exercising for Android Applications.**
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Yuyu He, Lei Zhang, Zhemin Yang, Yinzhi Cao, **Keke Lian**, Shuai Li, Wei Yang, Zhibo Zhang, Min Yang.
<br>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; *In Proceedings of the IEEE Symposium on Security and Privacy (S&P).* <span style="color:red">(CCF-A)</span>

# 🎖 Honors and Awards
- *2024* ACM SIGSOFT Distinguished Paper Award.
- *2023 & 2024* Outstanding Student Award of Fudan University.
- *2016* National Scholarship (Top 1%), Xiamen University.
- *2015 & 2016* Outstanding Student Award of Xiamen University.

# 📖 Educations
- *2018.09 - 2024.06*, Ph.D. in Cyberspace Security, Fudan University, Shanghai, China.
- *2014.09 - 2018.06*, B.E. in Software Engineering, Xiamen University, Xiamen, China.
