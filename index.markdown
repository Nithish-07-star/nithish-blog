---
layout: default
---

<div class="hero">
  <p class="hero-label">WELCOME TO MY WEBSITE</p>

  <h1>Hi, I'm Nithish 👋</h1>

  <p class="tagline">
    Student • Developer • Learner
  </p>

  <p class="intro">
    I'm a student exploring technology, programming, and new ideas.
    This is where I document what I'm learning, the things I'm building,
    and the ideas I want to explore.
  </p>

  <div class="hero-buttons">
    <a href="{{ '/about/' | relative_url }}" class="button">
      About Me
    </a>

    <a href="#posts" class="button secondary">
      Explore My Posts ↓
    </a>
  </div>
</div>

<section class="interest-section">
  <h2>🚀 What I'm Exploring</h2>

  <div class="interest-grid">

    <div class="interest-card">
      <span class="interest-icon">🤖</span>
      <h3>Artificial Intelligence</h3>
      <p>
        Exploring AI, natural-language interfaces, and how intelligent
        systems can change the way we interact with computers.
      </p>
    </div>

    <div class="interest-card">
      <span class="interest-icon">💻</span>
      <h3>Computer Systems</h3>
      <p>
        Learning about operating systems, programming, automation,
        and the technology behind modern computers.
      </p>
    </div>

    <div class="interest-card">
      <span class="interest-icon">🛠️</span>
      <h3>Building Things</h3>
      <p>
        Turning ideas into projects while learning new tools,
        technologies, and development workflows.
      </p>
    </div>

  </div>
</section>

<section class="posts-section" id="posts">

  <div class="section-heading">
    <div>
      <p class="section-label">MY JOURNEY</p>
      <h2>📝 Latest Posts</h2>
    </div>

    <span class="post-count">
      {{ site.posts | size }} post{% if site.posts.size != 1 %}s{% endif %}
    </span>
  </div>

  <div class="posts">

    {% for post in site.posts %}

      <article class="post-card">

        <p class="post-date">
          {{ post.date | date: "%B %-d, %Y" }}
        </p>

        <h3>
          <a href="{{ post.url | relative_url }}">
            {{ post.title }}
          </a>
        </h3>

        {% if post.excerpt %}
          <p>
            {{ post.excerpt | strip_html | truncate: 180 }}
          </p>
        {% endif %}

        <a class="read-more" href="{{ post.url | relative_url }}">
          Read article →
        </a>

      </article>

    {% endfor %}

  </div>

</section>

<section class="final-cta">

  <h2>Still learning. Still building. 🚀</h2>

  <p>
    Follow along as I document my journey through technology,
    programming, and the ideas I'm exploring.
  </p>

  <a href="{{ '/about/' | relative_url }}" class="button">
    Learn More About Me
  </a>

</section>