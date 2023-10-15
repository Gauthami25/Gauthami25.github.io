---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
header:
  og_image: "projects/ecdf.png"
---


**Some of my projects that were fun to work on**



{% include base_path %}

{% assign ordered_pages = site.projects | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

<nbsp>

**My Data Journey**

🏁 **The beginnings**: A Boston Dynamics video of a robot dog named BigDog ignited my fascination with Electrical Engineering, setting the course for my under graduate degree. Growing up, understanding the "Whys" and "Hows" was important and and I was certain that this path was the right one.

🎓 **Undergrad Enlightenment**: College was an eye-opener. Here is where, Calculus, Statistics, Optimization, and Probability met reality and it became clear that these were crucial for real-world problem-solving.

🧑‍💼 **Internships**: My stint at Bosch in the consumer electronics division was a game-changer. It not only honed my Python, Computer Vision & Robotics skills but also empowered me to conduct independent research. The highlight of this experience was successfully crafting a working proof of concept of an autonomously docking lawnmower.

👩‍💼 **Full-time**: When I went back to Bosch, data was my jam. This time the focus was on supercharging analytics, crafting comprehensive customer reports and Ad-hoc reports. I ended up developing an in-house ETL toolchain, alongside automating tedious tasks, leading to massive performance improvements.

⭐ **Conclusion**: Making sense of huge amounts of Data wasn't exactly my childhood dream, it was a result of a lot of experimentation.

