<script lang="ts">
	import Header from '$lib/components/Header.svelte';
	import '../app.css';
	import About from '../lib/components/About.svelte';
	import BottomCta from '../lib/components/BottomCTA.svelte';
	import CallToAction from '../lib/components/CallToAction.svelte';
	import Features from '../lib/components/Features.svelte';
	import Footer from '../lib/components/Footer.svelte';
	import Hero from '../lib/components/Hero.svelte';
	import Team from '../lib/components/Team.svelte';

	let open = false;
</script>

<Header bind:open />
<Hero />
<About />
<Features />
<CallToAction />
<Team />
<BottomCta />
<Footer />
<main>
	<slot />
</main>
