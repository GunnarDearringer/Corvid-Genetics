<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Project Corvus: The Origins of Belief</title>

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- GSAP and ScrollTrigger -->
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/gsap.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.2/ScrollTrigger.min.js"></script>

  <link rel="stylesheet" href="style.css">
</head>

<body class="bg-black text-white overflow-x-hidden">
<!-- Flying Crows Container -->
<div id="crow-container" class="fixed top-0 left-0 w-full h-full pointer-events-none z-0">
  <!-- Crow 1 -->
  <svg class="crow absolute w-12 h-12 text-white opacity-20" viewBox="0 0 24 24" fill="currentColor">
    <path d="M5 2L3 6l3 1-2 5 5-2 1 3 3-1 2 5 5-2 1 3 4-8-8-4-3-5-6-1z"/>
  </svg>

  <!-- Crow 2 -->
  <svg class="crow absolute w-16 h-16 text-white opacity-10" viewBox="0 0 24 24" fill="currentColor">
    <path d="M5 2L3 6l3 1-2 5 5-2 1 3 3-1 2 5 5-2 1 3 4-8-8-4-3-5-6-1z"/>
  </svg>

  <!-- Crow 3 -->
  <svg class="crow absolute w-8 h-8 text-white opacity-15" viewBox="0 0 24 24" fill="currentColor">
    <path d="M5 2L3 6l3 1-2 5 5-2 1 3 3-1 2 5 5-2 1 3 4-8-8-4-3-5-6-1z"/>
  </svg>
</div>

  <!-- Hero Section -->
  <section class="h-screen flex items-center justify-center text-center">
    <div>
      <h1 class="text-5xl font-bold mb-4 animate-fade">Project Corvus</h1>
      <p class="text-xl">The Origins of Belief</p>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="min-h-screen flex items-center justify-center p-8">
    <div class="max-w-2xl">
      <h2 class="text-3xl font-semibold mb-4">About the Experiment</h2>
      <p class="text-lg">What happens when crows achieve human-level intelligence? Can we witness the birth of mythology, culture, and belief?</p>
    </div>
  </section>

  <!-- Research Logs Section -->
  <section id="logs" class="min-h-screen flex flex-col items-center justify-center p-8 space-y-8">
    <div class="max-w-2xl">
      <h2 class="text-3xl font-semibold mb-4">Research Logs</h2>
      <div class="space-y-6">
        <div class="log bg-gray-800 p-4 rounded-lg">Day 1: Early tool improvement observed.</div>
        <div class="log bg-gray-800 p-4 rounded-lg">Day 30: Ritualistic behavior around shiny objects.</div>
        <div class="log bg-gray-800 p-4 rounded-lg">Day 100: Emergence of symbolic "totems."</div>
      </div>
    </div>
  </section>

  <!-- Conclusion Section -->
  <section id="conclusion" class="min-h-screen flex items-center justify-center p-8">
    <div class="max-w-2xl">
      <h2 class="text-3xl font-semibold mb-4">Conclusions</h2>
      <p class="text-lg">The crow civilization gives us a rare glimpse into the pure evolution of belief systems, myths, and cultures.</p>
    </div>
  </section>

  <script src="scripts.js"></script>
</body>
</html>

