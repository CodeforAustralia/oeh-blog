---
layout: post
title:  "Code Review"
date:   2016-03-10 14:35:00 +1100
author: Kenni Bawden
categories: update technical
---

Today [Daniel Buckmaster](https://github.com/eightyeight) and I performed a code review of the [Heritage Near Me swipe app prototype](https://github.com/kennib/heritage-near-me/tree/master/swipe-local-history/prototype).
You can check out the results in this [github issue](https://github.com/kennib/heritage-near-me/issues/55).

Traditionally a code review is a tool used to review code before it gets used in the live version of an app or service.
Code reviews are generally done incrementally and really on an entire app or website.
Since Jesse and I are running as a two man team and I'm the only one with coding experience, regular incremental code reviews are not a very practical option.
Instead I've opted to have Daniel come in and give an outsider perspective on the code base.
This is a particularly helpful task since it gives me a dry-run of the process of handing the code to the Office for Environment and Heritage later in the year.

The way we ran the session was to first open the [code on Github](https://github.com/kennib/heritage-near-me/tree/master/swipe-local-history/prototype).
Then Daniel had control of the computer and set about trying to understand how the code worked by reading through it.
It became readily apparent what information was missing or ambiguous.
Any time Daniel needed to ask a question, or I felt like I needed to jump in with information, I would record it in a [Github issue](https://github.com/kennib/heritage-near-me/issues/55).

The entire process took about 2 hours to complete including a 15 minute break in the middle.
The end result of all this was a list of areas that need improvement and some ideas on how to document the code from the perspective of an outsider (who might not know Elm for example).
The list of areas to improve should not only make the hand over to the OEH much easier but also make any further code reviews a much quicker and easier process.

If you'd like to help out with a code review send me an [email with the subject 'Code Review'](mailto:kenni@codeforaustralia.org?Subject=Heritage%20Near%20Me%20Code%20Review&Body=Hi%20Kenni%21%0A%0AI%27d%20like%20to%20help%20out%20with%20a%20code%20review%20some%20time.).
