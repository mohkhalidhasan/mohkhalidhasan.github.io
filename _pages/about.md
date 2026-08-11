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

  /* ---------- Latest News ---------- */

  .home-news-section {
    clear: both;
    margin-top: 2rem;
  }

  .home-news-section h2 {
    margin-bottom: 1rem;
  }

  .news-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 0.85rem;
    margin: 0 0 1.8rem;
  }

  .news-card {
    display: flex;
    min-width: 0;
    flex-direction: column;
    overflow: hidden;
    background: var(--global-card-bg-color, transparent);
    border: 1px solid var(--global-divider-color, #d8d8d8);
    border-radius: 10px;
    color: var(--global-text-color);
    text-decoration: none !important;
    transition:
      transform 0.18s ease,
      box-shadow 0.18s ease,
      border-color 0.18s ease;
  }

  .news-card:hover {
    transform: translateY(-2px);
    border-color: var(--global-theme-color, #450084);
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.09);
    color: var(--global-text-color);
  }

  .news-media {
    position: relative;
    width: 100%;
    height: 118px;
    overflow: hidden;
    background: color-mix(
      in srgb,
      var(--global-theme-color, #450084) 8%,
      var(--global-bg-color, #ffffff)
    );
    border-bottom: 1px solid var(--global-divider-color, #d8d8d8);
  }

  .news-image {
    width: 100%;
    height: 100%;
    object-fit: cover;
    display: block;
  }

  .news-fallback {
    position: absolute;
    inset: 0;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 1rem;
    color: var(--global-theme-color, #450084);
    font-size: 0.82rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    text-transform: uppercase;
  }

  .news-content {
    display: flex;
    flex: 1;
    flex-direction: column;
    padding: 0.78rem 0.85rem 0.72rem;
  }

  .news-category {
    color: var(--global-theme-color, #450084);
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    margin-bottom: 0.28rem;
    text-transform: uppercase;
  }

  .news-card h3 {
    color: var(--global-text-color);
    font-size: 0.94rem;
    line-height: 1.35;
    margin: 0 0 0.38rem;
  }

  .news-card p {
    display: -webkit-box;
    overflow: hidden;
    -webkit-box-orient: vertical;
    -webkit-line-clamp: 3;
    font-size: 0.80rem;
    line-height: 1.45;
    margin: 0 0 0.65rem;
    opacity: 0.84;
  }

  .news-date {
    margin-top: auto;
    font-size: 0.68rem;
    font-weight: 600;
    opacity: 0.58;
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

    .news-media {
      height: 150px;
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
  <a class="home-action" href="{{ '/publications/' | relative_url }}">View Publications</a>
  <a class="home-action" href="{{ '/projects/' | relative_url }}">Current Projects</a>
  <a class="home-action" href="{{ '/people/' | relative_url }}">Research Group</a>
</div>

<div class="home-news-section">

<h2>Latest News</h2>

<div class="news-grid">
{% for item in site.data.news limit:6 %}

  {% assign link_first_four = item.link | slice: 0, 4 %}
  {% assign image_first_four = item.image | slice: 0, 4 %}

  <a
    class="news-card"
    href="{% if link_first_four == 'http' %}{{ item.link }}{% else %}{{ item.link | relative_url }}{% endif %}"
    {% if item.external %}target="_blank" rel="noopener noreferrer"{% endif %}
    data-preview-url="{{ item.preview_url | default: '' | escape }}"
    aria-label="{{ item.title | escape }}"
  >

    <div class="news-media">

      {% if item.image and item.image != "" %}

        <img
          class="news-image"
          src="{% if image_first_four == 'http' %}{{ item.image }}{% else %}{{ item.image | relative_url }}{% endif %}"
          alt=""
        >

      {% else %}

        <img
          class="news-image news-auto-image"
          src=""
          alt=""
          hidden
        >

        <div class="news-fallback">
          {{ item.category }}
        </div>

      {% endif %}

    </div>

    <div class="news-content">

      <div class="news-category">
        {{ item.category }}
      </div>

      <h3>{{ item.title }}</h3>

      <p>{{ item.description }}</p>

      <div class="news-date">
        {{ item.date }}
      </div>

    </div>

  </a>

{% endfor %}
</div>

</div>

<script>
document.addEventListener("DOMContentLoaded", function () {
  const cards = document.querySelectorAll(".news-card[data-preview-url]");

  cards.forEach(async function (card) {
    const previewUrl = card.dataset.previewUrl;
    const autoImage = card.querySelector(".news-auto-image");
    const fallback = card.querySelector(".news-fallback");

    if (!previewUrl || !autoImage) return;

    try {
      const endpoint =
        "https://api.microlink.io/?url=" +
        encodeURIComponent(previewUrl);

      const response = await fetch(endpoint);
      if (!response.ok) return;

      const result = await response.json();
      const imageUrl =
        result &&
        result.data &&
        result.data.image &&
        result.data.image.url;

      if (!imageUrl) return;

      autoImage.addEventListener("load", function () {
        autoImage.hidden = false;
        if (fallback) fallback.hidden = true;
      });

      autoImage.src = imageUrl;
    } catch (error) {
      /* Keep the category fallback if preview retrieval fails. */
    }
  });
});
</script>
{% endfor %}
</div>

</div>
