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

There are various ways a website can be set up, in place, or in conjuction, of the services provided by MIT IST. Here are some "models":

### All-in-one site model
where course info, courseware, and grades/extensions alike are all handled by a standalone site. 

At EECS, these courses typically run via [catsoop](https://catsoop.org). Depending on if you'd like to host the website on a physical machine on campus or up in the cloud, the spin-up process can vary a little bit. Adam Hartz and I are probably able to help; at some point you might also need to contact Fletch.

Examples:

- 6.390 [Intro to Machine Learning](https://introml.mit.edu/spring23)

- 6.411 [Representation, Inference and Reasoning in AI](https://airr.mit.edu/fall23)

<!-- [introml](https://introml.mit.edu/spring23) -->

<!-- <iframe src="https://introml.mit.edu/spring23/info/" width=1000 height=300 async></iframe> -->


### Hybrid sites (model I)
where course info and courseare has a dedicated site, and all else is handled by Canvas (and modules linked therein like Piazza). 

Examples:

- 6.7900 [Machine Learning](https://gradml.mit.edu/)

- 6.8300 [Advances in Computer Vision](http://6.8300.csail.mit.edu/sp23/schedule.html)

<!-- [gradml](https://gradml.mit.edu) -->
<!-- <iframe src="https://gradml.mit.edu/" width=1000 height=300 async></iframe> -->

### Hybrid sites (model II)
where course info has a dedicated site, courseware has a dedicated site, and all else are is handled via other tech stack. 

Examples:

- 6.4210 [Robotic Manipulation](https://manipulation.csail.mit.edu/Fall2023/) (and a separate [courseware](https://manipulation.mit.edu) site)

- 6.8210 [Underactuated Robotics](https://underactuated.csail.mit.edu/Spring2023/) (and a separate [courseware](http://underactuated.mit.edu) site)

### Stick with just Canvas
where the Canvas site is made public -- either all of it or parts of it. An easy (yet clever) idea is to set up a public module on Canvas, dedicated for pre-semester FAQs, where the rest of the modules remain restricted to registered students (or to all MIT members).

Examples:

- 6.C06/18.C06 [Linear Algebra and Optimization](https://canvas.mit.edu/courses/16629)

## Consider to open-source course materials (as much as possible)

In my experience, with source texts and source code openly accessible, we create an inviting and productive learning community, and a positive feedback loop (positivity is good here:).

Personally, I've submitted unsolicited Pull Request (PR) to various lecture notes, and recently I've received unsolicited PR to the [gradML](https://gradml.mit.edu) draft site I'm grad(ually) building up. 

I was quite thrilled about this "full-circle". I think that's the magic of open-sourcing; sharing is mutually beneficial!

## Update the Registrar Course Catalog (e.g., link course site there)
Most students shop for classes by checking out the [Course Catalog](http://student.mit.edu/catalog/m6a.html). 

It's therefore a good idea to keep the info there up-to-date; I've also found it helpful to list the course website as "extra info" there.

[Lisa Bella]({{site.baseurl}}/info/contact/#lisa-bella) is the point person for requesting such changes.

## Pick a single place to handle logistical requests
and as many staff members having access to it as possible/sensible; and as few members acting on it as possible/sensible.
The "acting" part really varies from course to course; we focus on the "accessing" part below.

### Moira email list and tricks

[WebMoira](https://groups.mit.edu/webmoira/) is super intuitive to use (though may induce carpal-tunnel syndrome, if you run a big class and need to add lots of folks). It's possible to create a list more programmatically on Athena. The process goes like this:

1. Make an arbitrarily-named plain-text file, say, `my_list.txt`, with single kerb per line.

2. Suppose you want your Moira list to be `6st_staff@mit.edu`, then get on Athena, run: 
```sh
blanche <6st_staff> -al <my_list>.txt
```
where `<6st_staff>` and `<my_list>` could be tweaked to your liking. 

### Funnel everything to e.g. Piazza
or Discourse forum, or any other "central" place.


## Create an inclusive learning environment
### Remember students (names and faces)

The Registrar releases pictured roster PDF. I found that just sweeping through the roster back and forth itself can be helpful; but since the roster is alphabetically ordered, sometimes a head-on memorization approach may not be the most efficient. 

All is not lost. The python script below crops photos out of the roster PDF, and save the file with student names. One can then go make an Anki deck to facilitate the memorization.


Also, every class has a Canvas site -- some are not Published by the Instructors' choice so remain invisible to students. Regardless of the visibility to students, staff members have back-end access to the `People` page, which offers handy name search and shows students-uploaded pictures -- much like a digital year book.

What if we want an Anki deck via the Canvas route too? Well, the python script below does exactly that, as before -- except that instead of cropping photos from a PDF, it interacts with a Canvas instance to programmatically download student pictures. 


TODO: add the two scripts here

### Consider open-source 

By making course materials accessible to everyone, regardless of their registration status, or past experiences, we create opportunities for individuals from diverse backgrounds to contribute and collaborate. This inclusivity fosters a more diverse community, bringing in different perspectives, experiences, and ideas. 