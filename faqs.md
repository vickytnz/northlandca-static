---
layout: page
title: Frequently asked questions (FAQs)

related: templates_related
---

{% capture accordion_content %}
This is my content that I want to include in my accordion.

- List item 1
- List item 2

Some more text _here_ too.

{% endcapture %}

{% include accordion.html title="Question" content=accordion_content %}



{% capture accordion_content2 %}
This is my content that I want to include in my accordion.

- List item 1
- List item 2

Some more text _here_ too.

{% endcapture %}

{% include accordion.html title="Frequently asked question" content=accordion_content2 %}

{% capture accordion_content3 %}
This is my content that I want to include in my accordion.

- List item 1
- List item 2

Some more text _here_ too.

{% endcapture %}

{% include accordion.html title="A question" content=accordion_content3 %}

{% capture accordion_content4 %}
This is my content that I want to include in my accordion.

- List item 1
- List item 2

Some more text _here_ too.

{% endcapture %}

{% include accordion.html title="Another question" content=accordion_content4 %}


{% capture accordion_content5 %}
This is my content that I want to include in my accordion.

- List item 1
- List item 2

Some more text _here_ too.

{% endcapture %}

{% include accordion.html title="FAQ" content=accordion_content5 %}


{% capture accordion_content6 %}
This is my content that I want to include in my accordion.

- List item 1
- List item 2

Some more text _here_ too.

{% endcapture %}

{% include accordion.html title="Question" content=accordion_content6 %}
