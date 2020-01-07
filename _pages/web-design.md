---
title: Web Design & Development
subtitle: Let's build a website that serves the needs of your brand and business
description: Work with Lily Bruns, startup storyteller & strategy consultant
featured_image: /images/marketing.jpg
portfolio:
  - title: Cali Eco Smoke
    subtitle: A one-page website for an eco-cannabis consultant.
    description: ' * Web Design<br/> * Web Development <br/> * Brand Messaging'
    url: http://caliecosmoke.com/
    featured_image: /images/portfolio/caliecosmoke.png
  - title: BeachCity
    subtitle: A revamped website for a startup media project.
    description: '* Web Design<br/> * Web Development<br/> * Copywriting<br/> * Landing Page Creation'
    url: https://beachcity.com.au/
    featured_image: /images/portfolio/beachcity.png
  - title: Your Thai VA
    subtitle: A one-page website for a virtual assistant.
    description: '* Web Design<br/> * Web Development<br/>'
    url: https://yourthaiva.com/
    featured_image: /images/portfolio/yourthaiva.png
  - title: Ethnic Hilltribe Eco Trails
    subtitle: A website with booking integration for an eco-trekking company.
    description: '* Web Design<br/> * Web Development<br/> * Copywriting<br/> * Booking Integration'
    url: https://ethnichilltribeecotrails.com/
    featured_image: /images/portfolio/ehet.png
  - title: BEP
    subtitle: A one-page website for a bicycle courier service.
    description: '* Web Design<br/> * Web Development<br/>'
    url: https://www.bep.delivery/
    featured_image: /images/portfolio/bep.png
  - title: Bryan Bruns
    subtitle: A one-page website for a consultant sociologist.
    description: '* Web Design<br/> * Web Development<br/>'
    url: https://bryanbruns.com/
    featured_image: /images/portfolio/bryanbruns.png
---


## Web Design and Development for Startups and Small Businesses
With the tools of the modern web, anybody can make a website - but will it actually be any good?

Your website needs to have great SEO, it should load fast, it must be mobile-responsive, the design and branding should resonate with your target audience, it's gotta have copy that converts and - oh! - it needs to also not eat up your entire annual marketing budget.

I help startups, consultants and service providers to put their best foot forward online with **simple, beautiful, and high-performing websites designed to serve business goals.**

My full-service web packages include business consulting, design, development _and_ copywriting. Not only does this save you the hassle and cost of having to hire four separate people, it also means I can work _fast_ and the result will be coordinated and focused.

If you like for things to be easy, fast, and effective, pick me for your website needs.

---

## Selected Portfolio

{% for portfolio in page.portfolio %}

<article class="post">

  <div class="post__image-wrap">
    <div class="post__image" style="background-image: url({{ portfolio.featured_image }})"></div>
  </div>

  <div class="post__content-wrap">
    <div class="post__content">
      <h2 class="post__title"><a href="{{ portfolio.url }}">{{ portfolio.title }}</a></h2>
      <p class="post__subtitle">{{ portfolio.subtitle }}</p>
      <p class="post__description">{{ portfolio.description }}</p>
      <a href="{{portfolio.url}}" class="button" style="margin-top: 5%;">Visit Website</a>
    </div>
  </div>

</article>

{% endfor %}

.

---



If you're looking to launch a new site or revamp your web presence, I can help.

<a href="/contact" class="button button--large">Email Me to Schedule Your Free 30-min Consultation</a>
