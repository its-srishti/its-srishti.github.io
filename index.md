<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Srishti | Homepage</title>
  <link href="https://fonts.googleapis.com/css2?family=Cheltenham:wght@700&family=Lora:ital,wght@0,400;0,600;1,400&display=swap" rel="stylesheet" />
  <style>
    :root {
      --bg-dark: #111;
      --text-primary: #d4f1f9; /* electric teal */
      --text-secondary: #cccccc;
      --font-heading: 'Cheltenham', serif;
      --font-body: 'Lora', serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: var(--font-body);
      background: var(--bg-dark);
      color: var(--text-secondary);
      overflow-x: hidden;
      height: 100vh;
      display: flex;
      align-items: center;
      justify-content: center;
      padding: 2rem;
      animation: subtleZoom 30s infinite alternate ease-in-out;
    }

    @keyframes subtleZoom {
      0% { transform: scale(1); }
      100% { transform: scale(1.01); }
    }

    .container {
      max-width: 1000px;
      display: flex;
      flex-direction: row;
      align-items: center;
      gap: 3rem;
      flex-wrap: wrap;
      opacity: 0;
      animation: fadeIn 2s ease 2.5s forwards;
    }

    @keyframes fadeIn {
      to { opacity: 1; }
    }

    .text-content {
      flex: 1 1 400px;
    }

    .typewriter {
      font-family: var(--font-heading);
      font-size: 2.5rem;
      color: var(--text-primary);
      overflow: hidden;
      white-space: nowrap;
      border-right: 0.15em solid var(--text-primary);
      width: 0;
      animation: typing 2s steps(14, end), blink-caret 0.7s step-end infinite;
    }

    @keyframes typing {
      from { width: 0 }
      to { width: 9ch }
    }

    @keyframes blink-caret {
      50% { border-color: transparent; }
    }

    .description {
      margin-top: 1.5rem;
      font-size: 1.1rem;
      line-height: 1.6;
    }

    .poetic-line {
      margin-top: 1.2rem;
      font-style: italic;
      font-weight: 400;
      font-size: 1rem;
      color: #aaa;
    }

    .portrait {
      flex: 1 1 300px;
      max-width: 300px;
    }

    .portrait img {
      width: 100%;
      height: auto;
      border-radius: 1rem;
      object-fit: cover;
    }

    @media (max-width: 768px) {
      .container {
        flex-direction: column;
        align-items: center;
        text-align: center;
      }
      .portrait {
        max-width: 200px;
      }
    }
  </style>
</head>
<body>
  <div class="text-content">
    <div class="typewriter">I am Srishti.</div>
  </div>

  <div class="container">
    <div class="text-content">
      <p class="description">
        I am an economics and finance researcher passionate about decoding the world’s most pressing challenges. My work lies at the intersection of global macro trends, data analysis, and policy insight — bridging complex ideas and real-world impact.
      </p>
      <p class="poetic-line">
        “I write about how the world works — and sometimes, how it doesn’t.”
      </p>
    </div>
    <div class="portrait">
      <img src="portrait.jpg" alt="Portrait of Srishti" />
    </div>
  </div>

  <script>
    // Delay the fade-in of container to match typewriter timing
    window.addEventListener('DOMContentLoaded', () => {
      const container = document.querySelector('.container');
      setTimeout(() => {
        container.classList.add('visible');
      }, 2500);
    });
  </script>
</body>
</html>
