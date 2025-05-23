---
title: CTFs | 404CTF_2023 | ROSO_OSINT | Les OSINTables
author: BatBato
date: 2023-06-05
categories: [CTFs, 404CTF_2023]
tags: [ROSO,OSINT]
permalink: /CTFs/404CTF_2023/ROSO_OSINT/Les_OSINTables
---

# Les OSINTables

![image](https://github.com/Nouman404/nouman404.github.io/assets/73934639/3babe668-d45d-45fc-aebb-7f760284e643)

In this challenge, we need to find the address of Causette in the image:

![image](https://raw.githubusercontent.com/Nouman404/nouman404.github.io/main/_posts/CTFs/404CTF_2023/ROSO_OSINT/Causette.jpg)

We can notice that there is the number 83 in roman number `VXXXIII` (V=50, X=10, I=1 => 50+3x10+3x1=83). There is also the name of the street `Rue Victor Hugo`.

We can see on the envelope the beginning of the name of the city `VE`. At first I start looking at all `Rue Victo Hugo` listed [here](https://fr.wikipedia.org/wiki/Rue_Victor-Hugo), but no city beginning with `Ve` had a `Rue Victo Hugo`. I then tried to type `83 Rue Victor Hugo Ve` in Google Maps. I found `83 Rue Victor Hugo, Vergèze` and flagged with:
`404CTF{83_rue_victor_hugo_vergèze}`
