# Awesome-Technical-Interview-Platform

## Top Technical Interview Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Live Coding Interviews, Automated Assessments, Take-Home Challenges, Code Execution Sandboxes & Candidate Evaluation*

**Last updated: August 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Technical Interview / Coding Assessment**. These tools enable companies to screen and evaluate engineering candidates through live collaborative coding, timed algorithmic challenges, take-home projects, and automated scoring.



**Examples** include CoderPad, HackerRank, Codility, CodeSignal, DevSkiller, Qualified, Interviewing.io, Byteboard, Karat, and CodeSubmit (the category leaders).



**Open-source emphasis**: A growing set of open-source online judges and interview platforms now support self-hosted live coding, auto-graded assessments, and contest-style evaluation. This section is heavily expanded with practical alternatives such as DMOJ, CoderScreen, CodeVerdict, and related projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[CoderPad](https://coderpad.io/)**  

  Leading live collaborative coding interview platform with real-time execution, multi-language support, drawing tools, and replay features designed for in-house technical interviews.



- **[HackerRank](https://www.hackerrank.com/)**  

  Widely used technical assessment platform offering large question libraries, automated coding tests, live interviews, and analytics for high-volume engineering hiring.



- **[Codility](https://www.codility.com/)**  

  Enterprise coding assessment platform known for robust test tasks, plagiarism detection, and structured evaluation of programming skills.



- **[CodeSignal](https://codesignal.com/)**  

  Technical evaluation platform focused on standardized scoring, real-world coding scenarios, and consistent benchmarking across candidates.



- **[DevSkiller](https://devskiller.com/)**  

  Skills-testing platform that emphasizes real-life coding tasks and work-sample assessments rather than pure algorithmic puzzles.



- **[Qualified](https://www.qualified.io/)**  

  Technical screening and interview platform combining auto-graded challenges with collaborative coding environments.



- **[Interviewing.io](https://interviewing.io/)**  

  Anonymous technical interview practice and hiring platform that connects candidates with engineers for realistic mock and real interviews.



- **[Byteboard](https://byteboard.dev/)**  

  Work-sample and realistic engineering assessment platform designed to evaluate practical coding and problem-solving skills.



- **[Karat](https://karat.com/)**  

  Interview-as-a-service platform that provides trained human interviewers to conduct technical interviews on behalf of hiring companies.



- **[CodeSubmit](https://www.codesubmit.io/)**  

  Take-home challenge and coding assessment platform focused on realistic project-based evaluations.



## Open-Source GitHub Projects

- **[DMOJ Online Judge](https://github.com/DMOJ/online-judge)**  

  Modern, production-proven open-source online judge and contest platform supporting 60+ languages, interactive tasks, scalable judging, and flexible contest formats. Used for national olympiads and large competitions.



- **[CoderScreen](https://github.com/CoderScreen/coderscreen)**  

  Open-source technical hiring platform supporting live coding interviews, auto-graded assessments, and take-home challenges in a self-hostable package.



- **[CodeVerdict](https://github.com/ATOAPaymentsLimited/CodeVerdict)**  

  Self-hosted coding exam platform positioned as an open-source alternative to HackerRank/CodeSignal/Codility, with Monaco editor, Judge0 execution, live leaderboards, and ICPC-style scoring.



- **[Open Interview](https://github.com/yuan-alex/open-interview)**  

  Open-source coding interview platform built with Next.js, supporting collaborative sessions and Judge0-based code execution.



- **[CodeGaze](https://github.com/hb1998/CodeGaze)**  

  Free open-source code screening platform for creating custom coding challenges and assessing candidates with Judge0-backed execution.



- **[JudgeX and similar modern OJ systems](https://github.com/)**  

  High-concurrency open online judges with secure sandboxes, multi-language support, and contest features suitable for assessments.



- **[Virtual Online Judge (VOJ) and microservice OJ platforms](https://github.com/)**  

  Open architectures offering local and remote judging, contest management, and scalable evaluation pipelines.



- **[Judge0](https://github.com/judge0/judge0)**  

  Popular open-source code execution engine used as the runtime backend by many self-hosted interview and online-judge platforms.



- **[Custom live-coding and collaborative editor stacks](https://github.com/)**  

  Combinations of Yjs/Y-Sweet, Monaco/CodeMirror, and WebRTC for building real-time pair-programming interview environments.



- **[Plagiarism and similarity detection tools](https://github.com/)**  

  Open libraries (including MOSS integrations) used to help detect copied solutions in assessments.



### Additional Strong Open-Source Options

- LeetCode-style practice platforms and problem sets that can be self-hosted or adapted for internal use.

- Secure sandbox projects (cgroup, seccomp, gVisor-based) for safe code execution.

- ATS integration examples and webhook patterns for connecting open assessment tools to hiring workflows.

- Question banks and problem generators maintained by communities.

- Replay and recording solutions for live interview sessions.



**Frameworks for building custom systems**: Deploy **CoderScreen**, **CodeVerdict**, or a **DMOJ**-based instance as the core platform, use **Judge0** (or a hardened sandbox) for code execution, and add collaborative editing for live interviews. Store results in your own database and integrate with your ATS via webhooks or APIs. This stack gives full control over questions, scoring logic, data privacy, and candidate experience while eliminating per-candidate SaaS fees — ideal for companies with technical capacity or strong privacy requirements.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Technical interview platforms process candidate data and influence hiring decisions. Open-source solutions provide transparency and data ownership but still require careful security hardening of code-execution sandboxes, fair assessment design, and compliance with employment and privacy regulations.

- Always design assessments that are job-relevant, accessible, and free from unnecessary bias.



---

**Made for engineering hiring teams, technical recruiters, and platform engineers building fair, high-signal interview processes.**

Let's make technical evaluation more open, self-hostable, and candidate-friendly.
