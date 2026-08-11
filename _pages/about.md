---
layout: about
title: About
permalink: /
nav: false
nav_order: 1

subtitle: Assistant Professor of Computer Science · James Madison University

profile:
  align: right
  image: prof_pic.jpeg
  image_circular: false

selected_papers: false
social: true

announcements:
  enabled: false
  scrollable: false
  limit: 4

latest_posts:
  enabled: false
  scrollable: false
  limit: 3
---

<style>
  .profile-clear {
    clear: both;
  }

  .research-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
    margin: 1.5rem 0;
  }

  .research-card {
    background: var(--global-card-bg-color, transparent);
    border: 1px solid var(--global-divider-color, #d6d6d6);
    border-radius: 12px;
    padding: 1.2rem;
    transition:
      transform 0.2s ease,
      box-shadow 0.2s ease;
  }

  .research-card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.12);
  }

  .research-card h3 {
    color: var(--global-theme-color, #450084);
    font-size: 1.05rem;
    line-height: 1.35;
    margin: 0 0 0.6rem;
  }

  .research-card p {
    font-size: 0.93rem;
    line-height: 1.55;
    margin: 0;
  }

  .home-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.75rem;
    margin: 1.25rem 0 2rem;
  }

  .home-action {
    border: 1px solid var(--global-theme-color, #450084);
    border-radius: 7px;
    padding: 0.55rem 0.9rem;
    font-size: 0.9rem;
    font-weight: 500;
    text-decoration: none;
    transition:
      background-color 0.2s ease,
      color 0.2s ease;
  }

  .home-action:hover {
    background: var(--global-theme-color, #450084);
    color: #ffffff;
    text-decoration: none;
  }

  .social .contact-icons {
    font-size: 2rem;
  }

  .social .contact-icons a {
    margin: 0 0.3rem;
  }

  .social .contact-note {
    font-size: 0.9rem;
    margin-top: 0.7rem;
  }

  /* Homepage news */
  .home-news-section {
    clear: both;
    margin-top: 2.3rem;
  }

  .home-news-section h2 {
    margin-bottom: 1.25rem;
  }

  .news-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
    margin: 0 0 2rem;
  }

  .news-card {
    display: flex;
    flex-direction: column;
    min-height: 100%;
    overflow: hidden;
    background: var(--global-card-bg-color, transparent);
    border: 1px solid var(--global-divider-color, #d8d8d8);
    border-radius: 12px;
    color: var(--global-text-color);
    text-decoration: none !important;
    transition:
      transform 0.2s ease,
      box-shadow 0.2s ease,
      border-color 0.2s ease;
  }

  .news-card:hover {
    transform: translateY(-3px);
    border-color: var(--global-theme-color, #450084);
    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.10);
    color: var(--global-text-color);
  }

  .news-image-wrap {
    width: 100%;
    aspect-ratio: 16 / 7;
    overflow: hidden;
    border-bottom: 1px solid var(--global-divider-color, #d8d8d8);
  }

  .news-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

  .news-category-banner {
    display: flex;
    align-items: center;
    justify-content: center;
    min-height: 105px;
    padding: 1rem;
    background: color-mix(
      in srgb,
      var(--global-theme-color, #450084) 12%,
      transparent
    );
    border-bottom: 1px solid var(--global-divider-color, #d8d8d8);
    color: var(--global-theme-color, #450084);
    font-size: 1rem;
    font-weight: 700;
    letter-spacing: 0.03em;
    text-transform: uppercase;
  }

  .news-content {
    display: flex;
    flex: 1;
    flex-direction: column;
    padding: 1rem 1.05rem 0.9rem;
  }

  .news-category {
    color: var(--global-theme-color, #450084);
    font-size: 0.74rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    margin-bottom: 0.35rem;
    text-transform: uppercase;
  }

  .news-card h3 {
    color: var(--global-text-color);
    font-size: 1.02rem;
    line-height: 1.4;
    margin: 0 0 0.5rem;
  }

  .news-card p {
    font-size: 0.88rem;
    line-height: 1.55;
    margin: 0 0 1rem;
    opacity: 0.9;
  }

  .news-date {
    margin-top: auto;
    font-size: 0.78rem;
    font-weight: 600;
    opacity: 0.65;
    text-align: right;
    text-transform: uppercase;
  }

  @media (min-width: 700px) {
    .profile {
      width: 28%;
      max-width: 285px;
    }
  }

  @media (max-width: 1000px) {
    .news-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 760px) {
    .research-grid {
      grid-template-columns: 1fr;
    }

    .profile {
      float: none !important;
      width: 100%;
      max-width: 280px;
      margin: 0 auto 1.5rem !important;
    }
  }

  @media (max-width: 700px) {
    .news-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

I am an Assistant Professor in the Department of Computer Science at James Madison University. My research lies at the intersection of wireless communications and cybersecurity, with particular interests in federated learning, secure and trustworthy machine learning, wireless and networked systems, and security for UAV and IoT environments.

My work examines how intelligent and distributed systems behave under adversarial conditions and how practical defenses can be developed for real-world, resource-constrained environments. Please feel free to email me with questions or to discuss potential research collaborations.

<div class="profile-clear"></div>

## Research Focus

<div class="research-grid">

  <div class="research-card">
    <h3>Wireless Communications</h3>
    <p>
      Secure and efficient communication for next-generation wireless,
      cognitive radio, spectrum sharing, and networked systems.
    </p>
  </div>

  <div class="research-card">
    <h3>Secure and Trustworthy AI</h3>
    <p>
      Federated learning, adversarial threats, poisoning attacks, and
      practical defenses for distributed machine learning.
    </p>
  </div>

  <div class="research-card">
    <h3>UAV, IoT, and Cyber-Physical Systems</h3>
    <p>
      Security and resilience for autonomous, resource-constrained, and
      highly distributed computing environments.
    </p>
  </div>

</div>

<div class="home-actions">
  <a class="home-action" href="{{ '/publications/' | relative_url }}">
    View Publications
  </a>

  <a class="home-action" href="{{ '/projects/' | relative_url }}">
    Current Projects
  </a>

  <a class="home-action" href="{{ '/people/' | relative_url }}">
    Research Group
  </a>
</div>

<div class="home-news-section">

<h2>Latest News</h2>

<div class="news-grid">
{% for item in site.data.news limit:6 %}

  {% assign first_four = item.link | slice: 0, 4 %}

  <a
    class="news-card"
    href="{% if first_four == 'http' %}{{ item.link }}{% else %}{{ item.link | relative_url }}{% endif %}"
    {% if item.external %}target="_blank" rel="noopener noreferrer"{% endif %}
    aria-label="{{ item.title }}"
  >

    {% if item.image and item.image != "" %}

      <div class="news-image-wrap">
        <img
          src="{{ item.image | relative_url }}"
          alt=""
          class="news-image"
        >
      </div>

    {% else %}

      <div class="news-category-banner">
        {{ item.category }}
      </div>

    {% endif %}

    <div class="news-content">

      <div class="news-category">
        {{ item.category }}
      </div>

      <h3>
        {{ item.title }}
      </h3>

      <p>
        {{ item.description }}
      </p>

      <div class="news-date">
        {{ item.date }}
      </div>

    </div>

  </a>

{% endfor %}
</div>

</div>
