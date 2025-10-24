<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Barretto SHS Information Management System (BSHSIMS)</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap');
    body {
      font-family: 'Poppins', sans-serif;
      background: radial-gradient(circle at top, #0f172a 0%, #1e293b 60%, #0f172a 100%);
      color: white;
      overflow-x: hidden;
    }
    .fade-in {
      animation: fadeIn 1s ease-in-out;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>

<body class="min-h-screen flex flex-col items-center">

  
  <header class="w-full bg-slate-900/80 backdrop-blur-md border-b border-slate-700 fixed top-0 left-0 z-50 shadow-md">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 py-3 flex flex-wrap items-center justify-between gap-3">
      <div class="flex items-center space-x-3">
        <img src="se.png" alt="School Logo" class="w-10 h-10 rounded-full border border-slate-600">
        <h1 class="text-base sm:text-lg md:text-xl font-semibold text-blue-300 leading-tight">
          Barretto SHS Information Management System (BSHSIMS)
        </h1>
      </div>
    </div>
  </header>

  
  <main class="flex flex-col items-center justify-center flex-grow mt-28 sm:mt-32 fade-in text-center px-4 sm:px-6">

    <h1 class="text-3xl sm:text-5xl md:text-6xl font-extrabold tracking-wide mb-4 bg-gradient-to-r from-blue-400 via-green-400 to-teal-300 text-transparent bg-clip-text leading-snug">
      Barretto SHS Information Management System (BSHSIMS)
    </h1>

    <p class="text-slate-400 max-w-2xl mx-auto text-sm sm:text-base leading-relaxed mb-6">
      Aims to efficiently manage and organize school information, allowing administrators to record grades and student data accurately while giving students easy access to their academic records.
    </p>

    
    <section class="flex flex-col sm:flex-row justify-center gap-6 sm:gap-10 mt-10 sm:mt-20 fade-in w-full max-w-4xl px-4">

     
      <div class="bg-slate-800/70 backdrop-blur-xl rounded-2xl shadow-2xl border border-green-500/40 p-6 sm:p-8 w-full sm:w-80 hover:scale-105 hover:shadow-green-500/40 transition duration-300">
        <h3 class="text-lg sm:text-xl font-semibold mb-3 text-green-400">Admin Portal</h3>
        <p class="text-slate-400 text-sm mb-6 leading-relaxed">
          Manage student records, input grades, and track performance securely and efficiently.
        </p>
        <a href="admin-login.html" class="block text-center bg-green-600 hover:bg-green-500 transition py-2.5 rounded-lg font-medium text-sm">
          Go to Admin Login
        </a>
      </div>

     
      <div class="bg-slate-800/70 backdrop-blur-xl rounded-2xl shadow-2xl border border-blue-500/40 p-6 sm:p-8 w-full sm:w-80 hover:scale-105 hover:shadow-blue-500/40 transition duration-300">
        <h3 class="text-lg sm:text-xl font-semibold mb-3 text-blue-400">Student Portal</h3>
        <p class="text-slate-400 text-sm mb-6 leading-relaxed">
          View grades, monitor progress, and access your academic information anytime.
        </p>
        <a href="studentlogin.html" class="block text-center bg-blue-600 hover:bg-blue-500 transition py-2.5 rounded-lg font-medium text-sm">
          Go to Student Login
        </a>
      </div>

    </section>
  </main>

 
  <footer class="text-slate-500 text-xs text-center mt-16 mb-6 fade-in px-4">
    © 2025 Barretto Senior High School
  </footer>

</body>
</html>
