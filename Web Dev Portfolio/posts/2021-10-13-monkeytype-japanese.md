---
title: "Japanese Support for Monkeytype"
published_date: "2021-10-13 21:36:08 +0000"
layout: post.liquid
is_draft: false
data: {
    banner_url: "/images/monkeytype-japanese_screenshot.png",
    brief: "I successfully was able to add Japanese language support to the popular speedtyping website."
}
---
### About the Project
MonkeyType is arguably the best website for speedtyping practice on internet and bills itself as the most configurable. This view point seems almost unanimous among the speedtyping communities I have visited.

One of the coolest features they have is their out of the box support for many languages - they even support coding languages such as Rust.

Unfortunately, at the time they did not support Japanese… so I went and fixed that…
 
 ---
### The Tech Behind it
This was a really a simple affair. A new “language” in MonkeyType is submitted as a list of words in a JSON file.

[You can see my submission here.](https://github.com/Miodec/monkeytype/blob/master/static/languages/japanese_hiragana.json)

Relative to the amount of work that was put in, I feel disproportionately proud of this as a pull request of mine was accepted in one of the most popular typing sites there is, used by millions around the world.

I thought it would be a good idea to learn useful Japanese words while learning how to touch type in Japanese Kana.

One complication was that MonkeyType would not work with Kanji. Japanese is comprised of three scripts; Kanji, Hiragana and Katakana. Kanji communicates meaning whereas Hiragana and Katakana are phonetic, which means that they only express sound - just like English letters. As such every word can be expressed in Hiragana only.s

What I did was find a list of commonly-used Japanese words and copied and pasted it into [Visual Studio Code]() and applied a series of regex transformations on it so I could extract a list comprising of nothing but the hiragana versions of the words. Which I then added to the JSON file and submitted.

In addition to this I submitted a list of common-use loan words as a separate language. Loan words are Japanese words that are borrowed from other languages. 

They are written in Katakana.

- オレンジジュース → “Orenji Jyushuu” → “Orange Juice”
- テレビ → “Telebi” → “television”
- トイレ → “Toire” → “toilet”
- スマホ → “Sumaho” → “Smartphone”

The pull request for [this was also accepted](https://github.com/Miodec/monkeytype/blob/master/static/languages/japanese_katakana.json).