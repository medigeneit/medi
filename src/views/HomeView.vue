<script setup></script>

<template>
  <main class="min-h-screen bg-gray-50 text-gray-800">
    <section class="bg-blue-100 py-24 text-center">
      <div class="max-w-4xl mx-auto px-4">
        <h1 class="text-5xl font-bold text-blue-700 mb-6">Welcome to MEDI</h1>
        <p class="text-lg text-gray-700 mb-8">
          Empowering the future of healthcare through technology, training, and innovation.
        </p>
        <div class="flex justify-center space-x-4">
          <RouterLink
            to="/about"
            class="px-6 py-3 bg-blue-600 text-white rounded-xl hover:bg-blue-700"
            >Learn More</RouterLink
          >
          <a
            href="#programs"
            class="px-6 py-3 border border-blue-600 text-blue-600 rounded-xl hover:bg-blue-50"
            >Our Programs</a
          >
        </div>
      </div>
    </section>

    <section id="programs" class="py-20 px-4 max-w-6xl mx-auto">
      <h2 class="text-3xl font-semibold text-center mb-12">Our Key Programs</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-bold mb-2">E-Learning Platform</h3>
          <p class="text-gray-600">
            Interactive online courses for medical students and professionals to enhance their
            knowledge.
          </p>
        </div>
        <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-bold mb-2">Training & Workshops</h3>
          <p class="text-gray-600">
            Live sessions and expert-led seminars designed to develop critical healthcare skills.
          </p>
        </div>
        <div class="bg-white p-6 rounded-2xl shadow hover:shadow-lg transition">
          <h3 class="text-xl font-bold mb-2">Custom IT Solutions</h3>
          <p class="text-gray-600">
            Tailored software solutions for educational institutions and healthcare providers.
          </p>
        </div>
      </div>
    </section>

    <section class="bg-blue-50 py-20 text-center">
      <h2 class="text-3xl font-bold text-gray-800 mb-6">Join the MEDI Movement</h2>
      <p class="text-gray-600 mb-8">
        Be a part of the transformation in medical education and healthcare innovation.
      </p>
      <RouterLink
        to="/contact"
        class="px-8 py-4 bg-blue-600 text-white text-lg font-semibold rounded-xl hover:bg-blue-700"
        >Get in Touch</RouterLink
      >
    </section>
  </main>
</template>
