---
layout: page
title: Teaching
permalink: /teaching/
nav: true
nav_order: 6
description: Courses taught in computing, digital systems, machine learning, and electronics.
---

<style>
  .teaching-intro {
    font-size: 1.02rem;
    line-height: 1.7;
    margin-bottom: 1.75rem;
  }

  .course-grid {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    margin: 1rem 0 2rem;
  }

  .course-card {
    background: var(--global-card-bg-color, transparent);
    border: 1px solid var(--global-divider-color, #d8d8d8);
    border-radius: 12px;
    padding: 1.15rem 1.2rem;
    transition:
      transform 0.2s ease,
      box-shadow 0.2s ease;
  }

  .course-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.10);
  }

  .course-code {
    color: var(--global-theme-color, #450084);
    font-size: 0.85rem;
    font-weight: 700;
    letter-spacing: 0.04em;
    margin-bottom: 0.25rem;
    text-transform: uppercase;
  }

  .course-card h3 {
    font-size: 1.08rem;
    line-height: 1.35;
    margin: 0 0 0.45rem;
  }

  .course-meta {
    font-size: 0.88rem;
    line-height: 1.5;
    margin-bottom: 0.65rem;
    opacity: 0.8;
  }

  .course-card p {
    font-size: 0.94rem;
    line-height: 1.55;
    margin: 0;
  }

  .teaching-note {
    border-left: 4px solid var(--global-theme-color, #450084);
    margin: 1.5rem 0 0;
    padding: 0.2rem 0 0.2rem 1rem;
  }

  @media (max-width: 760px) {
    .course-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="teaching-intro">
My teaching spans computing foundations, digital systems, electronics, and applied machine learning. Across these courses, I emphasize the connection between core concepts, hands-on implementation, and practical problem solving.
</div>

## James Madison University

<div class="course-grid">

  <div class="course-card">
    <div class="course-code">IT 201</div>
    <h3>Computational Structures and Logic</h3>
    <div class="course-meta">Undergraduate · Lecture and Laboratory · Fall 2025, Spring 2026</div>
    <p>
      Introduces foundational computational structures and logical reasoning through
      a combination of conceptual instruction and hands-on laboratory work.
    </p>
  </div>

  <div class="course-card">
    <div class="course-code">IT 212</div>
    <h3>Digital Electronics</h3>
    <div class="course-meta">Undergraduate · Lecture and Laboratory · Spring 2026</div>
    <p>
      Covers core concepts in digital electronics and reinforces them through
      laboratory-based design, implementation, and testing activities.
    </p>
  </div>

</div>

## Previous Teaching Experience

<div class="course-grid">

  <div class="course-card">
    <div class="course-code">EE/CPE/AAI 595</div>
    <h3>Applied Machine Learning</h3>
    <div class="course-meta">Graduate · Stevens Institute of Technology · Fall 2024, Spring 2025</div>
    <p>
      Graduate-level instruction in applied machine learning, with emphasis on
      practical model development, evaluation, and problem-driven use of learning methods.
    </p>
  </div>

  <div class="course-card">
    <div class="course-code">ENGR 232 / ENGR 212</div>
    <h3>Analog Circuits Laboratories</h3>
    <div class="course-meta">Undergraduate · Stevens Institute of Technology · Jan. 2022–May 2024</div>
    <p>
      Served as a graduate teaching assistant and lead laboratory instructor for
      undergraduate analog circuits courses.
    </p>
  </div>

  <div class="course-card">
    <div class="course-code">Basic Electronic Circuits I</div>
    <h3>Laboratory Instruction</h3>
    <div class="course-meta">Undergraduate · Kookmin University · Sep.–Dec. 2019</div>
    <p>
      Supported laboratory instruction in introductory electronic circuits,
      including experimental setup, measurement, and circuit analysis.
    </p>
  </div>

</div>

<div class="teaching-note">
Course materials for currently enrolled students are provided through the university learning-management system.
</div>
