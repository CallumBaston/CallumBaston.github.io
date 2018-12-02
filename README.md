# CallumBaston.github.io
This is the repo for my website

I'm using the Minimal-Mistakes template by Michel Rose.
Link to his GitHub: https://github.com/mmistakes
Link to the template: https://github.com/mmistakes/minimal-mistakes/


Im going to add this to pages later

`{% include base_path %}
{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}`
yeah boi
