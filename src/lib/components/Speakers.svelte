<script lang="ts">

  const featuredBuilders = [
    { name: 'Agnel Nieves', role: 'Co-founder', img: '/generated/image-portrait-of-agnel-nieves-a-tech-founder--1770862643311-0.webp' },
    { name: 'Joshua Parini', role: 'Co-founder', img: '/generated/image-portrait-of-joshua-parini-a-creative-tec-1770862646095-1.webp' },
    { name: 'Elena Rodriguez', role: 'Lead Designer', img: '/generated/image-portrait-of-elena-rodriguez-a-talented-l-1770862847114-0.webp' },
    { name: 'Marcus Chen', role: 'Full-stack Engineer', img: '/generated/image-portrait-of-marcus-chen-a-young-asian-am-1770862849989-1.webp' }
  ];

  const moreBuilders = [
    { name: 'Sofia Valdes', role: 'Founder', company: 'Magic City Labs' },
    { name: 'David Miller', role: 'Product Lead', company: 'Neon Stream' },
    { name: 'Isabella Gomez', role: 'Creative Director', company: 'Studio 305' },
    { name: 'Julian Santos', role: 'Growth Engineer', company: 'Shipyard Alumni' },
    { name: 'Aria Knight', role: 'Indie Hacker', company: 'Build Fast' },
    { name: 'Leo Rivera', role: 'Hardware Engineer', company: 'Miami Robotics' },
    { name: 'Maya Patel', role: 'UX Researcher', company: 'Design Miami' },
    { name: 'Kobe Bryant Jr.', role: 'Community Lead', company: 'Shipyard' }
  ];
</script>

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200 overflow-hidden" id="community">
  <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium mb-8 text-gray-950">Featured Builders</h2>
  
  <p class="text-sm font-medium text-gray-600 mb-6">The minds behind the builds</p>

  <!-- Carousel -->
  <div class="relative w-full overflow-x-auto pb-12 hide-scrollbar">
    <div class="flex gap-6 min-w-max">
      {#each featuredBuilders as builder}
        <div class="w-[280px] md:w-[320px] bg-white rounded-lg overflow-hidden shadow-sm group cursor-pointer relative flex flex-col h-[420px] border border-gray-100 transition-all hover:shadow-md">
            <!-- Top Section with Name and Image -->
            <div class="relative flex-grow bg-gray-50 overflow-hidden">
                <!-- Name -->
                <div class="absolute top-6 left-6 z-10">
                    <h3 class="text-3xl font-medium text-gray-950 leading-[0.9] tracking-tight">
                        {#each builder.name.split(' ') as word}
                            <div>{word}</div>
                        {/each}
                    </h3>
                </div>
                
                <!-- Image -->
                <img 
                    src={builder.img} 
                    alt={builder.name} 
                    class="absolute bottom-0 right-0 w-[85%] h-auto object-cover object-bottom grayscale group-hover:grayscale-0 transition-all duration-500 mix-blend-multiply" 
                />
            </div>

            <!-- Bottom Section with Role -->
            <div class="p-6 bg-white border-t border-gray-100 relative">
                <p class="text-xs font-bold text-gray-950 mb-1">Shipyard</p>
                <p class="text-xs text-gray-600">{builder.role}</p>
                
                <!-- Arrow Icon -->
                <div class="absolute bottom-6 right-6 opacity-0 group-hover:opacity-100 transition-opacity">
                    <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-950"><path d="M7 17L17 7"></path><path d="M7 7h10v10"></path></svg>
                </div>
            </div>
        </div>
      {/each}
    </div>
  </div>

  <!-- Navigation Buttons -->
  <div class="flex justify-between items-center mb-16">
    <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center text-gray-600 hover:bg-gray-200 transition-colors">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M19 12H5"></path><path d="M12 19l-7-7 7-7"></path></svg>
    </button>
    <button class="w-10 h-10 rounded-full bg-gray-100 flex items-center justify-center text-gray-600 hover:bg-gray-200 transition-colors">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M5 12h14"></path><path d="M12 5l7 7-7 7"></path></svg>
    </button>
  </div>

  <!-- More Builders List -->
  <div>
    <p class="text-sm font-medium text-gray-600 mb-6">Community Spotlight</p>
    <div class="border-t border-gray-200">
      {#each moreBuilders as builder}
        <div class="grid grid-cols-1 md:grid-cols-12 py-4 border-b border-gray-200 items-center hover:bg-gray-50 transition-colors cursor-pointer group">
          <div class="md:col-span-4">
            <h3 class="text-xl font-normal text-gray-950">{builder.name}</h3>
          </div>
          <div class="md:col-span-7">
            <p class="text-xs font-bold text-gray-950 mb-0.5">{builder.company}</p>
            <p class="text-xs text-gray-600">{builder.role}</p>
          </div>
          <div class="md:col-span-1 flex justify-end opacity-0 group-hover:opacity-100 transition-opacity">
            <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="text-gray-400"><path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z"></path><rect x="2" y="9" width="4" height="12"></rect><circle cx="4" cy="4" r="2"></circle></svg>
          </div>
        </div>
      {/each}
    </div>
    <p class="text-sm text-gray-500 mt-8">Join the community to get featured.</p>
  </div>

</section>

<style>
  .hide-scrollbar::-webkit-scrollbar {
    display: none;
  }
  .hide-scrollbar {
    -ms-overflow-style: none;
    scrollbar-width: none;
  }
</style>
