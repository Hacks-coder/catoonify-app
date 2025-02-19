<script>
	import CharactersCard from "../Cards/CharactersCard.svelte";

    const characters = [
        {characterBg: '/bg/about.png', name: "Doom's Kid", comic: "The Ledgen of Kain", characteristics: "Big arms"},
    ]
</script>

<div>
    {#each characters as {characterBg, name, comic, characteristics}}
        <CharactersCard {characterBg} {name} {comic} {characteristics} />
    {/each}
</div>