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
      <img src="assets/images/Phillip_Compeau.JPG" alt="Jane" style="display:block; margin:auto; width:90%; border-radius:50%">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p markdown="1"> [Phillip Compeau](http://compeau.cbd.cmu.edu) is an Associate Teaching Professor and the Assistant Department Head for Education in the [Computational Biology Department](http://cbd.cmu.edu) in Carnegie Mellon University's School of Computer Science. He directs the [undergraduate program in computational biology](http://www.cbd.cmu.edu/education/bs-in-computational-biology/), co-directs the Precollege Program in Computational Biology (http://www.cbd.cmu.edu/education/pre-college-program-in-computational-biology/), and serves as Assistant Director of the Master's in Computational Biology program (http://www.cmu.edu/ms-compbio/).

Phillip is passionate about open online education, and his education projects have reached hundreds of thousands of learners around the world. He is the co-author of Bioinformatics Algorithms: An Active Learning Approach (http://bioinformaticsalgorithms.org), which has been adopted in over 140 institutions around the world. This textbook powers the popular Bioinformatics Specialization on Coursera (https://www.coursera.org/specializations/bioinformatics). He co-founded the learning platform Rosalind (http://rosalind.info) for learning programming, bioinformatics, and algorithms through independent problem solving.  Finally, Phillip is the founder of Programming for Lovers (http://compeau.cbd.cmu.edu/programming-for-lovers/), an online course in introductory programming motivated by fun scientific applications.</p>
        <p>example@example.com</p>
        <p><button class="button">Contact</button></p>
      </div>
    </div>
  </div>
  <div class="column">
    <div class="card">
      <img src="assets/images/190820_Comp Bio_LEE_CHRIS_107.jpg" alt="Jane" style="display:block; margin:auto; width:90%; border-radius:50">
      <div class="container">
        <h2>Jane Doe</h2>
        <p class="title">CEO &amp; Founder</p>
        <p>Chris Lee is a current graduate student at Carnegie Mellon University and is in the M.S. in Computational Biology Program. Previously, he was an undergraduate student at Rutgers University and worked as an undergraduate researcher studying hydrothermal vent bacteria. In 2019, Chris graduated magna cum laude with a B.A. in Molecular Biology & Biochemistry and double minor in Chemistry and Computer Science. He is currently interested in the fields of bioinformatics and genomics.</p>
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
