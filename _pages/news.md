---
layout: page
title: News
permalink: /news/
nav: false
description: Research news, publications, grants, awards, invited activities, and professional service.
---

<style>
  .news-archive-intro {
    font-size: 1rem;
    line-height: 1.65;
    margin-bottom: 1.5rem;
  }

  .news-archive-grid {
    display: grid;
    grid-template-columns: repeat(3, minmax(0, 1fr));
    gap: 1rem;
  }

  .archive-news-card {
    display: flex;
    flex-direction: column;
    border: 1px solid var(--global-divider-color, #d8d8d8);
    border-radius: 10px;
    overflow: hidden;
    color: var(--global-text-color);
    text-decoration: none !important;
    background: var(--global-card-bg-color, transparent);
    transition:
      transform 0.18s ease,
      box-shadow 0.18s ease,
      border-color 0.18s ease;
  }

  .archive-news-card:hover {
    transform: translateY(-2px);
    border-color: var(--global-theme-color, #450084);
    box-shadow: 0 6px 16px rgba(0, 0, 0, 0.09);
    color: var(--global-text-color);
  }

  .archive-news-content {
    display: flex;
    flex-direction: column;
    flex: 1;
    padding: 1rem;
  }

  .archive-news-category {
    color: var(--global-theme-color, #450084);
    font-size: 0.7rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    margin-bottom: 0.35rem;
  }

  .archive-news-card h3 {
    color: var(--global-text-color);
    font-size: 1rem;
    line-height: 1.4;
    margin: 0 0 0.5rem;
  }

  .archive-news-card p {
    font-size: 0.86rem;
    line-height: 1.55;
    margin: 0 0 0.8rem;
    opacity: 0.85;
  }

  .archive-news-date {
    margin-top: auto;
    text-align: right;
    font-size: 0.72rem;
    font-weight: 600;
    opacity: 0.6;
    text-transform: uppercase;
  }

  @media (max-width: 1000px) {
    .news-archive-grid {
      grid-template-columns: repeat(2, minmax(0, 1fr));
    }
  }

  @media (max-width: 700px) {
    .news-archive-grid {
      grid-template-columns: 1fr;
    }
  }
</style>

<div class="news-archive-intro">
Research news, publications, grants, awards, invited activities, and professional service.
</div>

<div class="news-archive-grid">

{% for item in site.data.news %}

  {% assign news_link = item.link | default: "" %}
  {% assign link_first_four = news_link | slice: 0, 4 %}

  <a
    class="archive-news-card"
    href="{% if link_first_four == 'http' %}{{ news_link }}{% else %}{{ news_link | relative_url }}{% endif %}"
    {% if item.external %}
      target="_blank"
      rel="noopener noreferrer"
    {% endif %}
    aria-label="{{ item.title | escape }}"
  >

    <div class="archive-news-content">

      <div class="archive-news-category">
        {{ item.category }}
      </div>

      <h3>
        {{ item.title }}
      </h3>

      <p>
        {{ item.description }}
      </p>

      <div class="archive-news-date">
        {{ item.date }}
      </div>

    </div>

  </a>

{% endfor %}

</div>
