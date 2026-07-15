---
permalink: /research/
title: "Research"
search: true
---

## Research Interests

My research is at the intersection of precision medicine, causal inference, and sequential decision-making, with applications in healthcare. I am broadly interested in problems where rigorous statistical thinking can directly inform policy and intervention design.

Current projects include work on **adaptive treatment policies** using online learning in precision medicine; and **causal inference with multiple instruments**, particularly over-identified instrumental variable settings. I am happy to discuss any of them. Feel free to [reach out](mailto:aniruddhan_ganesaraman@unc.edu), and see the [Recent News](/#recent-news) section on the homepage for the latest updates!

## Submitted Papers

<ol class="submitted-papers">

<li markdown="1">

*Proactive Inpatient Bed Requests for Emergency Department Admissions*, joint work with [Qian Cheng](https://www.linkedin.com/in/qian-cheng-552978147/), [Nilay Tanik Argon](https://nta.web.unc.edu), and [Serhan Ziya](https://ziya.web.unc.edu) — submitted to [Manufacturing & Service Operations Management](https://pubsonline.informs.org/journal/msom).

[SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7115720){:target="_blank"}

<details class="bibtex-details">
<summary>BibTeX</summary>
<pre><code id="bibtex-proactive-beds">@unpublished{cheng2026proactivebeds,
  author = {Cheng, Qian and Argon, Nilay Tanik and Ganesaraman, Aniruddhan and Ziya, Serhan},
  title  = {Proactive Inpatient Bed Requests for Emergency Department Admissions},
  note   = {Submitted to Manufacturing \&amp; Service Operations Management},
  year   = {2026},
  url    = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7115720}
}</code></pre>
<button type="button" class="bibtex-copy-btn" onclick="copyBibtex('bibtex-proactive-beds', this)">Copy BibTeX</button>
</details>

</li>

<li markdown="1">

*Data Driven Block Replacement Scheduling*, joint work with [Vidyadhar Kulkarni](https://vkulkarn.web.unc.edu) — submitted to [Operations Research](https://pubsonline.informs.org/journal/opre).

[SSRN](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7010598){:target="_blank"}

<details class="bibtex-details">
<summary>BibTeX</summary>
<pre><code id="bibtex-block-replacement">@unpublished{ganesaraman2026blockreplacement,
  author = {Ganesaraman, Aniruddhan and Kulkarni, Vidyadhar},
  title  = {Data Driven Block Replacement Scheduling},
  note   = {Submitted to Operations Research},
  year   = {2026},
  url    = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7010598}
}</code></pre>
<button type="button" class="bibtex-copy-btn" onclick="copyBibtex('bibtex-block-replacement', this)">Copy BibTeX</button>
</details>

</li>

</ol>

<script>
function copyBibtex(id, btn) {
  var text = document.getElementById(id).innerText;
  navigator.clipboard.writeText(text).then(function () {
    var original = btn.innerText;
    btn.innerText = 'Copied!';
    setTimeout(function () { btn.innerText = original; }, 1500);
  });
}
</script>

<style>
.submitted-papers { padding-left: 1.4em; }
.submitted-papers li { margin-bottom: 1.4em; }
.bibtex-details { margin-top: 0.5em; }
.bibtex-details summary { cursor: pointer; font-weight: 600; }
.bibtex-details pre { margin-top: 0.5em; }
.bibtex-copy-btn { margin-top: 0.5em; }
</style>

## Course Projects in UNC

Course projects have been an important part of my research development at UNC. They have allowed me to collaborate, engage seriously with open problems, replicate and extend results from the literature, and explore areas adjacent to my dissertation work.

| Semester | Course | Project Title | Materials
|---|---|---|---|
| Spring 2026 | HPM 883 (Causal Machine Learning) | Benchmarking Estimators of Local Average Treatment Effect | [Github Repo](https://github.com/AniruddhanG/LATE-Estimators) |
| Fall 2025 | BIOS 777 (Precision Medicine) | Deep RL for Personalized Treatment Recommendation ([Main Paper](https://pubmed.ncbi.nlm.nih.gov/35716038/)) | [Report](https://www.dropbox.com/scl/fi/je9dhasw81ixf0meo6tt5/777_Final_Report.pdf?rlkey=inwtdo669vr9bop3rdcna5vpq&st=3c6j3yx9&dl=0) \| [Slides](https://www.dropbox.com/scl/fi/vnufm09mal1xnt1asr66h/777_Slides.pdf?rlkey=3hfw0icnn174ftghqkcc472p8&st=f675pe2f&dl=0) | 
| Fall 2025 | STOR 743 (Reinforcement Learning and MDP) | Deep RL for Personalized Treatment Recommendation ([Main Paper](https://pubmed.ncbi.nlm.nih.gov/35716038/)) | [Report](https://www.dropbox.com/scl/fi/1vssghwf6dpy627coo1z3/743_Final_Report.pdf?rlkey=qifcpiqk78poflt8gmnefat6f&st=7bul3c0u&dl=0) \| [Slides](https://www.dropbox.com/scl/fi/jtph8688sdn0oueu8bfip/743_Slides.pdf?rlkey=8j8fl38vlzwk2o6p55fkf2lza&st=tgmqxrrp&dl=0) | 
| Fall 2025 | STOR 664 (Applied Statistics I) | NFL Resource Allocations | [Github Repo](https://github.com/AniruddhanG/UNC-STOR-664-Fall-2025-Project-NFLAllocation/tree/main) |
| Spring 2026 | STOR 672 (Simulations) | Possible causes for increased boarding times | [Report](https://www.dropbox.com/scl/fi/lmv68uy5j1aab0fvzlwxo/672_Project_Report.pdf?rlkey=3p5ahum4cevxlhy49tk3t1zs1&st=dp5qnzhx&dl=0) \| [Slides](https://www.dropbox.com/scl/fi/9h5vhdoil55rkw79xcsii/672-Presentation.pdf?rlkey=yob1jvu580f1v0augc8s38hgt&st=vdr6o2mi&dl=0) | 
| Fall 2024 | STOR 634 (Probability I) | Bayesian NPI of Topic Hierarchies | [Report](https://www.dropbox.com/scl/fi/9fi42vt18eww5k3yxakq0/634_Project_Final_Report.pdf?rlkey=rqin9ty8qd3jn5mlqqn556tso&st=fhq279lj&dl=0) | 

## Conferences & Schools Attended

I have made a deliberate effort to attend conferences and workshops across a variety of areas. I find that broad exposure to different methodologies helps me find my footing and think more creatively.

- **[American Causal Inference Conference (ACIC) 2026](https://sci-info.org/2026-meeting-2/)** (May 2026) - 
- **[Conference on Extreme Value Analysis 2025](https://eva2025.unc.edu/)** (June 2025) — Volunteered at this international conference hosted at UNC Chapel Hill, NC. A great introduction to the breadth of extreme value theory and its applications across climate science, public health, and finance.
- **[DAIR³ — Data and AI Intensive Research with Rigor and Reproducibility](https://dair-3.org/)** (May 2025) — An NIH-supported weeklong bootcamp focused on rigorous and reproducible biomedical data science, covering ethical AI, data management, analytical design, and reproducible workflows. Held at [Jackson State University](https://www.jsums.edu), Jackson, MS.
- **Mini-course by [Prof. Remco van der Hofstad](https://www.win.tue.nl/~rhofstad/)** (Oct 2024) — Attended a short course on *Dynamic Processes on Networks* offered in the STOR department at UNC Chapel Hill.
- **Advanced Instructional School in Stochastic Processes (AISSP)** (June 2023) — Intensive three-week school covering Brownian motion, martingales, and measure theory, held at [NISER Bhubaneswar, India](https://www.niser.ac.in/), organized by the [National Centre for Mathematics](https://www.atmschools.org/). [[Notes & Problem Sets](https://www.dropbox.com/scl/fo/fr94odgb62io82879a85k/h?rlkey=b5osk4fzozj0135oa01eayxb2&e=1&dl=0)]