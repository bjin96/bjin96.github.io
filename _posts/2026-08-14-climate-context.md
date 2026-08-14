---
layout: blog_post
title: 'Revisiting Climate Context'
date: 2026-08-14
tags:
  - Post
---

Prompted by another exceptionally hot summer in Europe, I revisit Climate Context an android app that puts prevailing
weather into its historical context we built 3 years ago.

![alt text](/assets/images/photos/climate_context.png "Climate Context App")

Back in 2023, Jakob Deutloff, Lara Stuck, and I built a small android app to put current weather at your current
location into historical context. We were driven by two questions we often asked ourselves whenever we encountered a
particularly hot week, or a particularly rainy streak of days.

_How normal or how exceptional is the current weather? How has this changed over
last decades due to climate change?_

And hence, we built an app using data provided from OpenMeteo that answers those exact questions:
[Climate Context](https://play.google.com/store/apps/details?id=com.milesgrey.climate_context). Back then we described
the app:

> With ongoing global warming, extreme weather events are becoming more frequent, but it is hard to assess how
> extraordinary current weather conditions really are. This is where Climate Context comes into play. It helps put the
> prevailing weather into its climatic context by comparing current temperatures and precipitation to their historical
> evolution. You can choose whether you want to compare daily values, averages over the last seven days (weekly) or the
> last 30 days (monthly) to the respective period of the year within the last eight decades, going back to 1940.

With another exceptionally hot summer across Europe slowly coming to a close I thought it would be worth revisiting the
app.

Since the original first version, I added a few more features, including an introductory walkthrough the app, when
opening the app for the first time. On the main page we show the current temperate/precipitation, and contextualising
information such as the last time a similarly or more extreme weather occurred and the return period of the temperature.
The return period describes the number of years between occurrences of the current or more extreme
temperatures/precipitations. If you're interested in more detailed information, the app provides the historical
evolution of the weather variable in a time series and its distribution. 

When you first open the app, the information is shown for the current day in comparison for the same day across the last
80 decades. E.g. today, August 14th, 2026 is compared to August 14th, 2025, August 14th, 2024, and so on. Admittedly,
due to high variance, a single day will not always be super meaningful. That's why the app provides comparisons for the
current week and the current month as well, which decrease the variance and shows clearer trends.

Sometimes, I was not only interested in my own location, but in others as well. Likewise, sometimes I wanted to check
a day in the past. So, arbitrary locations, both in space and time, can now be picked within the app.

Effects of climate change are becoming increasingly apparent. Climate Context helps to understand the weather we
experience every day, and at the place that we live. If this has caught you're attention, give the app a try!

<div class="row justify-content-center">
    <div class="col-md-3">
        <a href="https://play.google.com/store/apps/details?id=com.milesgrey.climate_context" target="_blank" rel="noopener noreferrer">
          <img src="/assets/images/photos/get_on_google_play.png" alt="Climate Context App" />
        </a>
    </div>
</div>
