<script>
	import Fill from "../Buttons/Fill.svelte";
	import Small from "../Texts/Small.svelte";


	import Title from "../Texts/Title.svelte";
    const about = "/bg/about.png"

</script>
<section class="@container">
    <div style={`background-image: url(${about})`} class="flex flex-col bg-cover bg-center items-center text-center gap-5 px-10 py-20">
        <Title text = "ABOUT US" />
        <Small text = "Welcome to our world of mythical creatures and epic tales! Our website is dedicated to bringing you captivating stories, breathtaking artwork, and unforgettable adventures. Whether you're a fan of fantasy, magic, or thrilling journeys, we aim to spark your imagination and transport you to realms beyond your wildest dreams" />
        <Fill text = "Read More!" />
    </div>
</section>