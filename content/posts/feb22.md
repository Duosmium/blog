---
title: "February 2022 Update"
date: 2022-02-26T23:06:26-05:00
weight: 0
authors:
  - duosmium
tags:
  - Duosmium News
  - Monthly Updates
geekblogToC: 3
geekblogHidden: true
geekblogAnchor: true
draft: true
---
Hey everyone! As February comes to a close, here's some of the things we've been working on in the past month.

## Competitions

We are approaching 400 results on Duosmium! This is a huge milestone for us, and we can't wait to reach it. It's been great getting to work with the community as we publish everything, and we're so grateful for your continuing support.

Some of our recent official work:

* BirdSO Satellite Invitational: [Division B](https://www.duosmium.org/results/2022-02-12_birdso_satellite_invitational_b), [Division C](https://www.duosmium.org/results/2022-02-12_birdso_satellite_invitational_c)
* MIT Invitational: [Division C](https://www.duosmium.org/results/2022-01-22_mit_invitational_c)
* North Pocono Invitational: [Division C In-Person](https://www.duosmium.org/results/2022-01-29_north_pocono_in-person_invitational_c), [Division C Satellite](https://www.duosmium.org/results/2022-01-29_north_pocono_satellite_invitational_c)
* Science Olympiad at Penn State Invitational: [Division C](https://www.duosmium.org/results/2022-02-05_soaps_invitational_c)
* Sierra Vista Invitational: [Division A](https://www.duosmium.org/results/2022-02-05_sierra_vista_invitational_a), [Division B](https://www.duosmium.org/results/2022-02-05_sierra_vista_invitational_b)
* University of Michigan Invitational: [Division B](https://www.duosmium.org/results/2022-02-19_umich_invitational_b), [Division C](https://www.duosmium.org/results/2022-02-19_umich_invitational_c)

## Technical

We have some big changes incoming to the Duosmium Results site! We've been working on an improved version of the site that allows for faster builds as well as new functionality. This new site is written in JavaScript using the [Nunjucks](https://mozilla.github.io/nunjucks/) templating engine and [11ty](https://www.11ty.dev/) static site generator. Using these tools and the powerful asynchronous functionality of [Netlify On-Demand Builders](https://docs.netlify.com/configure-builds/on-demand-builders/), we've been able to cut down build times from several minutes to as little as 15 seconds, since we no longer have to generate hundreds of results pages each time -- the results are now generated whenever someone accesses them!

Another cool feature that's been added to the new site is a popular request: you can now superscore tournaments! To superscore a tournament, open the filter menu and select "Superscored". This will show you the superscored results of the tournament, and you can analyze and export them like you would normally.

The new site is currently in testing, and we hope to replace our existing Duosmium Results site with it in the near future. If you would like to check it out, you can [visit the site](https://next.duosmium.org/) or [check out the source code](https://www.github.com/Duosmium/duosmium-js). Thanks so much to Tomi Chen for rewriting `sciolyff` and the Duosmium website and implementing all these innovative features!

{{< hint >}}
One note about the new site: it is tied more directly to Netlify-specific features, so it will not initially work properly if you're not using Netlify. We're working on a solution that will allow you to use the site without Netlify, but we're not quite there yet.
{{< /hint >}}
