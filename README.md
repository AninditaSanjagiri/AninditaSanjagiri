<div align="center">

<img src="assets/hero-banner.svg" width="100%" alt="Anindita Sanjagiri — AI/ML Developer & Researcher"/>

<br><br>

[![typing tagline](https://readme-typing-svg.demolab.com?font=Fira+Code&size=14&duration=2800&pause=1200&color=8B93A1&center=true&vCenter=true&width=620&height=24&lines=building+systems+that+don%27t+fall+over+in+production;computer+vision+%C2%B7+nlp+%C2%B7+applied+security;currently%3A+vision+transformers+%2B+paper+reproduction)](https://git.io/typing-svg)

<br>

<a href="https://github.com/AninditaSanjagiri"><img src="https://img.shields.io/badge/GitHub-0D1117?style=flat-square&logo=github&logoColor=A78BFA" alt="GitHub"/></a>
<a href="https://www.linkedin.com/in/anindita-sanjagiri-a04989233/"><img src="https://img.shields.io/badge/LinkedIn-0D1117?style=flat-square&logo=linkedin&logoColor=A78BFA" alt="LinkedIn"/></a>
<a href="mailto:anindita.sanjagiri@gmail.com"><img src="https://img.shields.io/badge/Email-0D1117?style=flat-square&logo=gmail&logoColor=A78BFA" alt="Email"/></a>
<a href="https://leetcode.com/u/Anindita_Sanjagiri/"><img src="https://img.shields.io/badge/LeetCode-0D1117?style=flat-square&logo=leetcode&logoColor=A78BFA" alt="LeetCode"/></a>
<a href="#"><img src="https://img.shields.io/badge/Resume-0D1117?style=flat-square&logo=readdotcv&logoColor=A78BFA" alt="Resume"/></a>
<!-- swap the "#" above for a hosted resume link — see notes at the bottom -->

<br><br>

<code>01 <a href="#about">about.me</a></code> &nbsp;&#183;&nbsp;
<code>02 <a href="#now">currently.exe</a></code> &nbsp;&#183;&nbsp;
<code>03 <a href="#stack">tech_stack.json</a></code> &nbsp;&#183;&nbsp;
<code>04 <a href="#projects">featured_projects/</a></code> &nbsp;&#183;&nbsp;
<code>05 <a href="#research">research_lab/</a></code> &nbsp;&#183;&nbsp;
<code>06 <a href="#stats">github_stats.py</a></code> &nbsp;&#183;&nbsp;
<code>07 <a href="#connect">connect.sh</a></code>

</div>

<br>

<a name="about"></a>

### `01` `about.me`

I'm a final-year engineering student who builds ML systems that touch real data and real constraints — not just notebooks that stop at a validation score. Most of my work sits across NLP, computer vision, and applied security: multi-model pipelines, honest evaluation, and shipping something that actually runs.

I spent a summer at **Bajaj Finance** deploying speech-to-text pipelines on Databricks and training risk-classification models for underwriting. It's mostly why I care about the boring parts now — data validation, explainability, latency — as much as the model itself.

<br>

<a name="now"></a>

### `02` `currently.exe`

```
→ PyTorch                          [ deepening ]
→ Vision Transformers               [ exploring ]
→ Anomaly Detection                 [ building  ]
→ Research paper reproduction       [ ongoing   ]
→ MLOps & model deployment          [ learning  ]
→ Generative AI / model optimisation[ exploring ]
```

<br>

<a name="stack"></a>

### `03` `tech_stack.json`

**Languages**

<img src="https://skillicons.dev/icons?i=python,cpp,c,r&theme=dark" alt="languages"/>

**ML / AI**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn,opencv&theme=dark" alt="ml stack"/>

**Systems &amp; Tools**

<img src="https://skillicons.dev/icons?i=fastapi,react,streamlit,git,postman&theme=dark" alt="tools"/>

<sub>`Pandas` `NumPy` `Transformers (HF)` `Databricks` — not all libraries have icons, so these are listed in text.</sub>

<br>

<a name="projects"></a>

### `04` `featured_projects/`

<table>
<tr>
<td width="50%" valign="top">

**`01`  PhishNet** — multimodal phishing detection

Three models running in parallel — Random Forest on URL features, DistilBERT on page text, MobileNetV3 on screenshots — fused into one verdict with SHAP/LIME explanations attached. Sub-200ms end to end on CPU.

<img src="https://img.shields.io/github/languages/top/AninditaSanjagiri/Phishnet?style=flat-square&color=A78BFA&labelColor=0D1117" alt="lang"/> <img src="https://img.shields.io/github/stars/AninditaSanjagiri/Phishnet?style=flat-square&color=A78BFA&labelColor=0D1117&logo=github" alt="stars"/>

`FastAPI` `PyTorch` `Transformers` `SHAP` `React`

[→ view repository](https://github.com/AninditaSanjagiri/Phishnet)

</td>
<td width="50%" valign="top">

**`02`  Facial Emotion Recognition**

A CNN trained for real-time facial-expression classification, taken from a 20% baseline to 60% accuracy through augmentation and hyperparameter tuning, optimised to run live on standard hardware.

<img src="https://img.shields.io/github/languages/top/AninditaSanjagiri/facial-emotion-recognition-cnn?style=flat-square&color=A78BFA&labelColor=0D1117" alt="lang"/> <img src="https://img.shields.io/github/stars/AninditaSanjagiri/facial-emotion-recognition-cnn?style=flat-square&color=A78BFA&labelColor=0D1117&logo=github" alt="stars"/>

`TensorFlow` `Keras` `OpenCV`

[→ view repository](https://github.com/AninditaSanjagiri/facial-emotion-recognition-cnn)

</td>
</tr>
<tr>
<td width="50%" valign="top">

**`03`  Bio-Aligned Fit**

A data-driven look at how workout recommendations should shift across hormonal phases — an ML pipeline over physiological and lifestyle inputs, evaluated on precision/recall, shipped as a Streamlit app.

<img src="https://img.shields.io/github/languages/top/AninditaSanjagiri/BioAligned-Fit?style=flat-square&color=A78BFA&labelColor=0D1117" alt="lang"/> <img src="https://img.shields.io/github/stars/AninditaSanjagiri/BioAligned-Fit?style=flat-square&color=A78BFA&labelColor=0D1117&logo=github" alt="stars"/>

`scikit-learn` `Pandas` `Streamlit`

[→ view repository](https://github.com/AninditaSanjagiri/BioAligned-Fit)

</td>
<td width="50%" valign="top">

**`04`  CourseRecommender**

A hybrid content-based + collaborative-filtering engine that recommends courses from past ratings and genre similarity — recommender-systems groundwork the flashier projects build on.

<img src="https://img.shields.io/github/languages/top/AninditaSanjagiri/CourseRecommender?style=flat-square&color=A78BFA&labelColor=0D1117" alt="lang"/> <img src="https://img.shields.io/github/stars/AninditaSanjagiri/CourseRecommender?style=flat-square&color=A78BFA&labelColor=0D1117&logo=github" alt="stars"/>

`Pandas` `scikit-learn`

[→ view repository](https://github.com/AninditaSanjagiri/CourseRecommender)

</td>
</tr>
</table>

<div align="right"><sub><a href="https://github.com/AninditaSanjagiri?tab=repositories">view all repositories →</a></sub></div>

<br>

<a name="research"></a>

### `05` `research_lab/`

<table>
<tr>
<td width="60%" valign="top">

```
ACTIVE AREAS

→ Computer Vision
→ Anomaly Detection
→ NLP & Foundation Models
→ Research paper reproduction
→ Applied deep learning systems
```

I care less about squeezing out an extra point of accuracy and more about *why* a model fails — where the baseline breaks, what the edge cases look like, whether the result reproduces.

</td>
<td width="40%" align="center">
<img src="assets/grid-motif.svg" width="260" alt="feature space grid"/>
</td>
</tr>
</table>

<br>

<a name="stats"></a>

### `06` `github_stats.py`

<table>
<tr>
<td width="50%">
<img src="https://github-readme-stats.vercel.app/api?username=AninditaSanjagiri&show_icons=true&hide_border=true&bg_color=0D1117&title_color=A78BFA&icon_color=A78BFA&text_color=E6EDF3&ring_color=A78BFA" alt="GitHub Stats"/>
</td>
<td width="50%">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AninditaSanjagiri&layout=compact&hide_border=true&bg_color=0D1117&title_color=A78BFA&text_color=E6EDF3&langs_count=8" alt="Top Languages"/>
</td>
</tr>
</table>

<img src="https://streak-stats.demolab.com/?user=AninditaSanjagiri&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA&sideLabels=E6EDF3&currStreakNum=E6EDF3&sideNums=E6EDF3&dates=6B7280" alt="GitHub Streak" width="100%"/>

**`> contribution_graph.exe`**

<img src="https://ghchart.rshah.org/A78BFA/AninditaSanjagiri" alt="Contribution Graph" width="100%"/>

<br>

<a name="connect"></a>

### `07` `connect.sh`

```
$ cat contact.txt

github     → github.com/AninditaSanjagiri
linkedin   → linkedin.com/in/anindita-sanjagiri
email      → anindita.sanjagiri@gmail.com
leetcode   → leetcode.com/u/Anindita_Sanjagiri
```

<br>

<div align="center">
<sub>start from the problem, not the model.</sub>
</div>
