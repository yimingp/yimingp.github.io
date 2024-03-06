---
layout: page
title: Contact
permalink: /contact/
weight: 4
---

<div class="">

  {%- assign unfocused_color = "6c757d" -%}

<ul class="contact-list">

  {% for account in site.author %}


    {%- assign service_name = account[0] -%}
    {%- assign service_data = site.data.social-media[service_name] -%}
    {%- if service_data -%}    
    <li class="contact-list-item">
    <a class="social mx-1"  href="{{ service_data.url }}{{ account[1] }}"
       style="color: #{{ unfocused_color }}"
       onMouseOver="this.style.color='#{{ service_data.color }}'"
       onMouseOut="this.style.color='#{{ unfocused_color }}'">
      <i class="{{ service_data.icon }} fa-3x"></i>
    </a>
    <p>{{ account[1] }}</p>
    </li>
    {%- endif -%}
  
  {% endfor %}

</ul>

</div>

<style>

.contact-list{
    list-style-type: none;
}

.contact-list-item{
    padding:2.5%;
}

.contact-list-item p{
    display:inline;
}

</style>