---
title: Blog
layout: 'layouts/page.html'
custom_css: "
p, h3{
  color: white;
}
main p, main h3{
  color:black;
  }
main li{
  padding: 2rem;
  background-color: #FFA015;
}
main img{
  width:40rem;
}
@media (min-width: 800px) {
  main li{
    display: grid;
    grid-template-columns: 2;
    column-gap:2rem;
  }
  .een{
    grid-column: 1;
  }
  .twee{
    grid-column: 2;}
}"
---

<ul class="blog">
<li>
<div class="een">
  <h3>How To Get Dark Mode Design Right</h3>
  <p style="font-style:italic;"> - Dark themes are everywhere these days. - </p>

  <p>As human beings continue to spend more of their time interacting with technology, dark themes provide a more relaxing way to engage with the digital world. More often than not, these themes are easier on the eyes, more attractive, and perfect for the dedicated user. <a href="/post/dark-design/">continue reading...</a></p>
</div>
<div class="twee">
  <img src="/img/darkMode1.jpg" alt="">
</div>
</li>
<li>
<div class="een">
  <h3>Exciting New Tools for Designers, September 2020</h3>
  <p>It’s fun to see new website design tools that reflect current times and the state of the world. That’s very true this month with new databases devoted to diversity and women in technology, as well and resources to make your design life easier. <a href="/post/design-tools/">continue reading...</a></p>
</div>
<div class="twee">
  <img src="/img/designTools1.png" alt="">
</div>
</li></ul>
