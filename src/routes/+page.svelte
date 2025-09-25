<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CenteredTextOnlyHero from "$lib/components/layout/hero-sections/CenteredTextOnlyHero.svelte";
</script>

<CenteredTextOnlyHero
	title="Simulations that don't slow you down"
	subtitle="Plasmatic makes plasma process optimization faster, smarter, and production-ready—no more weeks of trial-and-error."
	imageSrc="/generated/image-a-minimal-interior-scene-with-a-soft-gra.webp"
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/intel.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/samsung.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/asml.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/globalfoundries.com/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="Plasmatic transforms complex plasma physics simulations into real-time insights for semiconductor manufacturers and hardware companies. Our GPU-accelerated computing platform replaces weeks of manual testing with instant process optimization, helping manufacturing engineers achieve production-ready results faster than ever. By combining deep plasma physics expertise with adaptive algorithms, we're making plasma process control accessible and actionable for the $74B semiconductor equipment market."
/>

<Testimonials
	testimonials={[
		{
			name: "Dr. Keiko Tanaka",
			position: "Manufacturing Engineer",
			company: "NanoTech Semiconductors",
			quote:
				"Plasmatic reduced our plasma process optimization time from 3 weeks to 2 days.\nOur defect rates dropped by 47% and we saved $2.3M in production downtime last quarter.",
			image: "/generated/image-a-professional-asian-woman-engineer-stan.webp"
		},
		{
			name: "Miguel Rodriguez",
			position: "Process Development Director",
			company: "Precision Manufacturing",
			quote:
				"The real-time insights eliminated 90% of our trial-and-error testing.\nWe achieved production scaling 6x faster while maintaining strict quality standards.",
			image: "/generated/image-a-confident-hispanic-man-in-business-att.webp"
		},
		{
			name: "Dr. Amara Williams",
			position: "Senior Process Engineer",
			company: "Advanced Fabrication",
			quote:
				"Our plasma chamber utilization improved by 65% with predictive optimization.\nThe adaptive algorithms saved us $1.8M in equipment costs by maximizing existing infrastructure.",
			image: "/generated/image-a-professional-black-woman-in-a-semicond.webp"
		}
	]}
/>

<Features
	title="Advanced plasma simulation technology"
	subtitle="Transform weeks of manual testing into minutes of intelligent optimization with our GPU-accelerated platform"
	features={[
		{
			title: "Real-time simulation engine",
			description: "Get instant feedback on plasma behavior changes instead of waiting days for traditional simulations to complete, enabling rapid iteration and optimization."
		},
		{
			title: "Adaptive mesh refinement",
			description: "Automatically focus computational power on critical plasma regions for 10x more accurate results without sacrificing simulation speed."
		},
		{
			title: "Process optimization algorithms",
			description: "AI-driven parameter recommendations reduce failed production runs by 85% while optimizing for your specific quality targets."
		},
		{
			title: "GPU-accelerated computing",
			description: "Harness parallel processing power to run complex plasma physics calculations that scale seamlessly from lab bench to 500+ fab installations."
		},
		{
			title: "Predictive quality control",
			description: "Identify potential process failures before they happen, preventing costly rework and maintaining consistent production standards."
		},
		{
			title: "Production-ready deployment",
			description: "Deploy directly into your existing manufacturing workflow with enterprise-grade reliability and real-time process control integration."
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
