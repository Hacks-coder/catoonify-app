<script>
	import Fill from "../Buttons/Fill.svelte";
    let { characterBg, comicTitle, description } = $props();
</script>
<section class="@container flex justify-center">
    <div style={`background-image: url(${characterBg})`} class="bg-center bg-cover rounded-2xl flex w-60 h-90 border-2 border-black">
        <div class="h-32 w-54 text-center mt-40">
            <p class="text-red font-bold font-main">{comicTitle}</p>
            <p class="text-gold font-title">{description}</p>
            <Fill text = "Read More!" />
        </div>
    </div>
</section>