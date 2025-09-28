<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Precision",
			description: "Physics-driven accuracy in every simulation, because manufacturing tolerances demand nothing less than exact results."
		},
		{
			title: "Speed",
			description: "Real-time insights that keep pace with production demands, eliminating weeks of manual testing cycles."
		},
		{
			title: "Reliability",
			description: "Proven algorithms and GPU acceleration that manufacturing engineers can depend on for critical process control."
		}
	];
</script>

<SecondaryHero
	title="Plasma precision, in real time"
	subtitle="Physics-driven control for faster scaling"
	imageSrc="/generated/image-a-group-of-professionals-working-togethe.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We started in 2018 with a simple goal: make helpful tech that people actually need. While many chase profits, we chose to do things differently.",
		"Beyond making good products, we care about doing the right thing, being kind to our planet, and making sure everyone can use what we build. That's our compass.",
		"From day one, we've asked ourselves: 'Does this actually help people?' This question gets us through tough calls and shapes who we are. We're playing the long game here.",
		"We think about how our work affects real people's lives. We build tech that brings people together, keeps your information safe, and treats everyone fairly. When we stick to these basics, good things happen."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- Team and investor sections removed - no actual team/investor information available for Plasmatic -->

<!-- CTA Section -->
<CallToAction
	title="Ready to optimize your plasma processes?"
	subtitle="See real-time simulation in action"
	description="Join semiconductor manufacturers already using Plasmatic to eliminate guesswork, reduce testing cycles, and achieve consistent quality at production scale."
	imageSrc="/generated/image-a-professional-manufacturing-engineer-st.webp"
/>
