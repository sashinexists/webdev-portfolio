---
title: "Material Shell Website"
published_date: "2021-10-13 02:39:50 +0000"
layout: post.liquid
is_draft: false
data:
  banner_url: /images/material-shell-website_screenshot.png
  brief: "The Material Shell project is an attempt at rethinking the way we interface with our desktops. I designed and built their website - and made it look like Material Shell itself."
---
### About the Project
(Note: I write a little about Material Shell below, but I didn’t make the Shell, I made their [website](https://material-shell.com))

A shell is a user interface that we use to interact with our computers. It is called a shell because it's what we see, it's what is on the *outside*.

The Material Shell project is an ambitious attempt to change the way that we interface with our desktops with a focus on productivity and multitasking.

![Material Shell](/images/material-shell)

It does this by implementing what’s called a *tiling window manager* rather than the floating window managers we are used to. This automates the process of positioning apps on the screen. It also introduces a feature called persistence, where between sessions the apps a user was using, the windows that were open and where they were positioned, is remembered and the user can just continue where they left off.

The idea for Material Shell dawned from the realisation that the activities of opening apps and moving windows around were activities done very frequently and that they could be automated.

It is a shell for Linux that is packaged as an extension of the popular [GNOME desktop environment](https://forty.gnome.org/). 

I became interested in the project because I myself was using it, and so I reached out to their community discord and asked how I could help.

I created their website and built to so that it looked like Material Shell itself.

---
### The Tech Behind it
I built the Material Shell website using [NuxtJS](https://nuxtjs.org/) as a static site generator. This project served as an entry point into learning about [VueJS]() and related technologies. 

Material Shell is so named because it closely follows the [Material Design](https://material.io/design) principles by Google.

To make the website look like Material Shell, I used the [Vuetify](https://vuetifyjs.com/en/) framework for VueJS which allowed me to easily create and use components that were consistent with the Material Design guidelines.