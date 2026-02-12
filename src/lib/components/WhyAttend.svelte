<script lang="ts">
  // WhyAttend component
</script>

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200" id="events">
  <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium mb-16 text-gray-950">The Shipyard Experience</h2>

  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <!-- Left Content -->
    <div class="lg:col-span-5 flex flex-col gap-16">
      
      <!-- Item 1 -->
      <div>
        <h3 class="text-xl font-medium mb-3 text-gray-950">Monthly Build Nights</h3>
        <p class="text-sm leading-relaxed text-gray-600">
          Our consistent cadence builds habit and loyalty. Every month, we gather for high-energy build sessions, workshops, and live demos. It's where the distance between idea and production collapses.
        </p>
      </div>

      <!-- Item 2 -->
      <div>
        <h3 class="text-xl font-medium mb-3 text-gray-950">Full-Stack Building</h3>
        <p class="text-sm leading-relaxed text-gray-600 mb-4">
          We don't just code. Shipyard treats design, engineering, marketing, and launch as first-class citizens. Whether you're a developer, designer, or founder, you'll find your tribe here.
        </p>
      </div>

      <!-- Item 3 -->
      <div>
        <h3 class="text-xl font-medium mb-3 text-gray-950">The Annual Flagship</h3>
        <p class="text-sm leading-relaxed text-gray-600 mb-3">The tentpole moment of the year:</p>
        <ul class="list-disc pl-5 text-sm leading-relaxed text-gray-600 space-y-1 mb-4">
          <li>Conference × Hackathon × Showcase</li>
          <li>Hands-on workshops with industry experts</li>
          <li>Live product demos to the whole community</li>
          <li>Matchmaking between builders across disciplines</li>
          <li>Exclusive Shipyard merch and gear</li>
          <li>The ultimate celebration of Miami's maker culture</li>
        </ul>
      </div>

      <!-- Training Box -->
      <div class="bg-gray-100 p-4 rounded-lg flex items-center justify-between group cursor-pointer hover:bg-gray-200 transition-colors">
        <div>
          <p class="text-xs font-medium text-gray-950">Join our online community</p>
          <p class="text-xs font-medium text-gray-950">Connect with builders 24/7.</p>
          <p class="text-xs text-primary-600 mt-1 group-hover:underline font-semibold">Join Discord</p>
        </div>
        <div class="w-6 h-6 rounded-full bg-gray-300 flex items-center justify-center">
            <svg width="10" height="10" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-600"><line x1="7" y1="17" x2="17" y2="7"></line><polyline points="7 7 17 7 17 17"></polyline></svg>
        </div>
      </div>

      <hr class="border-gray-200" />

      <!-- Item 4 -->
      <div>
        <h3 class="text-xl font-medium mb-3 text-gray-950">A Cultural Brand</h3>
        <p class="text-sm leading-relaxed text-gray-600">
          Shipyard is a brand people wear, not just attend. Our community identity is built on shipping real products and supporting fellow builders. Join the movement that's defining the Miami tech ecosystem.
        </p>
      </div>

    </div>

    <!-- Right Content (Visual) -->
    <div class="lg:col-span-7 relative min-h-[600px] bg-gray-900 rounded-sm overflow-hidden">
      <img 
        src="/generated/image-a-high-energy-collaborative-building-env-1770862561615-0.webp" 
        alt="Shipyard Build Session" 
        class="absolute inset-0 w-full h-full object-cover opacity-80"
      />
      <div class="absolute inset-0 bg-gradient-to-t from-gray-950/60 to-transparent"></div>
      
      <!-- Controls -->
      <div class="absolute bottom-6 right-6 flex gap-2">
        <button class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center text-white hover:bg-white/20 transition-colors border border-white/20">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><rect x="6" y="4" width="4" height="16"></rect><rect x="14" y="4" width="4" height="16"></rect></svg>
        </button>
        <button class="w-10 h-10 rounded-full bg-white/10 backdrop-blur-md flex items-center justify-center text-white hover:bg-white/20 transition-colors border border-white/20">
          <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><polygon points="11 5 6 9 2 9 2 15 6 15 11 19 11 5"></polygon><path d="M19.07 4.93a10 10 0 0 1 0 14.14M15.54 8.46a5 5 0 0 1 0 7.07"></path></svg>
        </button>
      </div>
    </div>
  </div>
</section>
