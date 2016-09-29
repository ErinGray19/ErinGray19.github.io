---
layout: page
title : About
permalink: /about/
---


<h2>ErinGray19</h2>
<p>This site is the about me for ErinGray19<br>For INLS 161 Assignment 2.</p>
<br>

Welcome to my About Me Page! 
To be honest, this whole coding thing is still incredibly new to me, and still pretty intimidating, but this class is giving me more confidence every day! 

I wasn't sure exactly what I wanted to put in this post, so I thought I'd talk about the subject I know the most about,  **ME**

I got my undergraduate degree in Pscyhology from Appalachian State University ![alt text](https://mgtvsportzedge.files.wordpress.com/2014/08/app-st.gif)

<img src="/_resources/Appalachian_State_Mountaineers03.jpg" alt="appstate logo">

<iframe width="560" height="315" src="https://www.youtube.com/embed/QdDzRqC6-0U" frameborder="0" allowfullscreen></iframe>

I have a few obsessions: 

- Pizza ![pizza logo](http://slice.seriouseats.com/images/20110419-corner-slice-8th-and-31st-1.jpg)

- Mythology

- Game of Thrones ![got logo](http://cdn.wccftech.com/wp-content/uploads/2015/05/GoT.png)

I hope you enjoyed my post, and I'm excited to learn more!

<center><p ><strong><span class="manual">Get up and running with</span> Gravity</strong></p></center>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Posting</strong>
  </div>
<p>  <div class="manual-content">

      - Write the <a href="jekyll">Front Matter</a> and content in the file.<br>
      <div class="example">
        <span class='manual'>FORMAT</span><BR>
        <pre>---
layout: post | default | page
title:  String<span class="hint"> Post Title</span>
date:   Time Stamp
categories: String | Array of Strings<span class="hint"> Category / Categories </span>
---</pre>
      </div>
      <div class="example">

        <pre>---
layout: post
title:  "The One with the Blackout"
date:   2016-03-30 19:45:31 +0530
categories: ["life", "friends"]
---</pre>
      </div>


  </div>
</p>
</div>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Create Pages</strong>
  </div>
<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br>
      - Name the file with the desired page link name.<br>  <code>about.md</code><br><code>design.md</code><br>
      - Write the <a href="jekyll">Front Matter</a> and content in the file.
      <div class="example">
        <span class='manual'>FORMAT</span><BR>
        <pre>---
layout: page
title: String <span class="hint">Title of the webpage</span>
permalink: / String / <span class="hint">Permalink for the webpage</span>
tagline: String <span class="hint">Optional Gravity Feature : Tagline for the page</span>
---</pre>
      </div>
      <div class="example">

        <pre>---
layout: page
title:  "Science"
permalink:   /science/
tagline : "Humanity is overrated."
---</pre>
      </div>


  </div>
</p>
</div>
<br>
<div class="manual-post">
  <div class="manual manual-title">
  <strong>Create Archives/ Category Pages</strong><br>
</div><br>
<div class="archiveIntro">
  <p>
    Introducing <strong>Archive Pages</strong>.<br></p>
  <span class="archive-intro">  You can display a list of all the post corresponding to a particular category on a standalone Page using the <code>'archive'</code> layout.
</span>
</div>
<br>

<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br>
      - Name the file. Preferred name will be the name of the category<br>  <code>life.md</code><br>
      - Write the <a href="jekyll">Front Matter</a> and content in the file.
      <div class="example">
        <span class='manual'>FORMAT</span><BR>
    <pre>---
layout: archive<span class="hint"> Archive Page Layout</span>
title: String <span class="hint">Title of the webpage</span>
permalink: / String / <span class="hint">Permalink for the webpage</span>
tagline: String <span class="hint"> Tagline for the page</span>
category : String <span class="hint"> Name of the category of which the page will show posts.</span>
---</pre>
      </div>
      <div class="example">


    </div><br>
  </div>
</p>
</div>
