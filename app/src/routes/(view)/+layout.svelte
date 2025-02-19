<script lang="ts">
	import Footer from '../../components/others/Footer.svelte';
import Hero from '../../components/others/Hero.svelte';
    const hero = "/bg/img1.png"
	let { children } = $props();
</script>
<div style={`background-image: url(${hero})`} class="bg-center bg-cover p-5 py-20">
    <Hero />
</div>
{@render children()}
<Footer />