<script>
	import CharactersCard from "../Cards/CharactersCard.svelte";

    const characters = [
        {characterBg: '/bg/about.png', comicTitle: "Doom's Kid", description: "where machines clash in a fight for survival and supremacy"},
    ]
</script>

<div>
    {#each characters as {characterBg, comicTitle, description}}
        <CharactersCard {characterBg} {comicTitle} {description} />
    {/each}
</div>