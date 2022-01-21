---
title: Visualizing Your Data
nav: Visualize
permalink: /visualize.html
order: 4
---


# Use the graphs in your project website to explore your data

{% assign data = site.data.topic-data %}

<table class="table table-striped" style="max-width: 650px;margin-left: auto;margin-right: auto;">
    <thead>
       <tr>
          <th>"data" value</th>
       </tr>
    </thead>
    <tbody>
    {%- for d in data -%}
    <tr>
       <td class="value">{{ d.name }}</td>
    </tr>
    {%- endfor -%}
    </tbody>
</table>

# Steps for Creating a Visualization

# Steps for Creating an Essay

translate the results of digital methods into historical argument.