---
layout: none
title: "Home"
permalink: /
---

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Srishti Tripathy</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      padding: 0;
      background: linear-gradient(145deg, #0f2027, #203a43, #2c5364);
      color: #fefefe;
      font-family: 'Inter', sans-serif;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      text-align: center;
      overflow: hidden;
    }

    .container {
      padding: 2rem;
      animation: fadeIn 1.2s ease-in-out forwards;
    }

    h1 {
      font-size: 2.8rem;
      font-weight: 600;
      margin-bottom: 1rem;
      opacity: 0;
      animation: slideIn 1s ease-out forwards;
    }

    p {
      font-size: 1.1rem;
      max-width: 500px;
      margin: 0 auto 2rem auto;
      line-height: 1.6;
      color: #ccc;
      opacity: 0;
      animation: fadeIn 2s ease-in-out forwards;
      animation-delay: 0.8s;
    }

    .btn {
      display: inline-block;
      padding: 0.7rem 1.4rem;
      background-color: #00bcd4;
      color: #fff;
      text-decoration: none;
      font-weight: 600;
      border-radius: 8px;
      transition: background-color 0.3s ease;
      opacity: 0;
      animation: fadeIn 2s ease-in-out forwards;
      animation-delay: 1.4s;
    }

    .btn:hover {
      background-color: #0097a7;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    @keyframes slideIn {
      0% { opacity: 0; transform: translateY(-40px); }
      100% { opacity: 1; transform: translateY(0); }
    }

    @media (max-width: 600px) {
      h1 {
        font-size: 2rem;
      }

      p {
        font-size: 1rem;
        padding: 0 1rem;
      }
    }
  </style>
</head>
<body>

  <div class="container">
    <h1>Hi, I'm Srishti</h1>

  <p class="lead">
    I am an economics and finance researcher passionate about decoding the world’s most pressing challenges. My work lies at the intersection of global macro trends, data analysis, and policy insight — bridging complex ideas and real-world impact.
  </p>

  <em>"I write about how the world works — and sometimes, how it doesn’t."</em>
    <a href="/about/" class="btn">Explore More</a>
  </div>

</body>
</html>
