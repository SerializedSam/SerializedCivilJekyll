---
layout: full-width
title: Archive
nav_include: true
---

## Tags
{{ site | tag_cloud }}


## Posts
<section class="posts">
     {% for post in site.posts %}
     <time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%Y-%m-%d" }}</time>
        <a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a>
    <span>
        {% if post.tags.size > 0 %}
            {% assign sorted_tags = post.tags | sort %}
            •
            {% for tag in sorted_tags %}
                    <a href="/{{ site.tag_page_dir }}/{{ tag | slugify: 'pretty' }}/" style="padding: 4px;">{{ tag }}</a>
            {% endfor %}
        {% endif %}
    </span>
    <br>
    {% endfor %}
</section>
