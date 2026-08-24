---
title: Members
nav:
  order: 2
  tooltip: About our team
---

<!-- # {% include icon.html icon="fa-solid fa-users" %}People -->

# Members

We are allwys looking for new students and researchers to join our group! Drop us a line to know more.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}


{% include section.html %}
{% include figure.html image="images/group_photo.jpg" width="85%" %}


{% include section.html %}
## Alumni

{% assign alumni_members = site.members | where: "group", "alumni" | sort: "left" | reverse %}
{% for member in alumni_members %}
{% include portrait.html
    name=member.name
    image=member.image
    role=member.role
    description=member.description
    left=member.left
    aliases=member.aliases
    links=member.links
    style="small"
  %}
{% endfor %}