---
title: >
    Scaling Visual Search.... By Shrinking It
date: 2022-06-23
description: >
     A condensed and refined version of my LOPQ talk. It sticks more to higher ideas and shows more use cases at Bazaarvoice. Prepared for and presented at https://www.faire.com/ 's data tech talks on June 23, 2022..
img: /talks/64Ot6p2xubg.jpg
videoId: 64Ot6p2xubg
---



## Abstract
The sheer volume of user generated content online has exploded over the last decade: billions-scale datasets are now the norm instead of the exception. Bazaarvoice enables e-commerce brands to gather, curate, and publish this user-generated content on their product websites to drive sales, build consumer trust, and make the online shopping experience more transparent. Operating at scale, however, requires solving a unique data association problem: if a consumer posts an image of a product online, what products are in the photo?

In this talk, I explore the unique scaling challenges of this problem, known as visual search, and how Bazaarvoice solves them by compressing the space using state of the art techniques. Specifically, I start with an overview of our product space and how visual search fits the product need. Next, I discuss the general techniques of solving visual search, also known as the approximate nearest neighbor problem, and how the classical approaches fail in the face of large datasets. I'll follow this with a deep dive into our chosen technique -- locally optimized product quantization -- and how it enables scaling for our use case. Finally, I'll conclude with some insights into the engineering of the system, and how we've leveraged it for multiple product offerings.
