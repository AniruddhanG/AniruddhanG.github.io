---
permalink: /research/
title: "Research"
search: true
toc: true
toc_label: "On this page"
toc_sticky: true
description: "Research interests, submitted papers, and course projects of Aniruddhan Ganesaraman, PhD student in Statistics & Operations Research at UNC Chapel Hill, focused on precision medicine, causal inference, and sequential decision-making."
---

## Research Interests

My research is at the intersection of precision medicine, causal inference, and sequential decision-making, with applications in healthcare. I am broadly interested in problems where rigorous statistical thinking can directly inform policy and intervention design.

Current projects include work on **adaptive treatment policies** using online learning in precision medicine, and **causal inference with multiple instruments**, particularly over-identified instrumental variable settings — I'd be happy to discuss either in more depth. Feel free to [reach out](mailto:aniruddhan_ganesaraman@unc.edu), and see the [Recent News](/#recent-news) section on the homepage for the latest updates!

## Submitted Papers

<ol class="submitted-papers" reversed start="2">

<li markdown="1">

*Proactive Inpatient Bed Requests for Emergency Department Admissions*, joint work with [Qian Cheng](https://www.linkedin.com/in/qian-cheng-552978147/), [Nilay Tanik Argon](https://nta.web.unc.edu), and [Serhan Ziya](https://ziya.web.unc.edu) — submitted to [Manufacturing & Service Operations Management](https://pubsonline.informs.org/journal/msom).

<div class="paper-links">
<a class="paper-box" href="#" target="_blank" rel="noopener">arXiv ↗</a>
<a class="paper-box" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7115720" target="_blank" rel="noopener">SSRN ↗</a>
<button type="button" class="paper-box" onclick="toggleBox('abstract-box-proactive-beds')">Abstract</button>
<button type="button" class="paper-box" onclick="toggleBox('bibtex-box-proactive-beds')">BibTeX</button>
</div>

<div id="abstract-box-proactive-beds" class="content-box" style="display:none;">
<p><strong>Problem definition:</strong> Emergency department (ED) boarding occurs when patients admitted to the hospital remain in the ED while waiting for inpatient beds. Boarding is viewed as a major driver of ED crowding and has been associated with poor patient outcomes. We propose a framework to help EDs reduce boarding time and total length of stay by using information about current ED patients and hospital bed availability to proactively request inpatient beds before admission decisions are finalized.</p>
<p><strong>Methodology/results:</strong> We formulate the problem as a Markov decision process in which predictions of each patient's probability of hospital admission and time to disposition are aggregated to guide early inpatient bed requests. This formulation leads to three data-driven policies based on approximate dynamic programming, reinforcement learning, and a newsvendor-type approach. Using a simulation model based on data from a large ED, we evaluate these policies across a wide range of settings. The simulation study shows that proactive aggregate bed requests can reduce average boarding times for admitted patients by 30–70% and average length of stay for all ED patients by 6–15%, while creating only modest idle time for prepared inpatient beds. The newsvendor heuristic provides the most attractive tradeoff between ED performance and inpatient bed idle time, whereas the reinforcement learning-based heuristic produces smoother bed-request patterns when stability in downstream hospital processes is especially important.</p>
<p><strong>Managerial implications:</strong> Our work shows how EDs can use prediction tools to make proactive, ED-level bed-request decisions that improve ED operations while helping managers balance reductions in ED delays against limited idle time for prepared inpatient beds. Our findings also illustrate the value of evaluating both simple myopic heuristics and more sophisticated reinforcement learning-based approaches in this operational problem, since each can offer distinct advantages depending on the performance measures and implementation constraints most important to managers.</p>
</div>

<div id="bibtex-box-proactive-beds" class="content-box" style="display:none;">
<pre><code id="bibtex-code-proactive-beds">@unpublished{cheng2026proactivebeds,
  author = {Cheng, Qian and Argon, Nilay Tanik and Ganesaraman, Aniruddhan and Ziya, Serhan},
  title  = {Proactive Inpatient Bed Requests for Emergency Department Admissions},
  note   = {Submitted to Manufacturing \&amp; Service Operations Management},
  year   = {2026},
  url    = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7115720}
}</code></pre>
<button type="button" class="bibtex-copy-btn" onclick="copyBibtex('bibtex-code-proactive-beds', this)">Copy BibTeX</button>
</div>

</li>

<li markdown="1">

*Data Driven Block Replacement Scheduling*, joint work with [Vidyadhar Kulkarni](https://vkulkarn.web.unc.edu) — submitted to [Operations Research](https://pubsonline.informs.org/journal/opre).

<div class="paper-links">
<a class="paper-box" href="#" target="_blank" rel="noopener">arXiv ↗</a>
<a class="paper-box" href="https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7010598" target="_blank" rel="noopener">SSRN ↗</a>
<button type="button" class="paper-box" onclick="toggleBox('abstract-box-block-replacement')">Abstract</button>
<button type="button" class="paper-box" onclick="toggleBox('bibtex-box-block-replacement')">BibTeX</button>
</div>

<div id="abstract-box-block-replacement" class="content-box" style="display:none;">
<p>We develop data-driven algorithms for maintaining N independent identical machines under a block replacement policy, in which each machine is replaced upon failure and all machines are jointly replaced at regular intervals of length k. The goal is to learn the cost-minimizing interval k* from operational data when the lifetime distribution is unknown. At each decision epoch, the operator selects k ∈ {1, 2, …, K}, observes the resulting failure history (a mixture of complete and right-censored lifetimes) and incurs a per-unit-time cost governed by the renewal function. We formulate this as a stochastic multi-armed bandit and propose Hoeffding- and Bernstein-based lower-confidence-bound algorithms achieving O(K log T) regret, matching the Lai–Robbins lower bound. Exploiting a nested observation property unique to block replacement, correlated variants attain O((K - k*) log T) regret and require only O(1) direct pulls of suboptimal arms k &lt; k*. A complementary Kaplan–Meier renewal algorithm estimates the lifetime distribution nonparametrically from censored data, achieving almost-sure policy consistency and empirically near-zero incremental regret at long horizons. We additionally analyze two average-cost MDPs: a time-elapsed formulation establishing that block replacement is optimal within its policy class for any lifetime distribution, and an age-vector formulation proving a monotone threshold structure under increasing failure rate distributions and providing a gold-standard cost benchmark. Numerical experiments confirm the theoretical ordering and reveal structural cost gaps between optimal block and age-dependent replacement.</p>
<p>Code for replication is publicly available at <a href="https://github.com/AniruddhanG/Block-Replacement-Scheduling" target="_blank" rel="noopener">this GitHub repository</a>.</p>
</div>

<div id="bibtex-box-block-replacement" class="content-box" style="display:none;">
<pre><code id="bibtex-code-block-replacement">@unpublished{ganesaraman2026blockreplacement,
  author = {Ganesaraman, Aniruddhan and Kulkarni, Vidyadhar},
  title  = {Data Driven Block Replacement Scheduling},
  note   = {Submitted to Operations Research},
  year   = {2026},
  url    = {https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7010598}
}</code></pre>
<button type="button" class="bibtex-copy-btn" onclick="copyBibtex('bibtex-code-block-replacement', this)">Copy BibTeX</button>
</div>

</li>

</ol>

<script>
function toggleBox(id) {
  var el = document.getElementById(id);
  if (!el) return;
  el.style.display = (el.style.display === 'block') ? 'none' : 'block';
}
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
.submitted-papers li { margin-bottom: 1.6em; }
.paper-links { display: flex; flex-wrap: wrap; gap: 0.6em; margin: 0.7em 0; }
.paper-box { display: inline-block; padding: 0.35em 0.9em; border: 1px solid currentColor; border-radius: 4px; font-size: 0.9em; font-weight: 600; text-decoration: none; background: none; cursor: pointer; color: inherit; }
.paper-box:hover { opacity: 0.7; }
.content-box { border: 1px solid rgba(128,128,128,0.35); border-radius: 4px; padding: 0.8em 1em; margin: 0 0 0.8em; font-size: 0.92em; }
.content-box pre { margin: 0 0 0.6em; white-space: pre-wrap; }
.content-box p:last-child { margin-bottom: 0; }
.bibtex-copy-btn { padding: 0.25em 0.7em; border: 1px solid currentColor; border-radius: 4px; background: none; cursor: pointer; font-size: 0.85em; color: inherit; }
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

## Conferences & Workshops Attended

Early in my PhD, I have made a deliberate effort to attend conferences and workshops across a variety of areas. I find that broad exposure to different communities and methodologies helps me find my footing and think more creatively about my own work.

| Conference / Workshop | Location | Date | Notes |
|---|---|---|---|
| [INFORMS Annual Meeting](https://meetings.informs.org/wordpress/annual/) | San Francisco, CA | Nov 2026 | *Upcoming* — Invited speaker, MSOM Service Operations session honoring [Prof. Vidyadhar Kulkarni's](https://vkulkarn.web.unc.edu) retirement; presenting *Data Driven Block Replacement Scheduling* with [Vidyadhar Kulkarni](https://vkulkarn.web.unc.edu) |
| [INFORMS Simulation Society Research Workshop](https://isim2026.ise.ncsu.edu) | Raleigh, NC | Jul 2026 | *Upcoming* — Presenting *Proactive Inpatient Bed Requests for Emergency Department Admissions* with [Qian Cheng](https://www.linkedin.com/in/qian-cheng-552978147/), [Nilay Tanik Argon](https://nta.web.unc.edu), and [Serhan Ziya](https://ziya.web.unc.edu) |
| [INFORMS Healthcare Conference](https://meetings.informs.org/wordpress/healthcare/) | Raleigh, NC | Jul 2026 | *Upcoming* — Presenting *Proactive Inpatient Bed Requests for Emergency Department Admissions* with [Qian Cheng](https://www.linkedin.com/in/qian-cheng-552978147/), [Nilay Tanik Argon](https://nta.web.unc.edu), and [Serhan Ziya](https://ziya.web.unc.edu) |
| [American Causal Inference Conference (ACIC) 2026](https://sci-info.org/2026-meeting-2/) | Salt Lake City, UT | May 2026 | Presented latebreaker poster *Estimation of a Common Local Average Treatment Effect with Multiple Instruments* with [Patrick Lopatto](https://lopat.to) and [P. M. Aronow](https://pmaronow.github.io); awarded Honorable Mention in the [Tom Ten Have poster competition](https://sci-info.org/tom-ten-have-award/) |
| [Conference on Extreme Value Analysis (EVA 2025)](https://eva2025.unc.edu/) | Chapel Hill, NC | Jun 2025 | Volunteered; first exposure to the breadth of extreme value theory and its applications across climate science, public health, and finance |
| [DAIR³](https://dair-3.org/) | Jackson, MS | May 2025 | NIH-supported weeklong bootcamp on rigorous and reproducible biomedical data science; held at [Jackson State University](https://www.jsums.edu) |
| Mini-course by [Prof. Remco van der Hofstad](https://www.win.tue.nl/~rhofstad/) | Chapel Hill, NC | Oct 2024 | Short course on *Dynamic Processes on Networks*, hosted by the STOR department at UNC |
| [Advanced Instructional School in Stochastic Processes (AISSP)](https://www.atmschools.org/) | Bhubaneswar, India | Jun – Jul 2023 | Intensive three-week school on Brownian motion, martingales, and measure theory; held at [NISER Bhubaneswar](https://www.niser.ac.in/) [[Notes & Problem Sets](https://www.dropbox.com/scl/fo/fr94odgb62io82879a85k/h?rlkey=b5osk4fzozj0135oa01eayxb2&e=1&dl=0)] |