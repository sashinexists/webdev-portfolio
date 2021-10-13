---
title: "Japanese Verb Transformer"
published_date: "2021-10-13 21:36:26 +0000"
layout: post.liquid
is_draft: false
data: {
    banner_url: "/images/japanese-word-transformer_screenshot.png",
    brief: "A terminal program that allows you to input a Japanese verb and transform it to any of its other forms."
}
---
### About the Project
I am [learning Japanese](https://sashinexists.com/letter/learning-and-language).

In grammar, we have this concept of conjugation.

Where a word can be changed so that its meaning is altered.

Tense is a good example of this:

- Walk
- Walking
- Walks

Plurality is another one:

- Tree
- Trees

In English, this can get quite tricky. 

There isn’t a set of neat rules that you can apply to any word to change it to a plural for example.

Consider:
- House → Houses
- Mouse → Mice

You just have to remember them - which is rather inelegant.

The Japanese Teaching Youtuber [Cure Dolly sensei](https://www.youtube.com/channel/UCkdmU8hGK4Fg3LghTVtKltQ) has described Japanese has being like a perfect crystal. 

Completely regular and therefore beautiful. You only need to remember a finite set of word transformations and you can then apply them to any word with almost no excepts at all.

It occurred to me that what follows logically, is that it would be easy write a program that took any Japanese word and transformed it into any of its other forms… so I did.

(Note: Cure Dolly sensei often talks about how the European concept of “word conjugation” does not neatly apply to Japanese and criticises the term’s use in Japanese textbooks. What seems to be conjugation is actually separate words added on, as there are no spaces in between words in Japanese,  Westerners can easily mistake the addition of another word for conjugation).

---
### The Tech Behind it
This is a fairly simple script that was written in Rust and run in the Terminal.

It is very simple: when you run the script it asks you to type a Japanese Word and then asks you which form you would like to change it to and performs the transformation.s

I store a list of rules for all of the possible word transformations in a separate JSON file which the script then applies.

I wish to expand this in the future and even create a test mode that asks you to transform a verb and checks it against the right answer. 

I would also like to integrate it with a Jisho - that is; Japanese dictionary - API. This way it can verify if the input words are correct and even implement suggestions.

I would also like to create a graphical interface to the app which I will likely do when I am learning how to use GTK4 to create desktop apps for Linux.