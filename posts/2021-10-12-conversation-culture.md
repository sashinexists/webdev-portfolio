---
title: Conversation Culture
published_date: "2021-10-12 02:50:24 +0000"
layout: post.liquid
is_draft: false
data: {
    banner_url: "/images/conversation-culture_screenshot.png",
    brief: "Conversation Culture is an initiative to improve the quality of our discourse across different political, philosophical and religious views."
}
---

### About the Project

In 2018 I joined this group through [meetup.com](https://www.meetup.com/en-AU/conversation-culture/), it’s name used to be Fans of the Intellectual Dark Web in reference to a number of scientists, philosophers and public figures that were rising in popularity on the internet.

We met regularly to discuss questions such as:

- How do we find meaning in the modern world?
- What’s wrong with politics and how do we fix it?
- How is it that we can say we know things?

By the end of 2019 the organiser of the group had to move to Melbourne as she had landed a new job there - it was decided that I would take over her responsibilities.

We then rebranded to _Conversation Culture_ with the aim of creating a community environment with a culture that allowed disagreement over contentious issues to be productive and even enjoyable.

Due to the pandemic our meetings were moved to being online and we started hosting events every week.

It was towards the end of the year when I decided to build a [dedicated website](https://conversationculture.net) for the group separate to the [meetup page](https://www.meetup.com/en-AU/conversation-culture/).

---

### The Tech Behind it

The Conversation Culture website is powered by [Ghost](https://ghost.org) and uses a custom theme that I build with Ghost’s handlebars framework.

The process of building a ghost theme is very similar to building a static site using HTML, CSS and vanilla Javascript.

My friend [Nathan](https://fanlink.to/eAP4) wrote up a webscraper which takes data from the group’s meetup page and uses it to generate pages with details about all our events. It is possible to find the place, time and topic of any of our events on the website.

- [A list of all the events using data scraped from Meetup](https://conversationculture.net/our-events/)
- [An example of an event page](https://conversationculture.net/276156339/)

The website is running as a self-hosted Ghost install on a [Digital Ocean Droplet](https://docs.digitalocean.com/products/droplets/) which in turn is running Ubuntu. They way it was built means it requires very little maintenance.
