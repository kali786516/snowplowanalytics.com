---
layout: post
title: 2015-2016 winternship wrap-up
tags: [snowplow, intern, winter, wintern, internship]
author: Alex
category: Recruitment
permalink: /blog/2016/03/17/2015-2016-winternship-wrapup/
---

Snowplow's Data Engineering winternships wrapped up last week - many thanks to Ed and Oleks for their fantastic contributions to Snowplow over the winter period! In this blog post we'll introduce both winterns to the Snowplow community, as well as giving a little more background on the projects they worked on.

This is the fifth instalment of our internship program for open source hackers - you can read more about our previous [winter] [winter-2015] and [summer] [summer-2015] internship programs at those links.

![interns-montage] [interns-montage]

As always, our internships are open to remote applicants as well as candidates in London. Building on what we've learnt works best from the previous internships, our winterns were with us for a little longer this winter: two months for Ed and three months for Oleksandr. Find out more about Ed and Oleks and what they worked on after the jump!

<!--more-->

## Ed Lewis: SendGrid and Urban Airship support in Snowplow

Ed Lewis lives in Colchester, UK and joined us a remote Data Engineering wintern for December and January. Ed is an experienced Java developer - for him the winternship was an opportunity to get more applied Scala and Functional Programming experience.

Ed was responsible for a huge release for us: [Snowplow 75 Long-Legged Buzzard][r75-release]. This release lets you warehouse the event streams generated by Urban Airship and SendGrid.

The Urban Airship Connect adapter lets you track mobile app events delivered by [Urban Airship Connect][urbanairship-connect]. Using this functionality you can warehouse all of your Urban Airship mobile app and push notification events alongside your existing Snowplow events; Ed worked closely with the Urban Airship team to get this great new functionality tested and released.

Meanwhile, Ed's SendGrid webhook adapter lets you track all email-related events emitted by SendGrid through their [SendGrid webhooks] [sendgrid-webhooks]. It's great for keeping track of your email campaigns, allowing you to see which emails generate the most interest.

This was the first time that a wintern took charge of a whole Snowplow release - a great milestone for the internship program. Thanks for your contributions Ed!

## Oleksandr Olgashko: the first release of Sauna, an all-new product

Oleksandr is a student in Kiev, Ukraine, studying a Master's at Taras Shevchenko National University. Oleks joined us for a Data Engineering winternship for 3 months.

We gave Oleks an ambitious task: taking an all-new product idea, called [Sauna] [sauna], from specifications all the way through to a working first release. Oleks was certainly up to the task: the first release of Sauna is currently in test and should be released soon.

Sauna is an all-new open-source product designed to make it easy for business analysts to integrate third-party marketing systems like Optimizely and SendGrid into their workflow. If Snowplow is all about consolidating event streams from many sources into a event warehouse in Redshift, then Sauna is its complement: once you have the output of your analysis in Redshift, you can use Sauna to automatically pipe that data into Optimizely or SendGrid; a variety of integrations with other systems will be added to Sauna in due course.

We'll provide much more detail on Sauna when we release it - in the meantime, check out the [Sauna wiki] [sauna-wiki] for a sneak peak at the launch functionality.

Many thanks Oleks for taking Sauna from a concept through to a working system!

## Summer internships at Snowplow

Interested in working on an open-source internship at Snowplow? Applications for our summer internship program will open on 1st April - please check back with our blog then.

[winter-2015]: /blog/2015/01/25/introducing-our-2014-2015-winterns/
[summer-2015]: /blog/2015/07/10/introducing-our-2015-summer-interns

[interns-montage]: /assets/img/blog/2016/03/winterns-2015-2016.png

[r75-release]: /blog/2016/01/02/snowplow-r75-long-legged-buzzard-released/
[urbanairship-connect]: https://www.urbanairship.com/products/connect
[sendgrid-webhooks]: https://sendgrid.com/docs/API_Reference/Webhooks/index.html

[sauna]: https://github.com/snowplow/sauna
[sauna-wiki]: https://github.com/snowplow/sauna/wiki
