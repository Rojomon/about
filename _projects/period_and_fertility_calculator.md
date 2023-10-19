---
layout: page
title: period and fertility calculator
description: calculate the next period date and the fertile days
img: assets/img/period_and_fertility_calculator_1_2.png
importance: 1
category: learn
---

This project appeared by pure chance on my previous week's todo list. I was studying for the [Python Certified Associate Programmer \[PCAP\]](https://pythoninstitute.org/pcap) certification and was learning about the calendar package and its modules, functions and all that. I then took a short coffee break and told my girlfriend that I could build her an useful app. She didn't think twice and started giving me the requirements for this app: it should do this, and that, and you also have to consider this. The rest is history. I spent the next two evenings and the following weekend working on the Python script. Once that was done and over I decided that the best way to make this program easily available to everybody, including my girlfriend, was to make it publicly accesible. For this I asked a dear colleague of mine to assist me in creating a subdomain for my nginx web-server. I then had to learn the basics of Flask in order to rewrite the program as a Flask app, grab a nice CSS template from the guys over at [PicoCSS](https://picocss.com/) and put together some basic JavaScript for the form data using ChatGPT.

_Voilà !_ 

The result is now hosted here [`Period and Fertility Calendar Calculator`](http://period-and-fertility-calculator.stefanrosu.ro/) and you can also see it in the two screenshots below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/period_and_fertility_calculator_1_2.png" title="input form and legend" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/period_and_fertility_calculator_2_2.png" title="period and fertile days calendar" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    On the left, the input form and the legend. Right, the calendar with emphasis on the period and fertile days.
</div>