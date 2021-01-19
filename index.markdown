---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

<section id="one" class="wrapper style1">
    <div class="inner">
        {% for post in site.posts %}
        <article class="feature left">
            <span class="image"><img src="{{ site.baseurl }}/images/pic01.jpg" alt="" /></span>
            <div class="content">
                <h2>{{ post.title }}</h2>
                <ul class="actions">
                    <li>
                        <a href="{{ site.baseurl }}/{{ post.url }}" class="button alt">More</a>
                    </li>
                </ul>
            </div>
        </article>
        {% endfor %}
    </div>
</section>

