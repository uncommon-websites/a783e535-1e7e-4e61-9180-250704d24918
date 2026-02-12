<script lang="ts">
  import Header from "$lib/components/Header.svelte";
  import Hero from "$lib/components/Hero.svelte";
  import WhyAttend from "$lib/components/WhyAttend.svelte";
  import Passes from "$lib/components/Passes.svelte";
  import Speakers from "$lib/components/Speakers.svelte";
  import Agenda from "$lib/components/Agenda.svelte";
  import Sponsors from "$lib/components/Sponsors.svelte";
  import FAQ from "$lib/components/FAQ.svelte";
  import Footer from "$lib/components/Footer.svelte";
</script>

<main class="bg-gray-50 min-h-screen font-sans text-gray-950 selection:bg-primary-500 selection:text-white">
  <Header />
  <Hero />
  <WhyAttend />
  <Passes />
  <Speakers />
  <Agenda />
  <Sponsors />
  <FAQ />
  <Footer />
</main>

