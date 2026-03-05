---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<!-- {% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %} -->

<style>
  .badge {
    font-weight: 600;
    margin-bottom: 5px;
  }
</style>

<style>
  .logo-row {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 1.5rem;
    margin-top: 2rem; 
  }
  .logo-row img {
    height: 100px;
    width: auto;
    /* 
       border-radius: 6px;
       box-shadow: 0 0 6px rgba(0,0,0,.15); */
  }
</style>

<style>
  .site-footer {
    text-align: center;
    font-size: 0.85em;
    color: rgb(128, 128, 128);
    margin: 2rem 0 1rem; 
  }
  .site-footer a {
    color: inherit;
    text-decoration: underline;
  }
</style>

<style>
.project {
  margin-bottom: 2em;
}

.project-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin-bottom: 0.5em;
}

.project-title {
  font-weight: bold;
  font-size: 1.2em;
}

.project-role {
  background-color: #d4edda; /* 浅绿色背景 */
  color: #155724;
  padding: 0.2em 0.6em;
  border-radius: 4px;
  margin-left: 1em;
  white-space: nowrap;
  font-size: 0.9em;
}

.project-time {
  background-color: #e2e3e5; /* 浅灰色背景 */
  color: #383d41;
  padding: 0.2em 0.6em;
  border-radius: 4px;
  font-size: 0.9em;
  white-space: nowrap;
}
</style>

<span class='anchor' id='about'></span>

Hello everyone, my name is Haozhe Lu (陆皓喆). I am currently an undergraduate student in the College of Cryptology and Cyber Science(密码与网络空间安全学院), Nankai University(南开大学), majoring in Cyber Security and minoring in Finance. Please feel free to contact me through **15058298819@163.com** if you are interested in my projects.

In September 2026, I will begin my graduate studies at Peking University(北京大学), pursuing a Master's degree in Network and Information Security(网络与信息安全). 

My research interests lie in:

- **LLM Security:**&nbsp;RAG Attacks and Defenses, Poisoning Attacks and so on.

- **LLM for Security:**&nbsp;LLM for Vulnerability Mining, LLM for Penetration Testing and so on.

I have organized the [Course Note](https://github.com/Luhaozhhhhe/NKU_Course_Note)，[Lab Report](https://github.com/Luhaozhhhhe/NKU_Lab_Report) for the Information Security major courses at Nankai University, as well as the [Final Exam](https://github.com/Luhaozhhhhe/NKU_Final_Exam) for theoretical courses. So far, these resources have assisted over **1,000** students and accumulated more than **200,000** views.


<span class='anchor' id='publications'></span>

# 📝 Publications 

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">USENIX Security 2026在投</div>
      <img src='images/projects/GHOSTCITE.png' alt="RAGForensics" width="100%">
    </div>
  </div>

  <div class='paper-box-text'>
    <p>
      <a href="https://sec26cycle2.usenix.hotcrp.com/" target="_blank" rel="noopener"><strong>GHOSTCITE: A Large-Scale Analysis of Citation Validity in the Age of Large Language Models</strong></a>
    </p>
    <p>
      <span class="paper-role-badge">Co-author</span>
      <span class="paper-time-badge">2026.01 – 2026.02</span>
    </p>
<ul style="margin-top: 0.5em; padding-left: 1.5em;">
    <li>Develop <strong>GHOSTCITE</strong>, an open-source framework that verifies citations at scale, providing a replicable implementation example for venues, publishers, and future work.</li>
    <li>We evaluate <strong>13</strong> LLMs across <strong>40</strong> domains on <strong>375,440</strong> citations, showing hallucination rates of <strong>14.23–94.93%</strong> with significant research domain sensitivity.</li>
    <li>We analyze 2.2M citations from <strong>56,381</strong> papers (2020–2025), finding <strong>604/56,381 (1.07%)</strong> with invalid citations, an <strong>80.9%</strong> increase in 2025, and evidence of propagation (up to 16 repeated errors).</li>
</ul>
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">WWW 2025</div>
      <img src='images/projects/RAG.png' alt="RAGForensics" width="100%">
    </div>
  </div>

  <div class='paper-box-text'>
    <p>
      <a href="https://arxiv.org/abs/2504.21668" target="_blank" rel="noopener"><strong>Traceback of Poisoning Attacks to Retrieval-Augmented Generation</strong></a>
    </p>
    <p>
      <span class="paper-role-badge">Team Member</span>
      <span class="paper-time-badge">2024.09 – 2024.12</span>
    </p>
<ul style="margin-top: 0.5em; padding-left: 1.5em;">
    <li>This paper was completed during an internship in the research group, focusing on the research of <strong>retrieval-augmented generation (RAG) system poisoning</strong> attacks, defenses, and traceability.</li>
    <li>Assisted in designing the core <strong>RAGForensics</strong> system, which employs an <strong>iterative process</strong> to remove contaminated text and ensures that the final retrieved text remains benign.</li>
    <li>Designed experiments using datasets such as NQ, MS-MARCO and HotpotQA, established evaluation metrics, and tested the traceability effectiveness of the RAGForensics system.</li>
</ul>
  </div>
</div>







<span class='anchor' id='scholarships'></span>

# 💰 Scholarships

- 2025.11:&nbsp;💰Enlai Zhou Scholarship(￥10000, Top 10), Nankai University(**周恩来奖学金初评全校第二，南开大学最高荣誉**)；

- 2025.11:&nbsp;💰[BYD Scholarship](https://xgb.nankai.edu.cn/Uploads/file/20251107/1762486848163611.pdf)(￥10000, Top 0.6%), Nankai University(**比亚迪奖学金**)；

- 2025.09:&nbsp;💰[National Scholarship](http://www.moe.gov.cn/srcsite/A05/s7505/202512/t20251225_1424488.html)(￥10000, Top 0.6%), China(**国家奖学金**, 全学院综合排名第一)；

- 2025.04:&nbsp;💰First Prize of [Yun'an Scholarship](https://mp.weixin.qq.com/s/CTF8igqmYcOteFqi6dZI1g)(￥5000, Top 1.6%), Nankai University(南开大学“云安密码创新奖学金”一等奖)；

- 2024.09:&nbsp;💰[National Scholarship](https://xgb.nankai.edu.cn/Uploads/file/20241115/1731659467744499.pdf)(￥10000, Top 0.6%), China(**国家奖学金**, 全学院综合排名第一)；

- 2023.10:&nbsp;💰Academic Excellence Scholarship(￥2000), Nankai University(南开大学学业优秀奖学金)；

- 2023.10:&nbsp;💰Literary and Sports Scholarship(￥2000), Nankai University(南开大学文体奖学金)；



<span class='anchor' id='competitions'></span>

# 🏆 Competitions

- 2025.12:&nbsp;🏆The 3rd price of [2025 Haihe Cup](https://news.qq.com/rain/a/20260104A05CCT00)(￥5000),Tianjin(天津市“海河工匠杯”技能大赛决赛三等奖)；

- 2025.10:&nbsp;🏆[Changcheng Cup](https://endbm.ichunqiu.com/ccb2025), China(2025年第五届“长城杯”网络安全大赛“安全卫士”称号)；

- 2025.10:&nbsp;🏆The 1st prize of [2025 Beijing–Tianjin–Hebei Security Cup](https://www.tjise.edu.cn/info/1008/4592.htm), Tianjin(2025年京津冀大学生信息安全网络攻防大赛决赛一等奖)；

- 2025.08:&nbsp;🏆The 1st prize of [National Crypto-math Challenge](https://mp.weixin.qq.com/s/s_k4A0qcHwXBW3SreGsyRQ)(￥10000, Top 4), China(第十届全国高校密码数学挑战赛全国总决赛**一等奖**，单赛道**第一名**，并作为唯一本科生参与**特等奖答辩**)；

- 2025.08:&nbsp;🏆The 2nd prize of [National AI Security Contest for College Students](https://mp.weixin.qq.com/s/OpAf9eXVn_wdsNrdve7mfQ), China(第一届全国大学生人工智能安全竞赛作品赛二等奖)；

- 2025.07:&nbsp;🏆The 1st prize of [National Crypto-math Challenge](http://www.cmsecc.com/d/file/xuanchuan/2025-09-05/huabei.pdf)(rank 1st), Huabei Region(第十届全国高校密码数学挑战赛华北赛区一等奖，单赛道**第一名**)；

- 2025.03:&nbsp;🏆The 3rd Prize (CTF) of [National College Student information Security Contest](http://www.ciscn.cn/competition/securityCompetition), China(第十八届全国大学生信息安全竞赛创新实践能力赛半决赛三等奖)；

- 2024.11:&nbsp;🏆Qiangwang Pioneer Prize of [Qiangwang Bei](https://www.qiangwangbei.com/), China(第八届强网杯“强网先锋”荣誉称号)；

- 2024.11:&nbsp;🏆Wangding Star of [Wangding Bei](https://www.wangdingcup.com/index_list.html), China(第四届网鼎杯“网鼎之星”荣誉称号)；

- 2024.09:&nbsp;🏆The 1st prize of [2024 Beijing–Tianjin–Hebei Security Cup](https://www.tjise.edu.cn/info/1007/3442.htm), Tianjin(2024年京津冀大学生信息安全网络攻防大赛决赛一等奖)；

- 2023.12:&nbsp;🏆Third prize of the 15th Chinese Mathematics Competitions, China(第十五届全国大学生数学竞赛三等奖)；

<span class='anchor' id='honors-and-awards'></span>

# 🎖️ Honors and Awards

- 2026.01:&nbsp;🎉Participated in the Third Information Security Youth Training Camp organized by Tsinghua University and ranked top 20%(参与清华大学网络科学与网络空间研究院组织的**第三届信息安全青训营**，在考核中排名前20%);

- 2026.01:&nbsp;🎖Intermediate Network and Information Security Administrator, Tianjin(晋升网络与信息安全管理员**中级工**职称);

- 2025.11:&nbsp;🎖[Excellent student](https://mp.weixin.qq.com/s/aeUkiL33ibibZscemNARZA), Tianjin(**天津市优秀学生**)；

- 2025.11:&nbsp;🎖Outstanding Student, Nankai University(南开大学三好学生)；

- 2025.09:&nbsp;🎖Excellent Teaching Assistant, Nankai University(南开大学本科课程优秀助教)；

- 2025.06:&nbsp;🎖Awarded the Honorary Title of "[Top Ten Micro Party Lectures](https://mp.weixin.qq.com/s/HtZrsLp9LNndmtOzxZeOwQ)"，Nankai University(南开大学“十佳微党课”荣誉称号)；

- 2025.06:&nbsp;🎖Outstanding Team in the [National College Student Yimeng Spirit Volunteer Publicity Campaign](https://mp.weixin.qq.com/s/-nQ3BddP-9yxW9xoccRbog)，China(全国大学生沂蒙精神志愿宣讲活动优秀团队)；

- 2025.06:&nbsp;🎖Head of Red Flag Party Branch，Nankai University(南开大学红旗学生党支部主要负责人)；

- 2025.05:&nbsp;🎖Outstanding Communist Youth League Cadre, Nankai University(南开大学优秀共青团干部)；

- 2025.04:&nbsp;🏆Top 10 Singers in the Second Singing Competition of the College of Cryptology and Cyber Science, Nankai University(学院第二届十大歌手)；

- 2025.03:&nbsp;🎖National Information Security Test Program(Grade 1), China(国家信息安全水平考试一级)；

- 2025.02:&nbsp;🎖Awarded the Title of "Top Ten Volunteer Service Projects"，Nankai University(南开大学“十佳志愿服务项目”称号);

- 2024.12:&nbsp;🎖Sangfor Certified Security Associate Service, China(深信服SCSA认证)；

- 2024.11:&nbsp;🎖Outstanding Student, Nankai University(南开大学三好学生)；

- 2024.10:&nbsp;🎖Qianxin Certified Emergency Response Engineer, China(奇安信应急响应工程师认证)；

- 2024.09:&nbsp;🎖Outstanding Core Member of the "Hao Mi" Group, Nankai University(“豪密”爱国主义宣讲团优秀骨干)；

- 2024.05:&nbsp;🎖Outstanding Youth League member, Nankai University(南开大学优秀共青团员)；

- 2023.10:&nbsp;🏆Top 10 Singers in the First Singing Competition of the College of Cryptology and Cyber Science, Nankai University(学院第一届十大歌手)；

- 2023.05:&nbsp;🎖Third Prize and Outstanding Organization Award in ["May Flowers" Choir Competition](https://mp.weixin.qq.com/s/cq9SY25Z5Ur_hgKEXWDH3A)(as Team Leader), Nankai University(作为学院领队，获南开大学“五月的鲜花”合唱比赛三等奖、优秀组织奖)；








<span class='anchor' id='projects'></span>

# ⚙️ Projects

<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Zipf</div>
      <img src='images/projects/Zipf.png' alt="Zipf" width="100%">
    </div>
  </div>

  <div class='paper-box-text'>
    <p>
      <a href="https://mp.weixin.qq.com/s/G7Z5YdUcSwm8qtpgRfDTkQ" target="_blank" rel="noopener"><strong>Revisiting Zipf ’s Law in Passwords: A Taylor Series Modeling Approach</strong></a>
    </p>
    <p>
      <span class="paper-role-badge">Team Member</span>
      <span class="paper-time-badge">2025.04 – 2025.08</span>
    </p>
<ul style="margin-top: 0.5em; padding-left: 1.5em;">
    <li>Reproduced CDF-Zipf from the <a href="https://ieeexplore.ieee.org/document/7961213">original paper</a> and conducted multiple rounds of experiments to test the fitting rate, obtaining error results consistent with those in the paper. Optimized the original paper's approach using methods such as the binsort algorithm, achieving a performance improvement of <strong>1.97-3.93 times</strong>.</li>
    <li>Proposed a new model, <strong>Exp-Cutoff</strong>, and a hybrid model, <strong>Mix_CDF</strong>, which integrates the strengths of CDF-Zipf and <a href="https://ieeexplore.ieee.org/abstract/document/9777714">Stretched-exponential</a>. Both models achieved the best KS distance on all test datasets (Myspace, Rockyou, Dodonew, 000webhost, etc.), with a maximum optimization of <strong>55.39%</strong>.</li>
    <li>Conducted <strong>subset stability validation</strong> experiments by fitting data subsets of varying proportions (10%, 25%, etc.). The resulting errors were all below <strong>5%</strong>, demonstrating the stability of the models.</li>
</ul>
  </div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">CodeShielder</div>
      <img src='images/projects/CodeShielder.png' alt="CodeShielder" width="100%">
    </div>
  </div>

  <div class='paper-box-text'>
    <p>
      <a href="https://mp.weixin.qq.com/s/TaQEUHLS5iHyKcFEIWorjg" target="_blank" rel="noopener"><strong>CodeShielder: An Expert Vulnerability Detection System Based on Fine-Tuned Large Language Models</strong></a>
    </p>
    <p>
      <span class="paper-role-badge">Team Leader</span>
      <span class="paper-time-badge">2025.03 – 2025.08</span>
    </p>
<ul style="margin-top: 0.5em; padding-left: 1.5em;">
    <li>Built a vulnerability detection system based on <strong>fine-tuned large language models</strong> and constructed the <strong>VulExpert</strong>, which outperforms prior works (e.g., <a href="https://arxiv.org/pdf/2406.03718">VulLLM</a>) in vulnerability detection.</li>
    <li>In <strong>dataset construction</strong>, commits were crawled from GitHub, and the VulExpert dataset was built through a series of steps including <strong>binary classification</strong>, <strong>patch crawling</strong>, and <strong>diff code extraction</strong>.</li>
    <li>For <strong>model fine-tuning</strong>, the acquired dataset was used to fine-tune the base model <strong>Qwen-14B</strong> via <strong>Q-LoRA</strong>, resulting in the fine-tuned model.</li>
    <li>Fine-tuning tests were conducted on datasets such as <strong>BigVul</strong>, <strong>Draper</strong>, <strong>DiverseVul</strong> and <strong>Reveal</strong>. The results show that our VulExpert achieves significantly better fine-tuning performance compared to baselines.</li>
</ul>
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div>
      <div class="badge">Vulnerability Wiki</div>
      <img src='images/projects/Vulnerability Wiki.png' alt="Vulnerability Wiki" width="100%">
    </div>
  </div>

  <div class='paper-box-text'>
    <p>
      <a href="https://www.vul-wiki.org/" target="_blank" rel="noopener"><strong>Vulnerability Wiki: a Comprehensive, Systematic and Multi-dimensional Knowledge-sharing Community for Vulnerabilities</strong></a>
    </p>
    <p>
      <span class="paper-role-badge">Team Member</span>
      <span class="paper-time-badge">2025.08 – 2025.10</span>
    </p>
<ul style="margin-top: 0.5em; padding-left: 1.5em;">
    <li>Systematically organize the principles, attack techniques, detection, and defense methods of various vulnerabilities.</li>
    <li>Track high-risk CVE cases, combining reproduction environments and exploitation chain analysis
Provide learning materials tailored to different technical skill levels.</li>
    <li>Pool community efforts to collaboratively build an open and shared vulnerability encyclopedia.</li>


</ul>
  </div>
</div>






<span class='anchor' id='educations'></span>

# 📖 Educations

- *2022.09 - 2026.06*, **[College of Cryptology and Cyber Science](https://cyber.nankai.edu.cn/)(密码与网络空间安全学院), [Nankai University](https://www.nankai.edu.cn/)(南开大学)**

  *- Major in Cyber Security & Minor in Finance(主修信息安全，辅修金融学)*

- *2026.09 - 2029.06*, **[College of Software and Microelectronics](https://ss.pku.edu.cn/)(软件与微电子学院), [Peking University](https://www.pku.edu.cn/)(北京大学)**


<span class='anchor' id='academic-services'></span>

# 💬 Academic Services

- *2024.09-2025.08*, President of the Student Union of the College of Cryptology and Cyber Science, Nankai University(计算机学院和密码与网络空间安全学院学生会主席);

- *2024.09-2025.08*, Vice Captain of "Haomi", Nankai University(南开大学“豪密”爱国主义宣讲团副团长);

- *2023.09-2026.06*, Class Monitor of the College of Cryptology and Cyber Science, Nankai University(班长);

- *2025.03-2026.01*, Part-time Instructor, Nankai University(南开大学兼职辅导员);

- *2025.08-2026.06*, Organization Committee Member of the Party Branch of the College of Cryptology and Cyber Science, Nankai University(党支部组织委员);

- *2025.08-2026.06*, Vice President of the Information Security Association, Nankai University(南开大学信息安全协会副会长);

- *2023.09-2024.01*, Teaching Assistant for Higher Mathematics Class AI, Nankai University(高等数学AI课程助教);

- *2024.03-2024.07*, Teaching Assistant for Higher Mathematics Class AII, Nankai University(高等数学AII课程助教);

- *2024.09-2025.01*, Teaching Assistant for Higher Mathematics Class AI, Nankai University(高等数学AI课程助教);

- *2025.03-2025.07*, Teaching Assistant for Cryptology, Nankai University(密码学基础课程助教);

- *2025.09-2026.01*, Teaching Assistant for Higher Mathematics Class AI, Nankai University(高等数学AI课程助教);



<span class='anchor' id='internships'></span>

# 💻 Internships

- *2024.07 - 2024.08*, **[360 Safety Company](https://360.net/)(360安全集团)**

  *- Conducted penetration testing and vulnerability discovery tasks, reproduced various types of vulnerabilities, and developed PoC exploits.*





<div class="logo-row">
  <img src="../images/NKU.png" alt="NKU Logo">
  <img src="../images/PKU.png" alt="PKU Logo">
</div>

<footer class="site-footer">
  <p>&copy; 2025 <a href="https://github.com/Luhaozhhhhe" target="_blank" rel="noopener">Haozhe Lu</a> all rights reserved</p>
  
  <p>
    Template adapted from
    <a href="https://github.com/RayeRen/acad-homepage.github.io" target="_blank" rel="noopener">Yi Ren</a>
  </p>
  <p>Last modified: <time datetime="{{ site.time | date_to_xmlschema }}">{{ site.time | date: "%b %d, %Y" }}</time></p>

</footer>