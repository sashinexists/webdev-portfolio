---
title: Sashin Exists
published_date: "2021-10-12 03:12:07 +0000"
layout: post.liquid
is_draft: false
data: {
    banner_url: "/images/sashinexists_screenshot.png",
    brief: "Sashin Exists is my home as a writer featuring my articles on science, philosophy, spirituality and more. I built it in 2018 using Ghost."
}
---
### About the Project
In 2018, I quit my stable job to pursue a career as a non-fiction writer online. 

[Sashin Exists](https://sashinexists.com) is the home of my writing; all the [articles I have written](https://sashinexists.com/articles) and the [letters](https://sashinexists.com/letters’) I have sent out to my followers.

It is also a place where I keep track of the [books](https://sashinexists.com/recommended) I have read and heartily recommend and a list of [quotes](https://sashinexists.com/quotes) that I love.

---
### The Tech Behind it
The Sashin Exists website is powered by [Ghost](https://ghost.org) and uses a custom theme that I build with Ghost’s handlebars framework.

The process of building a ghost theme is very similar to building a static site using HTML, CSS and vanilla Javascript.

The website is running as a self-hosted Ghost install on a [Digital Ocean Droplet](https://docs.digitalocean.com/products/droplets/) which in turn is running Ubuntu.

My mailing list is managed by [Mailgun](https://mailgun.com) which has been configured to run with ghost.

The marketing and traffic analytics to my website are managed by [Ghostboard](https://ghostboard.io) which is an analytics dashboard tailored to Ghost websites and an alternative to the popular “Google Analytics”.

It’s possible to view a public dashboard of my analytics accessed through my about page.

 - [Click here to view the analytics dashboard for my site](https://ghostboard.io/public/5c4fbc8cd52bc52e26c61702#insights)

The [recommended page](https://sashinexists.com/recommended) integrates with the [Google Books API.](https://developers.google.com/books/) For all of the book recommendations you see, their titles, covers, authors and brief descriptions were fetched from [Google Books](https://ghostboard.io/public/5c4fbc8cd52bc52e26c61702#insights). 

This is achieved with javascript I have embedded in the sashinexists ghost theme. It fetches data for all of those books and then stores it in the cache (on your local machine), next time you load the page it checks to see if the number of books stored in cache matches the number that I have on my Google Books list. If it does, it simply loads the cache and if not it fetches the books data again.

(If any developers have a better idea as to how I can display a dynamic list of books on my website, feel free to [let me know](mailto://myself@sashinexists.com).)

I have also set up an [online store](https://shop.spreadshirt.com/sashinexists) selling t-shirts, jackets, mugs and other merchandise using [Spreadshop](https://www.spreadshop.com/).

I have a [list of quotes](https://sashinexists.com/quotes) that I am really fond of featured on my website. If you click on any you can get to [an expanded page](https://sashinexists.com/quote/if-you-wish-to-make-an-apple-pie-from-scratch-you-must-first-invent-the-universe/), which in turn has a link to buy a t-shirt, jacket or mug with said quote.

Unlike most of the other projects listed here, this website was not worked on to completion in a fairly short period of time but rather was tweaked and updated gradually over time.

There is a lot more to it than even what’s mentioned here.