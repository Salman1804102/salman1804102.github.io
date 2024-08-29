---
title: ""
excerpt: "My Projects"
author_profile: true
permalink: /projects/
redirect_from: 
  - /about.html
---


<style>
  .projects {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
    grid-auto-rows: 1fr;
    gap: 20px;
  }

  .grid-item {
    display: flex;
    flex-direction: column;
  }

  .card {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    transition: transform 0.2s ease;
  }

  .card:hover {
    transform: translateY(-5px);
  }

  .card img {
    width: 100%;
    height: auto;
    display: block;
    border-top-left-radius: 8px;
    border-top-right-radius: 8px;
  }

  .card-body {
    padding: 15px;
    text-align: center;
  }

  .card-text {
    margin: 0;
    font-weight: bold;
  }
</style>

<div class="container mt-5">
  <div class="post">
    <header class="post-header">
      <h1 class="post-title">Projects</h1>
      <p class="post-description" style="border-bottom: 1px solid #e8e8e8; padding-bottom: 1rem; text-align: left;">
        <em>I have worked on a wide range of projects, spanning areas such as Machine Learning, Natural Language Processing, and Mobile Application Development.</em>
      </p>
    </header>

    <article>
      <div class="projects grid">
        
        <div class="grid-item">
          <a href="https://github.com/Salman1804102/E-Complaint-Android-Application-Flutter" target="_blank">
            <div class="card hoverable">
              <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/e-complaint.jpg" alt="E-Complaint Android Application thumbnail" />
              <div class="card-body">
                <p class="card-text">E-Complaint Android Application (Flutter)</p>
              </div>
            </div>
          </a>
        </div>

        <div class="grid-item">
          <a href="https://github.com/Salman1804102/Bricks-Breaker-Game-Gaphics-OpenGL" target="_blank">
            <div class="card hoverable">
              <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/brickbreaker.png" alt="Bricks Breaker Game thumbnail" />
              <div class="card-body">
                <p class="card-text">Bricks Breaker Game (Graphics with OpenGL)</p>
              </div>
            </div>
          </a>
        </div>

        <div class="grid-item">
          <a href="https://github.com/Salman1804102/Flex-Project-Compiler-Design" target="_blank">
            <div class="card hoverable">
              <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/flex.PNG" alt="Flex Project Compiler Design thumbnail" />
              <div class="card-body">
                <p class="card-text">Flex Project (Compiler Design)</p>
              </div>
            </div>
          </a>
        </div>

        <div class="grid-item">
          <a href="https://github.com/Salman1804102/DravidianLangTech-EACL-2024-HOLD" target="_blank">
            <div class="card hoverable">
              <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/HOLD.PNG" alt="Hate Speech Detection in Dravidian Languages thumbnail" />
              <div class="card-body">
                <p class="card-text">Hate Speech Detection in Dravidian Languages</p>
              </div>
            </div>
          </a>
        </div>

        <div class="grid-item">
          <a href="https://github.com/Salman1804102/DravidianLangTech-EACL-2024-FakeNews" target="_blank">
            <div class="card hoverable">
              <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/Fake.PNG" alt="Fake News Detection in Dravidian Languages thumbnail" />
              <div class="card-body">
                <p class="card-text">Fake News Detection in Dravidian Languages</p>
              </div>
            </div>
          </a>
        </div>

        <div class="grid-item">
          <a href="https://github.com/Salman1804102/CASE-EACL-2024" target="_blank">
            <div class="card hoverable">
              <img src="https://raw.githubusercontent.com/Salman1804102/salman1804102.github.io/master/Gallery/case.PNG" alt="CASE Task EACL 2024 thumbnail" />
              <div class="card-body">
                <p class="card-text">Hate Speech Event Detection, Target Detection and Stance Classification</p>
              </div>
            </div>
          </a>
        </div>

      </div>
    </article>
  </div>
</div>


