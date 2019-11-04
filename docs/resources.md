---
layout: tabbed-assignment
---

# Resources

{% if site.data.assignment.slides %}
* [Presentation Slides][slides]
{% endif %}
{% if site.data.assignment.lesson %}
* [Lesson][]
{% endif %}
{% if site.data.assignment.template %}
* [Submission Template][template]
{% endif %}

<!-- Don't edit links here, change them in _data/assignment.yml instead, -->

[lesson]: <{{site.data.assignment.lesson}}>
[slides]: <{{site.data.assignment.slides}}>
[template]: <{{site.data.assignment.template}}>
