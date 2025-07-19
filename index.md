---
layout: page
title: "Home"
permalink: /
---

<style>
  body {
    background-color: #1e1e1e;
    color: #f0f0f0;
    font-family: 'Segoe UI', sans-serif;
    margin: 0;
    padding: 0;
  }

  .homepage-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 5vh 5vw;
    text-align: center;
  }

  .homepage-container img {
    width: 40vw;
    max-width: 200px;
    height: auto;
    border-radius: 50%;
    object-fit: cover;
    box-shadow: 0 0 15px rgba(0,0,0,0.3);
    margin-bottom: 1rem;
  }

  .homepage-container h1 {
    font-size: 6vw;
    max-width: 90%;
    white-space: nowrap;
    overflow: hidden;
    border-right: 0.15em solid #f0f0f0;
    animation: typing 3s steps(30, end), blink 0.75s step-end infinite;
  }

  @keyframes typing {
    from { width: 0 }
    to { width: 100% }
  }

  @keyframes blink {
    50% { border-color: transparent }
  }

  .lead {
    font-size: 1.1rem;
    margin: 1rem 0;
    max-width: 600px;
  }

  em {
    font-style: italic;
    color: #aaa;
    margin-top: 1rem;
  }

  .homepage-button {
    margin-top: 2rem;
  }

  .homepage-button a {
    display: inline-block;
    padding: 0.6rem 1.2rem;
    background-color: #005577;
    color: white;
    text-decoration: none;
    border-radius: 6px;
    transition: background-color 0.3s ease;
    font-size: 1rem;
  }

  .homepage-button a:hover {
    background-color: #003f5c;
  }

  @media (max-width: 600px) {
    .homepage-container h1 {
      font-size: 8vw;
    }

    .lead {
      font-size: 1rem;
    }

    .homepage-container img {
      width: 50vw;
      max-width: 150px;
    }
  }
</style>

<div class="homepage-container">
  <img src="/assets/images/Untitled design.png" alt="Srishti Tripathy">

  <h1>Hi, I'm Srishti</h1>

  <p class="lead">
    I am an economics and finance researcher passionate about decoding the world’s most pressing challenges. My work lies at the intersection of global macro trends, data analysis, and policy insight — bridging complex ideas and real-world impact.
  </p>

  <em>"I write about how the world works — and sometimes, how it doesn’t."</em>

  <div class="homepage-button">
    <a href="/about/">Explore More</a>
  </div>
</div>
