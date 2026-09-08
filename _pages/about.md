---
permalink: /
title: ""
excerpt: ""
author_profile: true
# redirect_from: 
#   - /about/
#   - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<!-- <span class='anchor' id='about-me'></span> -->

# Biography

I am a first-year M.S. student at [MVIG](https://www.mvig.org/), Shanghai Jiao Tong University. I am supervised by [Prof. Cewu Lu](https://www.mvig.org/) and [Prof. Jianhua Sun](https://gothicai.github.io/HomePage/). I have great research interest in 3D vision and robotics. Previously, I got my B.Eng. degree in SJTU. 
<!-- I was enrolled in the first session of [Guozhi Class](http://www.qingyuan.sjtu.edu.cn/c/Introductiongzb).  -->

*Email:* wjd_kznwl@sjtu.edu.cn

# Publications 


<div class='paper-box highlight-green'><div class='paper-box-image'><div><img src='images/pub/StructPolicy.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a class="paper-title" href="https://structpolicy.github.io/StructPolicy-Homepage/#">StructPolicy: Structure-Guided Imitation Learning Robust to Visual Domain Shifts</a>

Zehao Du<sup>\*</sup>, **Jiude Wei**<sup>\*</sup>, Cewu Lu, Jianhua Sun<sup>§</sup>

<span class="paper-venue">ECCV 2026</span>

[\[**Project Page**\]](https://structpolicy.github.io/StructPolicy-Homepage/#)

<details class="paper-tldr" markdown="1">
<summary>TL;DR</summary>

We propose StructPolicy, a lightweight structure-aware module that extracts task-relevant structural cues from visual observations to guide imitation learning, improving manipulation robustness against visual distribution shifts. 

</details>

</div>
</div>
<div class='paper-box'><div class='paper-box-image'><div><img src='images/pub/blueprint.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a class="paper-title" href="https://arxiv.org/abs/2510.07975">Empowering Precise Embodied Agents with Executable Analytic Concepts as Semantic-Physical Blueprints</a>

Mingyang Sun, **Jiude Wei**, Qichen He, Donglin Wang, Cewu Lu, Jianhua Sun<sup>§</sup>

<span class="paper-venue">IJCAI 2026</span>

[\[**Paper**\]](https://arxiv.org/pdf/2510.07975)

<details class="paper-tldr" markdown="1">
<summary>TL;DR</summary>

We propose GRACE, a training-free framework that bridges VLM reasoning and precise robot execution through executable analytic concepts, enabling semantic-to-physical grounding and zero-shot generalization for articulated-object manipulation tasks.

</details>

</div>
</div>


<div class='paper-box highlight-green'><div class='paper-box-image'><div><img src='images/pub/aotllm.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a class="paper-title" href="https://openaccess.thecvf.com/content/CVPR2026/papers/Wei_Physically_Ground_Commonsense_Knowledge_for_Articulated_Object_Manipulation_with_Analytic_CVPR_2026_paper.pdf">Phsyically Ground Commonsense Knowledge for Articulated Object Manipulation with Analytic Concepts</a>

**Jiude Wei**, Yuxuan Li, Cewu Lu, Jianhua Sun<sup>§</sup>

<span class="paper-venue">CVPR 2026</span>

[\[**Paper**\]](https://openaccess.thecvf.com/content/CVPR2026/papers/Wei_Physically_Ground_Commonsense_Knowledge_for_Articulated_Object_Manipulation_with_Analytic_CVPR_2026_paper.pdf)

<details class="paper-tldr" markdown="1">
<summary>TL;DR</summary>

We introduce Analytic Concepts as the bridge between the semantic-level knowledge inferred by MLLMs and the physics level where robots operate, to ground the object knowledge to physics level and guide object manipulation. 

</details>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/pub/artipg.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a class="paper-title" href="https://arxiv.org/abs/2412.14974">Arti-PG: A Toolbox for Procedurally Synthesizing Large-Scale and Diverse Articulated Objects with Rich Annotations</a>

Jianhua Sun<sup>\*</sup>, Yuxuan Li<sup>\*</sup>, **Jiude Wei**<sup>\*</sup>, Longfei Xu, Nange Wang, Yining Zhang, Cewu Lu<sup>§</sup>

<span class="paper-venue">ICCV 2025</span>

[\[**Paper**\]](https://arxiv.org/pdf/2412.14974) [\[**Code**\]](https://github.com/Analytic-Concept-Group/ArtiPG)

<details class="paper-tldr" markdown="1">
<summary>TL;DR</summary>

We propose the Articulated Object Procedural Generation (Arti‑PG) toolbox, which synthesizes diverse and unlimited articulated objects with rich annotations through program‑oriented structure manipulation and analytic label alignment, addressing the scarcity of high‑quality articulated object data and annotations.

</details>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/pub/aot.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a class="paper-title" href="https://arxiv.org/pdf/2409.11702">Discovering Conceptual Knowledge with Analytic Ontology Templates for Articulated Objects</a>

Jianhua Sun<sup>\*</sup>, Yuxuan Li<sup>\*</sup>, Longfei Xu<sup>†</sup>, **Jiude Wei**<sup>†</sup>, Liang Chai, Cewu Lu<sup>§</sup>

<span class="paper-venue">AAAI 2025, <span class="paper-highlight">Oral</span></span>

[\[**Paper**\]](https://arxiv.org/pdf/2409.11702)

<details class="paper-tldr" markdown="1">
<summary>TL;DR</summary>

We present AOT and the AOT-driven baseline AOTNet to empower machine intelligence with the kind of human capability to understand and then interact with articulated objects, espeically the novel ones, at the conceptual level for the first time. 

</details>

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><img src='images/pub/confac.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

<a class="paper-title" href="https://arxiv.org/pdf/2411.00448">ConceptFactory: Facilitate 3D Object Knowledge Annotation with Object Conceptualization</a>

Jianhua Sun<sup>\*</sup>, Yuxuan Li<sup>\*</sup>, Longfei Xu<sup>†</sup>, Nange Wang<sup>†</sup>, **Jiude Wei**<sup>†</sup>, Yining Zhang, Cewu Lu<sup>§</sup>

<span class="paper-venue">NeurIPS 2024 Datasets and Benchmarks Track</span>

[\[**Project Website**\]](https://apeirony.github.io/ConceptFactory) [\[**Paper**\]](https://arxiv.org/pdf/2411.00448)

<details class="paper-tldr" markdown="1">
<summary>TL;DR</summary>

We present ConceptFactory, a novel scope to facilitate more efficient annotation of 3D object knowledge through object conceptualization, containing a unified toolbox for object conceptualization and a large collection of conceptualized objects. 

</details>

</div>
</div>


# Honors and Awards
  - *2021.12:* Academic Exellent Scholarship of Shanghai Jiao Tong University
  - *2019.12 & 2017.12:* **First Price**, NOIP (National Olympiad in Informatics in Province)


# Education
- *2025.09 - Present*, M.S., major in Computer Science, SAI, Shanghai Jiao Tong University
- *2021.09 - 2025.06*, B.Eng., major in Artificial Intelligence, SEIEE, Shanghai Jiao Tong University
<!-- - *2018.09 - 2021.06*, High School Affiliated to Shanghai Jiao Tong University -->
