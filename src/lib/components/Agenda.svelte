<script lang="ts">
  import AgendaItem from './AgendaItem.svelte';

  const monthlies = {
    date: "Every Month",
    tags: ["Recurring"],
    items: [
      { time: "6:00 PM", title: "Build Night Kickoff", subtitle: "Pizza, drinks, and networking at The Factory." },
      { time: "7:00 PM", title: "Hands-on Build Session", subtitle: "Deep dive into a specific stack (e.g., Next.js + Supabase)." },
      { time: "9:00 PM", title: "Live Demos", subtitle: "Builders show off what they made in 2 hours." }
    ]
  };

  const flagshipDay1 = {
    date: "Nov 14",
    tags: ["Flagship Day 1"],
    items: [
      { time: "Morning", content: ["Check-in & Coffee", "Opening Keynote: The Future of Shipping", "Breakout Workshops: Design Systems, API Architecture"] },
      { time: "Afternoon", content: ["Lunch & Networking", "Build Challenge Begins", "Expert Mentorship Sessions"] },
      { time: "Evening", title: "Shipyard Mixer" }
    ]
  };

  const flagshipDay2 = {
    date: "Nov 15",
    tags: ["Flagship Day 2"],
    items: [
      { time: "Morning", content: ["Breakfast", "Final Build Push", "Pitch Prep Workshops"] },
      { time: "Afternoon", content: ["The Grand Showcase: Live Demos on Main Stage", "Community Voting & Awards"] },
      { time: "Evening", title: "Afterparty & Closing Ceremony" }
    ]
  };
</script>

<section class="px-6 max-w-[1400px] mx-auto py-20 border-t border-gray-200">
  <h2 class="text-[clamp(2.5rem,5vw,4rem)] leading-none font-medium mb-16 text-gray-950">The Cadence</h2>
  <AgendaItem {...monthlies} />
  <AgendaItem {...flagshipDay1} />
  <AgendaItem {...flagshipDay2} />
</section>
