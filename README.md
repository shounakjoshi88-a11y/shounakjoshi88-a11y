<img src="assets/hero.svg" width="680" alt="Shounak Joshi, BTech CSE with AI and ML at RCOEM, second year. Agentic AI systems, real-time web apps, engines written from scratch.">

Most of what I build ends up needing the unglamorous half of the job: making it
correct when two people reach the last seat at the same moment, when the font
is missing, when the thing finally runs on someone else's machine rather than
mine. That is the part I optimise for.

Everything below is shipped work, not a roadmap.

<p>
  <a href="https://github.com/shounakjoshi88-a11y/Flux"><strong>Flux</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/shounakjoshi88-a11y/stellar-forge"><strong>Stellar Forge</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/shounakjoshi88-a11y/de-ai"><strong>de-ai</strong></a> &nbsp;·&nbsp;
  <a href="https://github.com/shounakjoshi88-a11y/meridian"><strong>Meridian</strong></a> &nbsp;·&nbsp;
  <a href="https://x.com/BroIndian39416"><strong>X</strong></a> &nbsp;·&nbsp;
  <a href="https://youtube.com/@A3-21-ShounakSamirkumarJoshi"><strong>YouTube</strong></a> &nbsp;·&nbsp;
  <a href="mailto:shounakjoshi88@gmail.com"><strong>Email</strong></a>
</p>

<a href="https://github.com/shounakjoshi88-a11y?tab=repositories">
  <img src="assets/index.svg" width="680" alt="Index of selected work. 01 Flux, an agentic AI companion that plans, executes under tool permissions, verifies and retries. 02 Stellar Forge, an event platform whose ticket is cut by a scroll-driven pair of 3D scissors. 03 de-ai, a text rewriter that calls no model at all, with 156 assertions pinning the behaviour. 04 Meridian, clinical triage built only from six lab practicals on real ICD-10-CM data.">
</a>

## What the hard part was

**Flux** ran a plan, execute, verify, retry loop over 21 tools. Streaming meant
tool results and prose arrive interleaved, so the verifier had to judge results
it had not finished receiving. Memories are ranked and deduplicated by cosine
distance, and the ranking re-injects into later tool calls, which means a bad
extraction quietly poisons every answer after it.

**Stellar Forge** looks like a CRUD app with a 3D header. The 3D header is the
easy part. The hard part is that seat claims have to be race-safe across
concurrent users, so registration runs in serialisable transactions with row
locking, and the live counter is a single source of truth rather than whatever
each client last fetched.

**de-ai** was built to avoid the failure everyone else has. An LLM paraphraser is
non-deterministic, costs money per call, and quietly changes meaning. A rule bank
is none of those things, but it will happily turn `server` into `waiter`, so the
lexical pass is fenced off from a 600-term technical blocklist and the whole
pipeline re-scans its own output and reverts anything that introduced a new tell.

**Meridian** had a hard constraint: only concepts from six lab practicals. No ORM
because none was taught, no framework for the same reason. The interesting part is
what that forced, and the part I would not have guessed, which is that every
generator bug became a named regression test.

## Elsewhere

- **[Raksha](https://github.com/shounakjoshi88-a11y/raksha-crowd-safety-hackathon)**
  — team lead, Hackathon 2026, safety at large public events. The premise is that
  crushing pressure passes body to body before a guard notices anyone has stopped
  moving, so density and flow get measured rather than watched.
- **[60-login-page-challenge](https://github.com/shounakjoshi88-a11y/60-login-page-challenge)**
  — sixty login screens in plain HTML and CSS, one style per week.
- **[c-practice](https://github.com/shounakjoshi88-a11y/c-practice)** — where the C and
  the data structures came from.

## Currently

*October 2026*

- **Voxelcraft**, a Minecraft-faithful voxel sandbox in Godot 4.7 and C#. Greedy
  meshing with smooth lighting and baked ambient occlusion, two-channel voxel
  light propagation, multithreaded chunk streaming, every asset generated from
  scratch. Private until it is worth opening.
- Finishing the Raksha submission.
- Writing more C and less JavaScript.

## Stack

TypeScript · Python · JavaScript · C# · C · Bun · Express 5 · React · Tailwind ·
PostgreSQL with pgvector · Prisma · Three.js · GSAP · Supabase · Godot · Docker ·
Linux · Git

## Activity

<details>
<summary>Contribution history</summary>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/activity-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/activity-light.svg">
  <img src="assets/activity-light.svg" width="680" alt="Contribution activity across the last 53 weeks">
</picture>

Regenerated daily by <code>.github/workflows/activity.yml</code> and committed
into this repository, so it renders with no third-party service in the path.

</details>

---

<sub>Drawn as static SVG in <code>assets/</code> by me, not fetched from a badge
service, so nothing on this page can break or quietly rot. Both themes are
designed rather than inverted, contrast clears WCAG AA throughout, and the motion
collapses to nothing under <code>prefers-reduced-motion</code>.</sub>