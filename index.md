---

layout: default
title : Technology Awesomeness

---

Hey everybody! Welcome to the the **Technology Awesomeness** page for the [Scholars' Academy][sa]. I am super excited that you've decided to stop by. The goal is that this page will grow to be a most excellent resource for anything you want to know about the metric ton of technological resources at the schools. For now, we are at the humble beginings. That said, it's my goal that things will grow at an exponential rate. Stay tuned.

[sa]: http://scholarsnyc.com/ "The Scholar's Academy"

{% for post in site.posts %}
* [{{post.title}}]({{post.url}})
{% endfor %}