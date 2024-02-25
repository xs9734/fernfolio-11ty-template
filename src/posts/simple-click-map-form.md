---
title: Simple Click Map Form
date: 2024-02-19T03:52:05.549Z
summary: DIY-ing Paywalled features.
tags:
  - post
---
This quick project came up when I was trying to create a form for my Wundercat UX study. I wanted to ask a simple question, "Where would you click to open X". I wanted to make the survey to be very simple and easy to complete since I am working with a budget of $0. Surprisingly the only out-of-the-box solution I found was by Survey Monkey and it is behind a $39 paywall. I was able to create a form using pure JavaScript and Netlify to handle the form submission. With up to 100 free submissions per month I am definitely going to save a buck with this. It took about a couple hours of work and definitely worth it. The form consists of one question "Where would you click to order Tuna Treats", the user clicks somewhere in the image, the coordinates are recorded and submitted to a Netlify form. Once all submissions are completed I can use a python script to overlay the plots over an image using matplotlib