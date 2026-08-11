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

  /* =========================
     Research Focus
     ========================= */

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

  .news-more {
  margin-top: 0.4rem;
  margin-bottom: 2rem;
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

  /* =========================
     Social Links
     ========================= */

  .social .contact-icons {
    font-size: 2rem;
  }

  .social .contact-icons a {
    margin: 0 0.3rem;
  }

  /* =========================
     Latest News
     ========================= */

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
    flex-direction: column;
    min-width: 0;
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

  /* ---------- News cover ---------- */

  .news-media {
    position: relative;
    width: 100%;
    height: 112px;
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
    object-position: center;
  }

  .news-image[hidden] {
    display: none !important;
  }

  /* Displayed only when no usable image is available */

  .news-fallback {
    position: absolute;
    inset: 0;

    display: flex;
    align-items: center;
    justify-content: center;

    padding: 1rem;

    color: var(--global-theme-color, #450084);
    font-size: 0.78rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    text-transform: uppercase;

    background: color-mix(
      in srgb,
      var(--global-theme-color, #450084) 7%,
      var(--global-bg-color, #ffffff)
    );
  }

  .news-fallback[hidden] {
    display: none !important;
  }

  /* ---------- News text ---------- */

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

    font-size: 0.8rem;
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

  /* =========================
     Responsive Layout
     ========================= */

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
      height: 145px;
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

  <a
    class="home-action"
    href="{{ '/publications/' | relative_url }}"
  >
    View Publications
  </a>

  <a
    class="home-action"
    href="{{ '/projects/' | relative_url }}"
  >
    Current Projects
  </a>

  <a
    class="home-action"
    href="{{ '/people/' | relative_url }}"
  >
    Research Group
  </a>

</div>

<div class="home-news-section">

<h2>Latest News</h2>

<div class="news-grid">

{% for item in site.data.news limit:6 %}

  {% assign news_link = item.link | default: "" %}
  {% assign news_image = item.image | default: "" %}
  {% assign preview_url = item.preview_url | default: "" %}

  {% assign link_first_four = news_link | slice: 0, 4 %}
  {% assign image_first_four = news_image | slice: 0, 4 %}

  {% if news_image != "" %}

    {% if image_first_four == "http" %}
      {% assign manual_image_url = news_image %}
    {% else %}
      {% assign manual_image_url = news_image | relative_url %}
    {% endif %}

  {% else %}

    {% assign manual_image_url = "" %}

  {% endif %}

  <a
    class="news-card"
    href="{% if link_first_four == 'http' %}{{ news_link }}{% else %}{{ news_link | relative_url }}{% endif %}"
    {% if item.external %}
      target="_blank"
      rel="noopener noreferrer"
    {% endif %}
    data-manual-image="{{ manual_image_url | escape }}"
    data-preview-url="{{ preview_url | escape }}"
    aria-label="{{ item.title | escape }}"
  >

    <div class="news-media">

      <img
        class="news-image"
        src=""
        alt=""
        hidden
      >

      <div class="news-fallback">
        {{ item.category }}
      </div>

    </div>

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

<div class="news-more">
  <a class="home-action" href="{{ '/news/' | relative_url }}">
    View All News
  </a>
</div>

</div>

<script>
document.addEventListener("DOMContentLoaded", function () {

  const cards = document.querySelectorAll(".news-card");

  cards.forEach(function (card) {

    const manualImageUrl = card.dataset.manualImage || "";
    const previewUrl = card.dataset.previewUrl || "";

    const visibleImage = card.querySelector(".news-image");
    const fallback = card.querySelector(".news-fallback");

    const sources = [];

    /*
     * Priority 1:
     * Use an image uploaded by you.
     */
    if (manualImageUrl) {
      sources.push(manualImageUrl);
    }

    /*
     * Priority 2:
     * If no uploaded image works, try to retrieve the
     * representative image from the external page.
     */
    if (previewUrl) {

      const encodedUrl = encodeURIComponent(previewUrl);

      const representativeImage =
        "https://api.microlink.io/?url=" +
        encodedUrl +
        "&embed=image.url";

      const pageScreenshot =
        "https://api.microlink.io/?url=" +
        encodedUrl +
        "&screenshot=true" +
        "&meta=false" +
        "&embed=screenshot.url";

      sources.push(representativeImage);
      sources.push(pageScreenshot);
    }

    /*
     * If there is no uploaded image and no preview URL,
     * simply keep the category fallback visible.
     */
    if (sources.length === 0) {
      return;
    }

    function tryImage(index) {

      /*
       * Every candidate failed.
       * Keep the clean category fallback.
       */
      if (index >= sources.length) {

        visibleImage.hidden = true;

        if (fallback) {
          fallback.hidden = false;
        }

        return;
      }

      /*
       * Test the image before placing it in the visible card.
       * This prevents broken-image icons from appearing.
       */
      const tester = new Image();

      tester.onload = function () {

        visibleImage.src = sources[index];
        visibleImage.hidden = false;

        if (fallback) {
          fallback.hidden = true;
        }

      };

      tester.onerror = function () {

        tryImage(index + 1);

      };

      tester.src = sources[index];
    }

    tryImage(0);

  });

});
</script>
