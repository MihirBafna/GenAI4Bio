---
layout: page
title: Staff
description: A listing of all the course staff members.
---

# Staff

---

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign head_tas = teaching_assistants | where: 'headta', true %}
{% assign supporting_tas = teaching_assistants | where_exp: 'ta', 'ta.headta != true' | sort: 'name' %}
{% assign num_teaching_assistants = teaching_assistants | size %}

<div class="staff-groups">
  <div class="staff-group">
    <h2>Instructors</h2>

    {% for staffer in instructors %}
    {{ staffer }}
    {% endfor %}
  </div>

  {% if num_teaching_assistants != 0 %}
  <div class="staff-group">
    <h2>Teaching Assistants</h2>

    {% for staffer in head_tas %}
    {{ staffer }}
    {% endfor %}
    {% for staffer in supporting_tas %}
    {{ staffer }}
    {% endfor %}
  </div>
  {% endif %}
</div>
