<script lang="ts">
	import '../app.css';
	import '@fontsource/krona-one';
	import '@fontsource-variable/inter';
	let { children } = $props();
</script>
<div class="bg-black text-white font-main overflow-hidden">
	{@render children()}
</div>
