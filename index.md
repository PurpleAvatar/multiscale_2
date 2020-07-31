---
layout: single
author_profile: false
---

## Title Here

![image-center](assets/images/bio-photo.jpg){: .align-center}
*Could this be a caption?*

The following text should be in-line latex via katex, set in the config yaml file and added to the layout single file $$\sqrt{n}$$

$$ X = \sqrt{n+1} $$

On its own, would it be automatically centered? 

We can also checkout footnotes, like This is some text.[^1]. 

Other text.[^footnote].

Welcome to the home page

<div class="row">
  /* Add new profiles, use 2 columns per row div */
  <div class="column">
    <div class="card">
      <img src="assets/images/bio-photo.jpg" alt="Jane" style="border-radius: 50%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Some text that describes me lorem ipsum ipsum lorem.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
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
</div>

Try not to repeat the title with a wide layout, but did that pound sign break everything? Return back to the single format

Where does this (here) text go? (index.md) Changing as we go10

Classes: wide" extends content to the right of this page. This is the home page, (now) featured in the navigation bar

Adding the video here: 
Note how the frameborder is set to 1, width/height originally set to 640/360

<iframe width="640" height="360" src="https://www.youtube-nocookie.com/embed/l2Of1-d5E5o?start=210" frameborder="0" allowfullscreen></iframe>

Here's some content after the video to check the formatting

[^1]: This is the content of the first footnote
[^footnote]: Here's the second footnote content
