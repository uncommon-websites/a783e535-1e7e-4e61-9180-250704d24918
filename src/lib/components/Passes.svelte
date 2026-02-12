<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200">
  <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium mb-16 text-gray-950">Join the Crew</h2>

  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <!-- Cards -->
    <div class="lg:col-span-8 grid grid-cols-1 md:grid-cols-2 gap-6">
      
      <!-- Card 1 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col h-full relative overflow-hidden group hover:shadow-md transition-shadow">
        <div class="flex justify-between items-start mb-6">
          <h3 class="text-sm font-medium text-gray-900">Monthly Build Night</h3>
          <span class="bg-primary-100 text-primary-700 text-[10px] uppercase tracking-wider font-semibold px-2 py-1 rounded">Community</span>
        </div>
        
        <div class="flex items-baseline gap-2 mb-8">
          <span class="text-4xl font-medium text-gray-950">Free</span>
        </div>

        <p class="text-sm text-gray-600 mb-8 flex-grow">
          Access to our monthly IRL build sessions in Miami. Includes pizza, drinks, and the chance to demo your work.
        </p>

        <div class="mt-auto">
          <p class="text-xs text-gray-500 mb-4">RSVP required for each event. Limited capacity.</p>
          <button class="w-full bg-gray-950 text-white py-3 rounded-full text-sm font-medium hover:bg-primary-600 transition-colors">RSVP for Next Event</button>
        </div>
      </div>

      <!-- Card 2 -->
      <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col h-full relative overflow-hidden group hover:shadow-md transition-shadow">
        <div class="flex justify-between items-start mb-6">
          <h3 class="text-sm font-medium text-gray-900">Annual Flagship Pass</h3>
          <span class="bg-gray-100 text-gray-600 text-[10px] uppercase tracking-wider font-semibold px-2 py-1 rounded">Early bird</span>
        </div>
        
        <div class="flex items-baseline gap-2 mb-8">
          <span class="text-4xl font-medium text-gray-950">$299</span>
          <span class="text-gray-400 line-through text-sm">$499</span>
        </div>

        <p class="text-sm text-gray-600 mb-8 flex-grow">
          The ultimate builder experience. 2 days of workshops, hackathons, and the grand showcase. Includes exclusive merch.
        </p>

        <div class="mt-auto">
          <p class="text-xs text-gray-500 mb-4">Early bird rates end soon. Secure your spot in the flagship.</p>
          <button class="w-full bg-gray-950 text-white py-3 rounded-full text-sm font-medium hover:bg-primary-600 transition-colors">Get Flagship Pass</button>
        </div>
      </div>

    </div>

    <!-- Included List -->
    <div class="lg:col-span-4 pl-0 lg:pl-12 pt-4">
      <h3 class="text-sm font-medium text-gray-950 mb-6">What's included in the Flagship</h3>
      <ul class="space-y-4">
        {#each ['Keynote Sessions', 'Hands-on Workshops', 'Build Challenge Entry', 'Catered Meals', 'Networking Mixer', 'Exclusive Merch', 'Alumni Network Access'] as item}
          <li class="text-sm text-gray-600 flex items-center gap-3">
             <svg width="14" height="14" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="3" stroke-linecap="round" stroke-linejoin="round" class="text-primary-500"><polyline points="20 6 9 17 4 12"></polyline></svg>
             {item}
          </li>
        {/each}
      </ul>
    </div>
  </div>
</section>
