<script setup></script>

<template>
  <main class="min-h-screen text-gray-800">
    <!-- Contact Hero Section -->
    <section class="bg-blue-100 py-24 text-center">
      <div class="max-w-4xl mx-auto px-4">
        <h1 class="text-4xl font-bold text-blue-700 mb-4">Get in Touch</h1>
        <p class="text-lg text-gray-700">
          Have questions or want to collaborate? Reach out to us anytime.
        </p>
      </div>
    </section>

    <!-- Contact Form Section -->
    <section class="py-20 px-4 max-w-3xl mx-auto">
      <form class="bg-white p-8 rounded-2xl shadow space-y-6">
        <div>
          <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Your Name</label>
          <input
            type="text"
            id="name"
            name="name"
            class="w-full p-3 border border-gray-300 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500"
            required
          />
        </div>

        <div>
          <label for="email" class="block text-sm font-medium text-gray-700 mb-1"
            >Email Address</label
          >
          <input
            type="email"
            id="email"
            name="email"
            class="w-full p-3 border border-gray-300 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500"
            required
          />
        </div>

        <div>
          <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
          <textarea
            id="message"
            name="message"
            rows="5"
            class="w-full p-3 border border-gray-300 rounded-xl focus:outline-none focus:ring-2 focus:ring-blue-500"
            required
          ></textarea>
        </div>

        <button
          type="submit"
          class="w-full bg-blue-600 text-white py-3 rounded-xl font-semibold hover:bg-blue-700"
        >
          Send Message
        </button>
      </form>
    </section>

    <!-- Contact Info Section -->
    <section class="bg-blue-100 py-12 px-4">
      <div class="max-w-4xl mx-auto text-center">
        <p class="text-gray-700 text-lg mb-2">Email: office@medi.academy</p>
        <p class="text-gray-700 text-lg mb-2">Phone: +880-1759-584-836</p>
        <p class="text-gray-700 text-lg">
          Address: 230 Rajmonjil, Elephant Road, Dhaka-1205, Bangladesh
        </p>
      </div>
    </section>
  </main>
</template>
