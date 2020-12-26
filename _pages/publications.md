---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<!---
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

--->

<!-- This div is a placeholder which will contain the publications -->
<div id="pubszone">
  Loading publications...
</div>
<!-- Function which will handle the content received through JSONP -->
<script type='text/javascript'>
    function mycallback(ad_content) {
    	document.getElementById('pubszone').innerHTML = ad_content.html;
    }
</script>
<!-- Load of the remote JS which will call the callback function -->
<script src="https://www.csauthors.net/matthias-lindemann/embed/bib.js?callback=mycallback"></script>

