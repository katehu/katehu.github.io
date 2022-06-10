---
layout: page-home
permalink: /research/index.html
title: Research
description: Research
tags: 
imagefeature: fourseasons.jpg
chart: true
---
{% for post in site.posts %}
{% if post.category == 'research' %}
<article class="notepad-index-post post row">
    <div class="small-12 medium-3 large-2 columns datetime">
        <span class="notepad-post-meta">
            <time datetime="{{ post.date | date_to_xmlschema }}">
                <span class="day">
                    {{ post.date | date: "%d" }}
                </span>
                <span class="month-year">
                    {{ post.date | date: "%B %Y" }}
                </span>
            </time>
        </span>
    </div>
    <div class="small-12 medium-9 large-10 columns">
        <header class="notepad-post-header">
            <h3 class="notepad-post-title">
                <a href="{{ site.url }}{{ post.url }}">
                    {{ post.title }}
                </a>
            </h3>
        </header>
        <section class="notepad-post-excerpt">
            <p>{{ post.content | strip_html | truncatewords:100 }}</p>
        </section>
        
            <div class="notepad-index-post-tags">
            {% for tag in post.categories %}<a href="{{ site.url }}/categories/index.html#{{ post.categories | cgi_encode }}" title="Other posts from the {{ tag | capitalize }} category">{{ tag | capitalize }}</a>{% unless forloop.last %}&nbsp;{% endunless %}{% endfor %}
                
            </div>
        
    </div>
</article>
{% endif %}
{% endfor %}  
