<script>
	import Fill from "../Buttons/Fill.svelte";


	import Title from "../Texts/Title.svelte";
    const commicI = "/bg/commicI.png"
</script>
<section>
    <div style={`background-image: url(${commicI})`}  class="text-center flex flex-col gap-5 items-center bg-cover bg-center py-20 px-10">
        <Title text = "Step Into the Realm of Adventure: Explore Our Featured Comics" />
        <Fill text = "Read More!" />
    </div>
</section>