<script>
	import Small from "../Texts/Small.svelte";

    let { characterBg, name, comic, characteristics } = $props();
</script>
<section class="@container flex justify-center">
    <div style={`background-image: url(${characterBg})`} class="bg-center bg-cover rounded-2xl flex w-60 h-90 border-2 border-black">
        <div class="h-32 w-54 text-center mt-40">
            <p class="text-red font-bold font-main">{name}</p>
            <p class="text-gold font-title">{comic}</p>
            <Small text = {characteristics} />
        </div>
    </div>
</section>