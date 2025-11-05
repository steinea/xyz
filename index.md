---
layout: default
title: "Eric Stein / Garden"
permalink: /
---

#### Activity

<!-- Tracking for hobbies using liquid generators and frontmatter to produce activity feeds from pages in my inventory and garden. For a more high level summary, see my [Now](https://steinea.fyi/now/) page. -->

<!-- To add: Drinking, Listening, Sleeping, Traveling -->

{% include activity.html %}

<br>


#### Codex

<!-- Cross-reference for my garden and library, using pre-defined liquid generators in combination with [tags](https://jekyllrb.com/docs/front-matter/) and conditional liquid generators in my [page.html](https://github.com/steinea/xyz/blob/main/_layouts/page.html) layout to procedurally build lists of related pages. -->

{% include codex.html %}

<br>


#### Garden

<!-- My personal wiki of bookmarks from across the web, presented in three different views for a variety of approaches to discovery. -->

{% include garden.html %}

<br>


#### Inventory

<!-- Records of my physical media, collectibles, and other durables, generated from a mix of standard pages and [data](https://jekyllrb.com/docs/datafiles/) files, and cross-referenced with codex and library. -->

{% include inventory.html %}

<br>


#### Library

<!-- Pages split from my garden due to volume and complexity, heavily cross-referenced with activity and codex. -->

{% include library.html %}

<br>


#### Workshop

<!-- Raw materials from my research, teaching, and creative practice. -->

{% include workshop.html %}

<br>


#### WIP

{% include wip.html %}

<br>

<hr>


#### Colophon

{% include colophon.md %}
