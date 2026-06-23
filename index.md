---
layout: default
title: Home
---

<section class="hero">
  <div class="hero-copy">
    <p class="eyebrow">Antiquitt</p>
    <h1>Advanced mathematics, explained from first principles.</h1>
    <p class="intro">
      I make videos that build the fundamentals behind advanced mathematics, with a current focus on graph theory.
      I also write technical essays on Temporal.io, Go, and the engineering details behind reliable distributed systems.
    </p>
    <div class="actions">
      <a class="button primary" href="https://www.youtube.com/@Antiquitt">Watch on YouTube</a>
      <a class="button" href="#writing">Read essays</a>
      <a class="button" href="#cv">View CV</a>
    </div>
  </div>
  <aside class="research-note" aria-label="Current focus">
    <img src="{{ '/assets/img/graph-theory-figure.svg' | relative_url }}" alt="Graph theory figure with labeled vertices and edges">
    <span>Current Focus</span>
    <strong>Graph Theory</strong>
    <p>Vertices, edges, invariants, connectivity, walks, colorings, matchings, and the proof techniques that make the subject useful.</p>
  </aside>
</section>

<section class="section two-column" id="about">
  <div>
    <p class="section-label">About</p>
    <h2>Mathematics and systems, written carefully.</h2>
  </div>
  <div class="prose">
    <p>
      This site is a working archive for my public teaching and engineering writing. The mathematics side is centered on clear exposition:
      definitions, examples, proofs, and intuition that make advanced topics feel reachable without reducing their rigor.
    </p>
    <p>
      On the engineering side, I work with Temporal.io and Go. My writing will focus on useful implementation notes:
      workflow design, failure handling, worker behavior, testing, observability, and production patterns that are hard to learn from API references alone.
    </p>
  </div>
</section>

<section class="section" id="mathematics">
  <div class="section-heading">
    <p class="section-label">Mathematics Studio</p>
    <h2>Graph theory as a foundation.</h2>
  </div>
  <div class="card-grid three">
    <article class="note-card">
      <span class="tag">Series</span>
      <h3>Graph Theory Fundamentals</h3>
      <p>Definitions, examples, visual intuition, and proof patterns for core graph theory concepts.</p>
    </article>
    <article class="note-card">
      <span class="tag">Proofs</span>
      <h3>From Statement to Argument</h3>
      <p>How to read graph problems, choose invariants, and turn informal intuition into precise proofs.</p>
    </article>
    <article class="note-card">
      <span class="tag">Videos</span>
      <h3>Antiquitt on YouTube</h3>
      <p>Long-form explanations for learners who want depth, not shortcuts.</p>
      <a href="https://www.youtube.com/@Antiquitt">Open channel</a>
    </article>
  </div>
</section>

<section class="section" id="writing">
  <div class="section-heading">
    <p class="section-label">Technical Essays</p>
    <h2>Temporal.io and Go, from implementation experience.</h2>
  </div>
  <div class="writing-list">
    <article class="writing-row">
      <div>
        <span class="tag">Temporal.io</span>
        <h3>Workflow design notes</h3>
      </div>
      <p>Space for essays on workflow determinism, activities, retries, signals, queries, schedules, testing, and production debugging.</p>
    </article>
    <article class="writing-row">
      <div>
        <span class="tag">Go</span>
        <h3>Golang systems notes</h3>
      </div>
      <p>Space for practical writing on concurrency, context propagation, interfaces, error boundaries, testing, and maintainable service design.</p>
    </article>
    <article class="writing-row">
      <div>
        <span class="tag">Distributed Systems</span>
        <h3>Reliability patterns</h3>
      </div>
      <p>Space for bridging Temporal and Go: idempotency, timeouts, backpressure, observability, and failure-mode analysis.</p>
    </article>
  </div>
</section>

<section class="section two-column" id="cv">
  <div>
    <p class="section-label">CV</p>
    <h2>Curriculum vitae.</h2>
  </div>
  <div class="cv-panel">
    <p>
      A copy of my CV is available here for academic, collaboration, and professional context.
    </p>
    <a class="button primary" href="{{ '/assets/files/ayush-kumar-cv.pdf' | relative_url }}">Open CV</a>
  </div>
</section>

<section class="section" id="contact">
  <div class="section-heading">
    <p class="section-label">Links</p>
    <h2>Follow the work.</h2>
  </div>
  <div class="link-grid">
    <a href="https://www.youtube.com/@Antiquitt">YouTube: Antiquitt</a>
    <a href="https://github.com/AyushIITR007">GitHub: AyushIITR007</a>
    <a href="https://github.com/AyushIITR007/antiquit.io">Website repository</a>
  </div>
</section>
