---
layout: page
title: About
permalink: /about me/
---

<div class="man-title">
  <center>GitHub Repository
    <h2><a href="http://github.com/Marslo"><i class="fa fa-github"></i></a></h2>
  </center>
</div>
<div class="intro">
  <br />
  <p>
    Hello there! :)
    <br />
    <br /> This is Marslo
    <br /> I'm a DevOps engineer.
    <br />
    <br />
    <a href="http://facebook.com/hemangkr"><i class="fa fa-facebook"></i></a> &nbsp; &nbsp; &nbsp;<a href="http://github.com/hemangsk"><i class="fa fa-github"></i></a>
  </p>
</div>

<div class="manual manual-title">
  Posting
  </div>

<p>  <div class="manual-content">

      - Create a .markdown file inside <code class="highlighter-rouge">_posts</code> folder.<br />
      - Name the file according to the format YY-MM-DD-[short name for your post].<br />
      &nbsp;&nbsp;&nbsp;<code>2016-03-30-i-love-design.markdown</code><br />
      - Write the <a href="jekyll">Front Matter</a> and content in the file.<br><br>
      <div class="example">

        <div class="highlight">
        <pre>
          ---
          layout: post | default | page
          title:  String<span class="hint"> Post Title</span>
          date:   Time Stamp
          categories: String | Array of Strings<span class="hint"> Category / Categories </span>
          ---
        </pre>
        </div>

      </div>
      <div class="example">
        <div class="highlight">
        <pre>
        ---
        layout: post
        title:  "The One with the Blackout"
        date:   2016-03-30 19:45:31 +0530
        categories: ["life", "friends"]
        ---
      </pre>
    </div>
      </div>



</p>
</div>
<p><br /></p>

  <div class="manual manual-title">
  Create Pages
  </div>
<p>  <div class="manual-content">

      - Create a .md file in the root directory.<br />
      - Name the file with the desired page link name.<br />
        &nbsp;&nbsp;&nbsp;<code>about.md</code><br />
          &nbsp;&nbsp;&nbsp;<code>design.md</code><br />
      - Write the <a href="jekyll">Front Matter</a> and content in the file.<br><br>
      <div class="highlight">


        <pre>
          ---
          layout: page
          title: String <span class="hint">Title of the webpage</span>
          permalink: / String / <span class="hint">Permalink for the webpage</span>
          tagline: String <span class="hint">Optional DevJournal Feature : Tagline for the page</span>
          ---
      </pre><br />
    </div><br>
      <div class="highlight">

        <pre>
        ---
        layout: page
        title:  "Science"
        permalink:   /science/
        tagline : "Humanity is overrated."
        ---
      </pre>
      </div>


  </div>
</p>
