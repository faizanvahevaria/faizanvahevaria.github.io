---
layout: single
title: "50k Challenge to check my Perseverance and Get Back in Shape"
categories:
  - Challenge
tags:
  - Life Change
  - Perseverance
  - Health and Fitness
  - Challenge
excerpt: "Nothing"
permalink: /50k-challenge/
---

<table>
  <thead>
    <tr>
      <th>Day</th>
      <th>Pushups</th>
      <th>Abs</th>
      <th>Squats</th>
    </tr>
  </thead>
  <tbody>
    {% for day in site.data.challenge %}
    <tr>
      <td>Day{{ day.day }}: {{ day.date | date_to_long_string }}</td>
      <td>{{ day.p }}</td>
      <td>{{ day.c }}</td>
      <td>{{ day.s }}</td>
    </tr>
    {% endfor %}

    <tr>
    <td>Total: </td>
    <td></td>
    <td> </td>
    <td> </td>
    </tr>
  </tbody>
</table>
