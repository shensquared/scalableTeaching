---
title: General tips
info_cat: true
nav_order: 0
---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

# General tips

## Make a publicly-accessible site (even if merely for the logistics)
A publicly-accessible site (of at least course logistics FAQs) significantly reduces the volume of inquiries before and during the first few weeks of the course run. It also doubles as an internal knowledge base for onboarding new staff members.

There are various ways a website can be set up in place, or in conjuction, of the services provided by MIT IST. Here are two examples:

### All-in-one site model
where course info, plus courseware and gradebook are all handled via a standalone independent site. 

At EECS, these courses typically run via [catsoop](https://catsoop.org), e.g. [6.101 py](https://py.mit.edu) and [6.390 introml](https://introml.mit.edu/spring23). Depending on if you'd like to host the website on a physical machine on campus or up in the cloud, the process can vary a little bit. Adam Hartz and I are probably able to help with the consultation.

<!-- [introml](https://introml.mit.edu/spring23) -->

<!-- <iframe src="https://introml.mit.edu/spring23/info/" width=1000 height=300 async></iframe> -->


### Hybrid sites (model I)
where course info has a dedicated site, and courseware and gradebooks are handled via Canvas (and e.g. Piazza modules linked therein). 

Examples here incldue [Computer Vision]()
<!-- [gradml](https://gradml.mit.edu) -->
<!-- <iframe src="https://gradml.mit.edu/" width=1000 height=300 async></iframe> -->

### Hybrid sites (model II)
where course info has a dedicated site, and courseware has an independent site. 

Examples include the [Underactuated Robotics]()

### Stick with just Canvas
where the Canvas site is made public -- either all of it or parts of it. For instance, an easy yet clever idea is to set up a public module on Canvas, dediacated for pre-semester FAQs, where the rest of the modules remain restrictied to registered students (or to all MIT members).

## Consider to open-source course materials (as much as possible)

Sharing is great; and also mutually beneficial! With source texts and source code openly accesible, we create an inviting and prodcutive learning community! Personally, I've submitted unsolicited Pull Request (PR) to various lecture notes, and recently have received unsolicited PR to the gradML draft site I'm grad(ually) building up.

I truly believe open-sourcing helps create a positive feedback loop (positive is good in this case).

## Update the Registrar Course Catalog (e.g., link course site there)
Most students shop for classes by checking out the [Course Catalog](http://student.mit.edu/catalog/m6a.html). 

It's therefore a good idea to keep the info there up-to-date; it's also been helpful for us to list the course website as "extra info" there.

[Lisa Bella]({{site.baseurl}}/info/contact/#lisa-bella) is the point person for requesting such changes.

## Pick a single place to handle logistical requests
Typically, the more staff member have access to the info, the less communication need. 

### Moira email list and tricks
- WebMoira is super intuitive (though may induce Carpel Tunnel, if you run a bit class and need to add lots of folks)
- Blanche 

```sh

```

### Funnel eveything to e.g. Piazza
or Discourse forum, or any other "central" place.

## Remember the students (names and faces)

The Registrar releases pictured roster. The python script below crops those photos out and save the file with student names. 

TODO: add the script here

I typically just sweep through the deck a few rounds; but one can go fancy and make this an Anki deck to help facilitate the memorization.

Also, every class has a Canvas site -- some are not Published by the Instructors' choice so remain invisible to students. Regardless of the visibility to students, staff members have access to the `People` tab on Canvas, with handy name search and students-uploaded pictures -- much like a year book.

The python script below interacts with Canvas instance to programmatically download student pictures (saved as kerb.png or kerb.jpg)






