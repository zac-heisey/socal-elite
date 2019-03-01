---
title: Sitemap
layout: page
---

<!-- Sitemap Page -->
<section id="sitemap">
    <div class="container">
        <div class="row">
            <div class="col-lg-12">
              <a href="/">⬅️ Back to SoCal Elite Physical Therapy</a>
                <h2 class="section-heading">Sitemap</h2>
                <h3 class="section-subheading text-muted">Pages</h3>
                <ul>
                  <li><a href="/blog">Blog</a></li>
                  {% for page in site.pages %}
                  {% if page.title and page.title != "Irvine Physical Therapy Resources, Tips, and More" and page.title != "Thank You" %}
                  <li>
                    <a href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a>
                  </li>
                  {% endif %}
                  {% endfor %}
                  {% for page in site.team-members %}
                  <li>
                    <a href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a>
                  </li>
                  {% endfor %}
                </ul>
                <h3 class="section-subheading text-muted">Blog Posts</h3>
                <ul>
                  {% for post in site.categories.blog %}
                    <li>
                      <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
                    </li>
                  {% endfor %}
                </ul>
            </div>
        </div>
    </div>
</section>
