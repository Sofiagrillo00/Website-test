<script>
	export let Chisono;
	export let Progetti;
	export let Contatti;
	export let Ciao;

	export let image;
</script>

<div class="Sofia">
	<div class="Sofia_Topbar">
		<p class="Sofia">{Progetti}</p>
		<p class="Sofia">{Chisono}</p>
		<p class="Sofia">{Contatti}</p>
	</div>

	<img class="Sofia_Image" src={image} alt="copertina" />

	<div class="Sofia_Centro">
		<p class="Sofia">{Ciao}</p>
	</div>
</div>

<style>
	.Sofia {
		background-color: rgb(253, 247, 235);
		border-radius: 20px;
		padding: 20px;
		font-family: sans-serif;
	}

	.Sofia_Topbar {
		font-size: 25 px;
		display: flex;
		flex-direction: row;
		justify-content: space-between;
	}
</style>
