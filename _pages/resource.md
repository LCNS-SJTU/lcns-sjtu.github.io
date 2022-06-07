---
layout: page
permalink: /resources/
title: resources
description: Data and tools facilitate your research.
nav: true
nav_order: 3
---

## Data

---

<div class="resources">
<div class="card hoverable">
    <div class="row">
        <div class="col-sm-6 col-md-4 mb-auto mb-md-auto">
            <img src="{{ 'assets/img/allen.jpg' | relative_url }}" class="img-fluid rounded-circle" alt="{{ member.profile.name }}" />
        </div>
        <div class="col-sm-6 col-md-8 mb-auto mb-md-auto">
            <div class="card-body">
                {% if member.inline == false %}<a href="{{ member.url | relative_url }}">{% endif %}
                <h3 class="card-title">Allen Brain Observatory</h3>
                <hr>
                {% if member.profile.position %}<h6 class="card-subtitle mb-2 text-muted">{{ member.profile.position }}</h6>{% endif %}
                <p class="card-text">
                    This is data from Allen Brain Observatory.
                </p>
                {% if member.inline == false %}</a>{% endif %}
            </div>
        </div>
    </div>
</div>
</div>

<br/>

## Tools

---