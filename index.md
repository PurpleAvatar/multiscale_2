---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: single
author_profile: false
---

<html>
  <head>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.css" integrity="sha384-AfEj0r4/OFrOo5t7NnNe46zW/tFgW6x/bCJG8FqQCEo3+Aro6EYUG4+cU+KJWu/X" crossorigin="anonymous">

    <!-- The loading of KaTeX is deferred to speed up page rendering -->
    <script defer src="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/katex.min.js" integrity="sha384-g7c+Jr9ZivxKLnZTDUhnkOnsh30B4H0rpLUpJ4jAIKs4fnJI+sEnkvrMWph2EDg4" crossorigin="anonymous"></script>

    <!-- To automatically render math in text elements, include the auto-render extension: -->
    <script defer src="https://cdn.jsdelivr.net/npm/katex@0.12.0/dist/contrib/auto-render.min.js" integrity="sha384-mll67QQFJfxn0IYznZYonOWZ644AWYC+Pt2cHqMaRhXVrursRwvLnLaebdGIlYNa" crossorigin="anonymous"
        onload="renderMathInElement(document.body);"></script>
  </head>
  ...
</html>

## Title Here

![image-center](assets/images/bio-photo.jpg){: .align-center}
*Could this be a caption?*

The following text should be in-line latex via katex, set in the config yaml file and added to the layout single file $\sqrt{n}$

On its own, would it be automatically centered? 

{% katex %}
c = \pm\sqrt{a^2 + b^2}
{% endkatex %}

We can also checkout footnotes, like This is some text.[^1]. 

Other text.[^footnote].

Welcome to the home page

<div class="row">
  /* Add new profiles, use 3 columns per row div */
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
