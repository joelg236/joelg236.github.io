---
title: Thinking about syntax
layout: post
---

Lately I've been wondering about where we are in the programming world, and why. Inspired by [this talk](http://worrydream.com/dbx/) (even more interesting discussion [here](https://news.ycombinator.com/item?id=6129148)), I want to give my perspective on programming, syntax and what I think programming might benefit from. I think my perspective might be interesting to look at in comparison to some of the more experienced people in the community, as I don't have a lot of years of experience. Maybe my not-so-conformed ways of thinking might add something interesting. I'd be very happy to hear from those with experience as well.

So before you wander into the territory of what *good* syntax is, you want to figure out what exactly you're trying to accomplish.

- Clean
- Understandable
- Fast to write
- Efficiently organised

I'll stick with these 4 basic elements to avoid getting too specific with details, since getting into details too quickly can damage discussion's usefulness.

I'll go on by one, trying to demonstrate what I think is important for each.

### Clean
What makes a language clean? This one is probably the most abstract and vague, since there is a million ways to interpret it. I think my definition of clean is pretty concise: "If you read the language like a book, it's wrong. If you read the language like a sticky note, it's right". The obvious example is Java's `AbstractSingletonProxyFactoryBean`. This doesn't only apply to naming though. You shouldn't have to sift through details to find what you're trying to.

And this doesn't apply to the experts of the language. Anyone can get familiar enough with a language that they can understand anything thrown at them. This is mostly about the people just becoming familiar with a language. For that reason, I definitely see C and C++ as un-clean languages. Sure, *you* know C so well that everything just makes sense. But that doesn't apply at all for people new. There's a good reason why a lot of higher-level languages are being used more and more often.

To be continued...
