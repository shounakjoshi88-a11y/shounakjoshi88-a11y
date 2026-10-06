<img src="assets/masthead.svg" width="600" alt="Shounak Joshi — second-year CSE student building agentic AI systems, real-time web apps and engines from scratch">

Second-year **B.Tech CSE (AI &amp; ML)** at Ramdeobaba University, Nagpur.
I build agentic AI systems, real-time web apps, and engines written from
scratch — mostly TypeScript and Python, with C# when the real problem is a
renderer.

The thread through most of it: I care far less about whether a demo works on
my own laptop than about whether it still holds up when someone else runs it.

<p>
  <a href="https://x.com/BroIndian39416"><img src="https://img.shields.io/badge/X-000000?logo=x&logoColor=white&style=flat-square" alt="Shounak Joshi on X" width="90"></a>
  <a href="https://youtube.com/@A3-21-ShounakSamirkumarJoshi"><img src="https://img.shields.io/badge/YouTube-FF0000?logo=youtube&logoColor=white&style=flat-square" alt="Shounak Joshi on YouTube" width="104"></a>
  <a href="mailto:shounakjoshi88@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?logo=gmail&logoColor=white&style=flat-square" alt="Email Shounak Joshi at shounakjoshi88@gmail.com" width="104"></a>
  <a href="https://github.com/shounakjoshi88-a11y?tab=repositories"><img src="https://img.shields.io/badge/All_repositories-181717?logo=github&logoColor=white&style=flat-square" alt="Browse all repositories by Shounak Joshi" width="150"></a>
</p>

## Selected work

<a href="https://github.com/shounakjoshi88-a11y/Flux">
  <img src="assets/card-flux.svg" width="600" alt="Flux — agentic AI research companion built on Bun, Express 5, React 19 and PostgreSQL with pgvector">
</a>

- **[Flux](https://github.com/shounakjoshi88-a11y/Flux)** — a multi-model research
  companion built around a real agentic loop: plan the work, execute it under
  tool permissions, verify the result against criteria, retry what failed.
  Twenty-one registered tools, 1024-dimensional vector memory in pgvector,
  Python running in isolated Firecracker microVMs, a 3D knowledge graph, and
  a WebSocket agent protocol with team orchestration.
  <sub>[live](https://flux-weld-rho.vercel.app)</sub>

<a href="https://github.com/shounakjoshi88-a11y/stellar-forge">
  <img src="assets/card-stellar-forge.svg" width="600" alt="Stellar Forge — event platform with a scroll-driven 3D ticket-cut animation, built with React 19, Three.js and WebSocket">
</a>

- **[Stellar Forge](https://github.com/shounakjoshi88-a11y/stellar-forge)** — event
  management where the ticket gets cut by a falling pair of scissors driven by
  scroll position: the blades track the perforation, the thread runs out
  mid-cut, and what is left swings free. Seats are claimed in serialisable
  transactions, so two people cannot both take the last one.
  <sub>[live](https://stellar-forge-frontend.vercel.app/)</sub>

<a href="https://github.com/shounakjoshi88-a11y/de-ai">
  <img src="assets/card-de-ai.svg" width="600" alt="de-ai — a deterministic text rewriter that calls no language model, built with Python and FastAPI">
</a>

- **[de-ai](https://github.com/shounakjoshi88-a11y/de-ai)** — a text rewriter that
  deliberately calls no model at all. Same input, same output, every run. A
  blocklist of 600+ technical terms that the lexical pass may never touch
  exists because `server → waiter` and `self-attention → elf-attention` are
  exactly the class of bug a naive synonym swap creates. 156 assertions pin
  the behaviour so a fix cannot silently regress.

<a href="https://github.com/shounakjoshi88-a11y/meridian">
  <img src="assets/card-meridian.svg" width="600" alt="Meridian — clinical records and triage tool built with Python, Flask and pandas on real ICD-10-CM and HPO registries">
</a>

- **[Meridian](https://github.com/shounakjoshi88-a11y/meridian)** — clinical records and
  symptom triage under a hard constraint: only concepts from six lab
  practicals. No ORM because none was taught, no frontend framework for the
  same reason. Runs on the real 98,403-code ICD-10-CM registry and 11,655 HPO
  rare conditions, and refuses to write any condition whose code is not
  already in that registry.

## Also worth a look

- **[Raksha](https://github.com/shounakjoshi88-a11y/raksha-crowd-safety-hackathon)**
  — team lead for a Hackathon 2026 entry on safety at large public events.
  The argument: crushing pressure passes body to body before a guard notices
  anyone has stopped moving, so density and flow have to be measured rather
  than watched.
- **[60-login-page-challenge](https://github.com/shounakjoshi88-a11y/60-login-page-challenge)**
  — sixty distinct login screens in plain HTML and CSS, one style per week.
- **[c-practice](https://github.com/shounakjoshi88-a11y/c-practice)** — where the C and
  the data structures came from.

## Currently

*October 2026*

- **Voxelcraft** — a Minecraft-faithful voxel sandbox in Godot 4.7 and C#.
  Greedy meshing with smooth lighting and baked ambient occlusion,
  two-channel voxel light propagation, multithreaded chunk streaming, and
  every asset procedurally generated from scratch. Private until it is worth
  opening.
- Finishing the Raksha submission for Hackathon 2026.
- Trying to write more C and less JavaScript.

## Stack

Shipped work, not aspiration — the repositories are the evidence.

**Languages** — TypeScript, Python, JavaScript, C#, C

<img src="https://skillicons.dev/icons?i=ts,py,js,cs,c" alt="TypeScript, Python, JavaScript, C# and C" width="250">

**Runtime and data** — Bun, Express, PostgreSQL with pgvector, Prisma, React,
Tailwind, Three.js, GSAP

<img src="https://skillicons.dev/icons?i=bun,express,postgres,prisma,react,tailwind,threejs,gsap" alt="Bun, Express, PostgreSQL, Prisma, React, Tailwind CSS, Three.js and GSAP" width="450">

**Platform and tooling** — Supabase, Godot, Git, Linux, Docker

<img src="https://skillicons.dev/icons?i=supabase,godot,git,linux,docker" alt="Supabase, Godot, Git, Linux and Docker" width="280">

## Activity

<details>
<summary>Contribution history</summary>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/activity-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/activity-light.svg">
  <img src="assets/activity-light.svg" width="600" alt="Contribution activity over the last 53 weeks">
</picture>

Regenerated daily by <code>.github/workflows/activity.yml</code> and committed
straight into this repository, so it renders without any third-party image
service being up.

</details>

---

<sub>Every graphic here is a static SVG in <code>assets/</code> — no external
badge or stats service, so nothing on this page can break or rot. Both colour
themes are designed, not inverted, and the motion respects
<code>prefers-reduced-motion</code>.</sub>