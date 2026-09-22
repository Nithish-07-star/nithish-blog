---
layout: default
---

<div class="hero">
  <h1>Hi, I'm Nithish 👋</h1>

  <p class="tagline">
    Student • Developer • Learner
  </p>

  <p class="intro">
    Welcome to my little corner of the internet.
    I write about what I'm learning, the projects I'm building,
    and my journey as a student.
  </p>

  <div class="hero-buttons">
    <a href="{{ '/about/' | relative_url }}" class="button">
      About Me
    </a>

    <a href="{{ '/feed.xml' | relative_url }}" class="button secondary">
      RSS Feed
    </a>
  </div>
</div>

<hr>

<h2>📝 Latest Posts</h2>

<div class="posts">
  {% for post in site.posts %}
    <article class="post-card">
      <h3>
        <a href="{{ post.url | relative_url }}">
          {{ post.title }}
        </a>
      </h3>

      <p class="post-date">
        {{ post.date | date: "%B %-d, %Y" }}
      </p>

      {% if post.excerpt %}
        <p>{{ post.excerpt | strip_html | truncate: 160 }}</p>
      {% endif %}

      <a href="{{ post.url | relative_url }}">
        Read more →
      </a>
    </article>
  {% endfor %}
</div>
