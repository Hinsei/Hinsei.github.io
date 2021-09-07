---
layout: post
title: "My Experience with Imba"
date: 2021-09-07 20:37:11 +0800
categories: jekyll update
---

> Imba is a Web programming language that's fast due to it's time saving syntax and memoized DOM

I'm a big fan of tools that reduces working time since there's only 2 developers max in my current company. Less frontend work means more time to dedicate to backend or devops shenanigans.

My main frontend stack at the moment is [Vue](https://vuejs.org/) while I have a couple of other smaller projects running on [Reef](https://reefjs.com/) and [Svelte](https://svelte.dev/).

I enjoy tinkering around with new things, said thing being able to save me time made picking it up all the more enticing. I don't really have an opinion on having a memoized DOM versus a virtual DOM since I'm not knowledgeable on the subject matter at the moment.

Installing it was straight forward. It can be done by just following the instructions on their homepage. Most web developers have `node` already installed in their machines so you just need to run their project creation command and you're good to go. I did not have to do any tweaking to the pregenerated files to start.

Picking up the syntax is fairly straight forward. Indentation is an integral part of the language to make sure everything is compiled properly. 

```html
<!-- normal html & css -->
<style>
  p {
    color: red;
  }
</style>
<div>
  <p>
    Hello
  </p>
</div>
 ```

 ```imba
# imba html & css
css p
  c: red

tag hello-container
  <self>
    <div>
      <p> "Hello"
 ```

Writing plain html and css was truly a joy. I find plain html and css to be unreadable and a pain to work with once my projects reach a certain size. Cutting the bottom portion of my html pyramid was sweet.

Further testing is still required before I add Imba as a staple in my full time work tool box. If you're a beginner I'd actually recommend sticking to plain old html and css until you reach a point where the annoyance is unbearable. 

I'll be releasing more posts detailing some of the tinkering I did as a sort of tutorial/guide for people starting out.
