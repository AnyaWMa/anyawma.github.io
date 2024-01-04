---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
*These authors contributed equally to this work

# Journal Papers
Tran, J. E.*, Yeatman, J. D.*, Burkhardt, A., Ma, W. A., Mitchell, J., Yablonski, M., Townley-Flores, C., Richie-Halford, A. (2023, December 1).    Development and validation of a rapid online sentence reading efficiency assessment. [Prepint](https://doi.org/10.31219/osf.io/u3mjz)


# Peer-Reviewed Conference Proceedings


# Conference Presentations


# Software



{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
