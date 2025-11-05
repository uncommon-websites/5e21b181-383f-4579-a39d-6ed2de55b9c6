<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import CustomerCardHero from "$lib/components/layout/hero-sections/CustomerCardHero.svelte";

	// Icons
	import IconVideo from "~icons/lucide/video";
	import IconTrendingUp from "~icons/lucide/trending-up";
	import IconPlug from "~icons/lucide/plug";
	import IconZap from "~icons/lucide/zap";
	import IconNetwork from "~icons/lucide/network";
	import IconShieldCheck from "~icons/lucide/shield-check";
</script>

<CustomerCardHero
	centered={true}
	title="Trusted by leading hospital administrators optimizing OR performance"
	subtitle="Automated surgical documentation and real-time OR coordination that reduces turnaround time by 45% and captures the $240B operating room market."
	customers={[
		{
			name: "Dr. Michael Harrison",
			position: "Hospital Administrator",
			imageSrc: "/generated/image-professional-male-hospital-administrator.webp"
		},
		{
			name: "Dr. Sarah Chen",
			position: "OR Director",
			imageSrc: "/generated/image-confident-female-operating-room-director.webp"
		},
		{
			name: "James Rodriguez",
			position: "Healthcare CFO",
			imageSrc: "/generated/image-experienced-male-healthcare-cfo-in-a-hos.webp"
		},
		{
			name: "Dr. Emily Watson",
			position: "Surgery Coordinator",
			imageSrc: "/generated/image-professional-female-surgery-coordinator-.webp"
		},
		{
			name: "Robert Thompson",
			position: "Operations Manager",
			imageSrc: "/generated/image-senior-male-operations-manager-walking-t.webp"
		}
	]}
/>
<LogoScroller
	label="Trusted by leading healthcare systems"
	logoUrls={[
		'https://cdn.brandfetch.io/mayoclinic.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/clevelandclinic.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/massgeneral.org/w/400/h/400/logo',
		'https://cdn.brandfetch.io/hopkinsmedicine.org/w/400/h/400/logo'
	]}
/>

<Summary
	title="What we do"
	text="We combine real-time computer vision with AI agents to automate surgical documentation and coordinate operating room workflows. Hospital administrators use our platform to eliminate billing errors, optimize OR utilization, and reduce case turnaround time by 45%. Our Epic and Cerner pre-built connectors integrate seamlessly into existing hospital systems, turning low-performing operating rooms into revenue-generating assets."
/>

<Testimonials
	testimonials={[
		{
			name: "David Ramirez",
			position: "Chief Financial Officer",
			company: "Mercy Health System",
			quote:
				"We recovered $2.3 million in previously missed billing within the first quarter. The automated documentation reduced our turnaround time by 48%, and our OR utilization jumped from 67% to 89%. The ROI was immediate and measurable.",
			image: "/generated/image-a-professional-male-hospital-cfo-in-tail.webp"
		},
		{
			name: "Dr. Patricia Okonkwo",
			position: "OR Director",
			company: "St. Michael's Medical Center",
			quote:
				"Our surgical coordinators used to spend hours manually documenting procedures. Now it happens in real-time with complete accuracy. We've eliminated documentation errors entirely and cut post-op reporting time from 3 hours to 15 minutes per case.",
			image: "/generated/image-a-professional-female-or-director-in-scr.webp"
		},
		{
			name: "Marcus Chen",
			position: "Hospital Administrator",
			company: "Valley Regional Hospital",
			quote:
				"The Epic integration was seamless, taking just two weeks instead of the six months we anticipated. Our staff adopted the system within days, and we're now scheduling 12 additional procedures per week without adding resources. Risk management is finally confident in our documentation.",
			image: "/generated/image-a-professional-male-hospital-administrat.webp"
		}
	]}
/>

<Features
	title="Intelligent automation for operating rooms"
	subtitle="Comprehensive technology that transforms surgical documentation and OR coordination from post-operative burden into real-time intelligence"
	features={[
		{
			title: "Real-time computer vision documentation",
			description:
				"AI agents capture surgical procedures as they happen, eliminating post-op documentation burden. Automatically generate accurate operative reports while surgeons focus on patient care.",
			icon: IconVideo
		},
		{
			title: "Revenue optimization that pays for itself",
			description:
				"Reduce billing errors and capture missed charges with automated documentation that ensures complete, compliant coding. Turn every OR minute into properly documented revenue.",
			icon: IconTrendingUp
		},
		{
			title: "Seamless Epic and Cerner integration",
			description:
				"Pre-built connectors eliminate integration fears with direct data flow into existing EMR systems. Deploy in weeks, not months, without disrupting clinical workflows.",
			icon: IconPlug
		},
		{
			title: "45% faster documentation turnaround",
			description:
				"Dramatically reduce the time from surgery completion to finalized documentation. Accelerate billing cycles and improve operational efficiency across your entire OR department.",
			icon: IconZap
		},
		{
			title: "Coordinated OR scheduling intelligence",
			description:
				"AI-powered coordination optimizes room utilization and reduces turnover delays. Maximize your most valuable asset with predictive scheduling that adapts to real-time changes.",
			icon: IconNetwork
		},
		{
			title: "Compliance and safety built-in",
			description:
				"Automated verification ensures regulatory compliance and surgical safety protocols are documented consistently. Reduce risk while meeting Joint Commission and CMS requirements.",
			icon: IconShieldCheck
		}
	]}
/>
<AboutTeaser />
<CallToAction
	title="Transform your OR from cost center to revenue engine"
	subtitle="Deploy in weeks with Epic and Cerner pre-built connectors"
	description="Every day without automated documentation costs your hospital thousands in missed charges and inefficient turnaround times. See how our platform integrates seamlessly with your existing EMR system and starts capturing revenue within weeks, not months. Join leading healthcare systems already optimizing their operating rooms."
	imageSrc="/generated/image-a-confident-hospital-administrator-in-a-.webp"
	callsToAction={[
		{
			href: "/contact",
			label: "Schedule a demo",
			variant: "primary"
		},
		{
			href: "/about",
			label: "Meet our team",
			variant: "secondary"
		}
	]}
/>
