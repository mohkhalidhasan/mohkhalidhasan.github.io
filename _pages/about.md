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

selected_papers: true
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
    border: 1px solid var(--global-divider-color, #777);
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

  @media (min-width: 700px) {
    .profile {
      width: 28%;
      max-width: 285px;
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
</style>

I am an Assistant Professor in the Department of Computer Science at James Madison University. My research lies at the intersection of wireless communications and cybersecurity, with particular interests in federated learning, secure and trustworthy machine learning, wireless and networked systems, and security for UAV and IoT environments.

My work examines how intelligent and distributed systems behave under adversarial conditions and how practical defenses can be developed for real-world, resource-constrained environments. I also involve undergraduate students in applied research projects spanning cybersecurity, machine learning, and emerging networked systems.

<div class="profile-clear"></div>

## Research Focus

<div class="research-grid">

  <div class="research-card">
    <h3>Wireless Communications</h3>
    <p>
      Secure and efficient communication for next-generation wireless,
      cognitive radio, spectrum-sharing, and networked systems.
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
    Projects &amp; Grants
  </a>

  <a class="home-action" href="{{ '/people/' | relative_url }}">
    Research Group
  </a>
</div>

<!-----
layout: about
title: about
permalink: /
subtitle: <a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>555 your office number</p>
    <p>123 your address street</p>
    <p>Your City, State 12345</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: true
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](https://www.reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them.-->
