---
layout: single
title:  "Interview with Julia Pottinger"
date:   2021-02-20 10:20:47 +0000
categories: interviews
---

## Julia Pottinger

Twitter: [@ailuj876](https://twitter.com/ailuj876)

LinkedIn: <https://www.linkedin.com/in/julia-pottinger/>

## Interview

### Where are you in your testing journey?

I am 6 years in. Continuous learning and sharing to grow and expand knowledge. I am currently a Training and Development Manager so I am helping persons on their testing journey, pointing them in the correct direction and providing guidance.

### The best bug you have ever found?

An interesting bug that I found was with an e-commerce website. They were moving from a single cart to having the user being able to purchase multiple items at the same time. The business logic required certain fields to show based on what was in the cart.

The bug was that SOMETIMES I would get the fields to show correctly and other times I would not. What I realized was that checks were only being done for the first item in the cart(logic from single cart still existed). So if an item that will trigger the fields to display were second in the cart, the fields would not display.

I found this bug by trying out different combinations of items in the cart being first and shuffling the order. Understanding the business logic was crucial as no error was thrown but the field was missing. So the order would go through but it could not be delivered by the business as needed fields would be missing.

### Advice you would give to Testers?

Learn and share with your community. There is so much valuable information that you can learn to expand your mindset and skills.

Be patient with yourself. You won't know everything that is why we learn.

### What does winning mean to you?

It means that I helped someone and for me that is the goal of sharing. :)
