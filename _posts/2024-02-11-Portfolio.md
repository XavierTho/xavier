---
layout: game
title: Portfolio
comments: false
type: tangibles
courses: { week: {week: 11} }
---

<style>
  .container {
    transition: 0.15s;
    box-shadow: 1px 1px 1px rgba(0,0,0,0.15);
  }

  .container:hover {
    box-shadow: 2px 2px 2px rgba(0,0,0,0.15);
  }
  
  .project-information {
    text-align: center;
  }

  .project-name {
    font-size: 20px;
    font-weight: bold;
  }

  .project-date {
    font-size: 15px;
    color: grey;
    text-decoration: none;
  }

  .project-date:hover {
    text-decoration: none;
  }
</style>

Code, above all, is not a means of communication between us and computers, but rather, a collection of the most powerful languages in the world, that have and continue to solve the largest problems of the world, and with it transform us into a new age of innovation. Allow my own code to represent to the humble beginnings of an ambitious soul, who like others, desires to use this ability to which is code, to better our world.



<div style="display: grid; grid-template-columns: 1fr 1fr 1fr; margin-bottom: 30px; column-gap: 20px; row-gap: 40px;">

  <!--Container 1-->
  <div class="container">
    <!--Image-->
    <div class="image">
      <a href="{{site.baseurl}}//2023/08/24/tech-journey.html" target="_blank">
        <img src="{{site.baseurl}}/images/Portfolio/cyberaegis.jpg">
      </a>
    </div>
        <!--Project Information-->
        <div class="project-information">
          <p class="project-name">First Blog</p>
        </div>
  </div>

  <!--Container 2-->
  <div class="container">
    <!--Image-->
    <div class="image">
      <a href="{{site.baseurl}}//2023/08/24/tech-journey.html" target="_blank">
        <img src="{{site.baseurl}}/images/Portfolio/css-magic.jpg">
      </a>
    </div>
        <!--Project Information-->
        <div class="project-information">
          <p class="project-name">CSS Magic</p>
        </div>
  </div>

  <!--Container 3-->
  <div class="container">
    <!--Image-->
    <div class="image">
      <a href="{{site.baseurl}}//2023/08/24/tech-journey.html" target="_blank">
        <img src="{{site.baseurl}}/images/Portfolio/snake.jpg">
      </a>
    </div>
        <!--Project Information-->
        <div class="project-information">
          <p class="project-name">Snake</p>
        </div>
  </div>
</div>