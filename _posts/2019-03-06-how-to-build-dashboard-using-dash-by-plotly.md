---
layout: post
title:  "Tool of the Month: How to create interactive dashboards using Dash by Plotly?"
author: himanshu
categories: [ data visualization, Dash ]
image: assets/images/plotly.png
tags: [featured]
---
One of the promises I made myself at the start of 2019 was that I would finish learning one new tech or one online course per month. I have already started the Machine Learning course by Tom Mitchell in January (you can find my online notes here) and still going on. For the month of February, I wanted to learn something less exhaustive and chose 'Interactive Python Dashboards with Plotly and Dash".

Data visualization is a quick and easy way to convey the message universally. If you are looking for a way to visualize your data and share it with others, [Dash] is an excellent option. With about 100 lines of code, I built an interactive dash to analyze time series data for a financial service company. Written on top of Flask, Plotly.js, and React.js, Dash is ideal for building data visualization apps with highly custom user interfaces in pure Python. Through a couple of simple patterns, Dash abstracts away all of the technologies and protocols required to build an interactive web-based application, making this framework particularly suited for anyone who works with data in Python. It supports the OAuth authentication to secure the dashboards as well.


---

## What is the difference between Matplotlib, Plotly, and Dash?
=> Matplotlib: Static Visualisation <br>
=> Plotly: Animated visualization, generated in a file (e.g. HTML) <br>
=> Dash: Real-Time animated visualization <br>


---

## Table of Content
Week 1:
- [How to build your first dashboard using Dash]({{ site.baseurl }}/build-your-first-dashboard-using-Dash)
- [How to build Scatter 2D and 3D plots in Dash]({{ site.baseurl }}/build-scatter-2d-and-3-plots-in-dash) <br>
Week 2:
- How to make Heatmaps using Dash
- How to make Time Series Plots using Dash <br>
Week 3:
- How to make dashboard using Dash in Jupyter Notebook
- Case Studies <br>
Week 4:
- How to Deploy Dash dashboards on various platforms

---

My Notes:
Dash makes it dead-simple to build a GUI around your data analysis code. Here’s a 43-line example of a Dash App. As the user selects a value in the Dropdown, the application code dynamically exports data from Google Finance into a Pandas DataFrame. This app was written in just 43 lines of code (view the source). Simple.

![gif]({{ site.baseurl }}/assets/images/dash-app1.jpg)


Dash app code is declarative and reactive, which makes it easy to build complex apps that contain many interactive elements. Here’s an example with 5 inputs, 3 outputs, and cross-filtering. This app was built in just 160 lines of code, all of which were Python.

![gif]({{ site.baseurl }}/assets/images/dash-app2.jpg)

---

I highly recommend Plotly as a visualization toolkit. Well, I will be giving up Matplotlib and taking up Plotly for a very long period of time now!


---

Read User guide to Dash from https://dash.plot.ly & Follow Plotly on <br>
Instagram: https://t.co/mwuo0P15zB <br>
Twitter: https://t.co/uhrfjR4TBj <br>