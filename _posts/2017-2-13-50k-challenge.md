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

## Why am I doing this?
Actually, I am out of shape right now and I am not working out as I used to. So, I have decided to push my self to get back on the healthy lifestyle.

I read an article by Jeff Haden ["Here's What Happened When I Did 100,000 Pushups and 50,000 Sit-Ups"] (http://www.inc.com/jeff-haden/heres-what-happened-when-i-did-100000-pushups-and-50000-situps.html) and I decided  I also want to do this.

But I am doing it differently.

I will be doing 50,000 Pushups and 50,000 Squats in the timespan of 180 days.

I will start with 100 pushups and 100 squats a day and will increase 20 every week.
I will be having the Sunday as Rest day.


The main goal of this challenge is not just the Physical Transformation, but the Mental challenge of doing the WORK every single day.

I am posting this here on my blog so that I can stay Accountable.


<table>
  <thead>
    <tr>
      <th>Day</th>
      <th>Pushups</th>
      <th>Squats</th>
    </tr>
  </thead>
  <tbody>
    {% for day in site.data.challenge %}
    <tr>
      <td>Day{{ day.day }}: {{ day.date | date_to_long_string }}</td>
      <td>{{ day.p }}</td>
      <td>{{ day.s }}</td>
    </tr>
    {% endfor %}

    <tr>
    <td>Total: </td>
    <td>100</td>
    <td>100</td>
    </tr>
  </tbody>
</table>
