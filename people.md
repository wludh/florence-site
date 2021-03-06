---
layout: page
title: Historic Figures
---

## Painters
{% assign painters = (site.people | where:"category", "painter") %}
<div class="posts">
  {% for person in painters %}
  <article>
    {% if person.image %}
    <span><img src="{{ site.baseurl }}/assets/images/{{ person.image }}" width="100%" /></span>
    {% endif %}
    <div class="content">
      <h3>{{person.title}}</h3>
      {{ person.excerpt }}
      <ul class="actions">
        <li><a href="{{ person.url | absolute-url }}" class="button small">Continue</a></li>
      </ul>
    </div>
  </article>
  {% endfor %}
</div>

## Sculptors
{% assign sculptors = (site.people | where:"category", "sculptor") %}
<div class="posts">
  {% for person in sculptors %}
  <article>
    {% if person.image %}
    <span><img src="{{ site.baseurl }}/assets/images/{{ person.image }}" width="100%" /></span>
    {% endif %}
    <div class="content">
      <h3>{{person.title}}</h3>
      {{ person.excerpt }}
      <ul class="actions">
        <li><a href="{{ person.url | absolute-url }}" class="button small">Continue</a></li>
      </ul>
    </div>
  </article>
  {% endfor %}
</div>

## Patrons
{% assign patrons = (site.people | where:"category", "patron") %}
<div class="posts">
  {% for person in patrons %}
  <article>
    {% if person.image %}
    <span><img src="{{ site.baseurl }}/assets/images/{{ person.image }}" width="100%" /></span>
    {% endif %}
    <div class="content">
      <h3>{{person.title}}</h3>
      {{ person.excerpt }}
      <ul class="actions">
        <li><a href="{{ person.url | absolute_url }}" class="button small">Continue</a></li>
      </ul>
    </div>
  </article>
  {% endfor %}
</div>

## Politicians
{% assign politicians = (site.people | where:"category", "politician") %}
<div class="posts">
  {% for person in politicians %}
  <article>
    {% if person.image %}
    <span><img src="{{ site.baseurl }}/assets/images/{{ person.image }}" width="100%" /></span>
    {% endif %}
    <div class="content">
      <h3>{{person.title}}</h3>
      {{ person.excerpt }}
      <ul class="actions">
        <li><a href="{{ person.url | absolute_url }}" class="button small">Continue</a></li>
      </ul>
    </div>
  </article>
  {% endfor %}
</div>

<hr>

## Historians
{% assign historians = (site.people | where:"category", "historian") %}
<div class="posts">
  {% for person in historians %}
  <article>
    {% if person.image %}
    <span><img src="{{ site.baseurl }}/assets/images/{{ person.image }}" width="100%" /></span>
    {% endif %}
    <div class="content">
      <h3>{{person.title}}</h3>
      {{ person.excerpt }}
      <ul class="actions">
        <li><a href="{{ person.url | absolute_url }}" class="button small">Continue</a></li>
      </ul>
    </div>
  </article>
  {% endfor %}
</div>
