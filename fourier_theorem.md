---
layout: page
title: "Fourier Theorem or: How I Learned to Stop Worrying and Love the Math."
date: 2022-09-16
categories: math "electrical engineering" fourier
---

<script>
    var head = document.getElementsByTagName('head');
    head.innerHTML += '<script type="text/javascript" asyncsrc="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML"> </script>'
</script>

<!-- <style> max-width:600px </style> -->

### Fourier Theorem or: How I Learned to Stop Worrying and Love the Math.

I was in my third year of electrical engineering school when shit hit the fan (again?). It was COVID, online school, minimal social interaction, and some pretty hard engineering courses. 

I'd made it out of the first two years of some pretty hard math, science, and introductory electrical engineering courses, but it was time to get royally fucked once again.

Me, in all of my wisdom, had unknowingly decided to take three of the hardest electrical engineering courses for the Fall: Probability for Engineers, Semiconductor Theory, and Signals and Systems/Transform Methods. You'll just have to take me and my fellow engineers' words for it - these were some pretty hard classes.

The usual symptoms of a crazy quarter of school set in - self doubt, anxiety, hopelessness, etc. etc.

Now, these feelings didn't really go away, but getting through this quarter opened me up to a whole new side of engineering and math that made it all pretty exciting. 

We learned a way to break down complex ideas into simpler ones, which is one of my favorite ways of learning.

I think it was Einstein that said something like, "If you can't explain an idea in a simple way, you don't really understand it."

So how did we do this? What's the magic? 

#### $\rightarrow$ Fourier Theorem.

I think I'll do away with the gritty of the mathematics for now, because this is really about getting excited about the math and then letting the details follow.

Say your teacher says to you:

> I've devised a way for different groups of people to talk to each other from all over the world, without any one voice interfering with another! How did I do it?

You might say back: I think you've bought a cellphone.

<img src="./assets/big%20brain%20teacher.png" width="50%" height="50%">

Well, you'd be right, but he does propose an interesting question - how _do_ two people have a conversation on their phones without another phone conversation interfering with it. It's like asking, if we have many pairs of people talking in the same room to each other, how can they hear each other with all the background noise.

Another way to frame the question, interestingly enough, is: if two people are playing the same note on a piano and a flute, how can we tell the intruments apart. A note is, a note, is a note... right?

Well yes... sort of.