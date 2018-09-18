---
title: Projects
layout: splash
permalink: /projects/
collection: projects
entries_layout: grid

excerpt: "Some of the projects"
header:
  overlay_image: "/assets/img/projects/Banner.jpg"
  overlay_filter: 0.1
  image_description: "A description of the image"
  caption: "Photo credit: [**Me**](https://unsplash.com)"
classes: wide

intro: 
  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'

---



{% if page.url != "/" and site.breadcrumbs %}
  {% unless paginator %}
    {% include breadcrumbs.html %}
  {% endunless %}
{% endif %}

---

{% include feature_row id="intro" type="center" %}



# Some Projects


This is the base Jekyll theme. You can find out more info about customizing your Jekyll theme, as well as basic Jekyll usage documentation at [jekyllrb.com](https://jekyllrb.com/)



<div class="entries-{{ page.entries_layout }}">
  {% include documents-collection.html collection=page.collection sort_by=page.sort_by sort_order=page.sort_order type=page.entries_layout %}
</div>