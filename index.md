---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: false
---

Different options for figure captions: https://stackoverflow.com/questions/19331362/using-an-image-caption-in-markdown-jekyll

![image-center](assets/images/bio-photo.jpg){: .align-center}
*Could this be a caption?*

We can also checkout footnotes, like This is some text.[^1]. Other text.[^footnote].

Welcome to the home page

<div class="row">
  <div class="column">
    <div class="card">
      <img src="assets/images/bio-photo.jpg" alt="Jane" style="width:100%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>

Try not to repeat the title with a wide layout, but did that pound sign break everything? Return back to the single format

<div class="testBreak"> Text here with margins apparently, reaching across the sides </div>

Where does this (here) text go? (index.md) Changing as we go10

Classes: wide" extends content to the right of this page. This is the home page, (now) featured in the navigation bar

Adding the video here: 
Note how the frameborder is set to 1

<iframe width="640" height="360" src="https://www.youtube-nocookie.com/embed/l2Of1-d5E5o?start=210" frameborder="0" allowfullscreen></iframe>

Here's some content after the video to check the formatting

[^1]: This is the content of the first footnote
[^footnote]: Here's the second footnote content
