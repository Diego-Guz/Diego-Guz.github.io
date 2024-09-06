---
layout: page
permalink: /teaching/
title: Teaching
# description: Materials for courses you taught. Replace this text with your description.
nav: true
nav_order: 6
---

<div class="courses-list">
    {% for course in site._courses %}
    <div class="course-item">
        ### {{ course.title }}
        **Term:** {{ course.term }}  
        **Location:** {{ course.location }}  
        **Details:**  
        {{ course.description }}
    </div>
    <hr/>
    {% endfor %}
</div>