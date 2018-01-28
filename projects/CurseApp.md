---
layout: page
title: CurseApp
permalink: /projects/CurseApp
---

This project seeks to build a curses widgeting library using python.  The
basic design is such that a curses UI can be sketched in an XML grammer,
then implemented at runtime by an application which uses the curseapp
library.

<ul class="post-list">
	{% for post in site.posts %}
	{% if  post.tags contains 'CurseApp' %}
      <li>
        <span class="post-meta">{{ post.date | date: "%Y-%m-%-d" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
        <div class="post-excerpt">{{ post.excerpt }}</div>
      </li>
	{% endif %}
    {% endfor %}
  </ul>

