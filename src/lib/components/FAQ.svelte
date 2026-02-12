<script lang="ts">

  const faqs = [
    "What is Shipyard?",
    "Do I need to be a developer to attend?",
    "How often are the build nights?",
    "Where in Miami are the events held?",
    "Is there a cost for monthly events?",
    "What should I bring to a build night?",
    "How do I demo my product at an event?",
    "What is the Shipyard Flagship?",
    "How can I sponsor Shipyard?",
    "Is there an online community I can join?"
  ];
</script>

<section class="py-20 px-6 max-w-[1400px] mx-auto border-t border-gray-200" id="faq">
  <div class="grid grid-cols-1 lg:grid-cols-12 gap-12">
    <div class="lg:col-span-4">
      <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium text-gray-950">FAQs</h2>
    </div>

    <div class="lg:col-span-8">
      <div class="border-t border-gray-200">
        {#each faqs as question}
          <div class="py-5 border-b border-gray-200 flex justify-between items-center cursor-pointer group hover:bg-gray-50 transition-colors px-2 -mx-2 rounded-sm">
            <h3 class="text-sm font-medium text-gray-950 pr-8">{question}</h3>
            <div class="text-gray-400 group-hover:text-gray-950 transition-colors">
              <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M12 5v14"></path><path d="M5 12h14"></path></svg>
            </div>
          </div>
        {/each}
      </div>
    </div>
  </div>
</section>
