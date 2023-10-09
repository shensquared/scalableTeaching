---
title: Upcoming - Spring 2024
description: Listing of course modules and topics.
nav_order: 0
#nav_exclude: true

---


{% for module in site.modules %}
{{ module }}

## `python` encoding of the dates/events

```py
{% include_relative /_modules/spring24.py %}
```
{% endfor %}

