# Drmo_ali
Mo ali
<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Digital vCard</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css" rel="stylesheet">
  <script src="https://cdnjs.cloudflare.com/ajax/libs/typed.js/2.0.12/typed.min.js"></script>
  <style>
    body {
      background-color: #121212;
      color: #f0f0f0;
      font-family: 'Arial', sans-serif;
    }

    .neon-text {
      color: #00ffc8;
      text-shadow: 0 0 5px #00ffc8, 0 0 10px #00ffc8, 0 0 15px #00ffc8;
    }

    .neon-button {
      background-color: #00ffc8;
      color: #121212;
      border-radius: 12px;
      padding: 12px 24px;
      font-size: 16px;
      font-weight: 600;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .neon-button:hover {
      transform: scale(1.05);
      box-shadow: 0 0 20px #00ffc8, 0 0 30px #00ffc8, 0 0 40px #00ffc8;
    }

    .social-button {
      font-size: 24px;
      padding: 15px;
      margin: 10px;
      color: #00ffc8;
      border: 2px solid #00ffc8;
      border-radius: 50%;
      transition: transform 0.3s ease;
    }

    .social-button:hover {
      transform: scale(1.1);
      background-color: #00ffc8;
      color: #121212;
    }

    .profile-image {
      border: 5px solid #00ffc8;
    }
  </style>
</head>

<body class="font-sans">

  <header class="text-center py-10">
    <!-- Profile Picture -->
    <img src="https://via.placeholder.com/150" alt="Profile Picture" class="mx-auto rounded-full profile-image w-36 h-36 mb-4">
    <h1 class="text-4xl font-semibold text-white">John Doe</h1>
    <p class="text-xl text-gray-400">Web Developer & Designer</p>
  </header>

  <!-- Bio Section -->
  <section class="text-center py-10 px-5">
    <p class="text-lg text-gray-300">
      Hi, I'm John, a passionate web developer and designer with a love for creating beautiful and user-friendly digital experiences. Let's connect and collaborate on exciting projects.
    </p>
  </section>

  <!-- Contact Info -->
  <section class="flex justify-center gap-10 py-10">
    <a href="tel:+1234567890" class="text-gray-300 hover:text-white transition duration-300">
      <i class="fas fa-phone-alt text-3xl"></i>
      <p class="text-gray-400 mt-2">Call</p>
    </a>
    <a href="mailto:john.doe@example.com" class="text-gray-300 hover:text-white transition duration-300">
      <i class="fas fa-envelope text-3xl"></i>
      <p class="text-gray-400 mt-2">Email</p>
    </a>
  </section>

  <!-- Social Links -->
  <section class="flex justify-center gap-8 py-10">
    <a href="https://wa.me/1234567890" target="_blank" class="social-button">
      <i class="fab fa-whatsapp"></i>
    </a>
    <a href="https://linkedin.com/in/johndoe" target="_blank" class="social-button">
      <i class="fab fa-linkedin"></i>
    </a>
    <a href="https://instagram.com/johndoe" target="_blank" class="social-button">
      <i class="fab fa-instagram"></i>
    </a>
    <a href="https://johndoe.com" target="_blank" class="social-button">
      <i class="fas fa-globe"></i>
    </a>
  </section>

  <!-- Save Contact Button -->
  <section class="text-center py-10">
    <a href="data:text/vcard;charset=utf-8,BEGIN:VCARD%0AVERSION:3.0%0AN:John Doe%0AEMAIL:john.doe@example.com%0APHONE:+1234567890%0AEND:VCARD" 
       download="John_Doe.vcf" class="neon-button">
      Save Contact
    </a>
  </section>

  <!-- Footer -->
  <footer class="text-center py-5">
    <p class="text-gray-400">&copy; 2026 John Doe. All Rights Reserved.</p>
  </footer>

  <script>
    // Optional: Typewriter effect for the name
    var options = {
      strings: ["Web Developer", "Designer", "Creator", "Technologist"],
      typeSpeed: 80,
      backSpeed: 60,
      backDelay: 1000,
      loop: true
    };
    var typed = new Typed(".text-xl", options);
  </script>

</body>

</html>
