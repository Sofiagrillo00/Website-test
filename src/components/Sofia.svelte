<script>
	export let Chisono;
	export let Progetti;
	export let Contatti;
	export let Ciao;
	export let WorkExperienceTitle;

	export let image;
</script>

<div class="Sofia">
	<div class="Sofia_Topbar">
		<p class="Sofia">{Progetti}</p>
		<p class="Sofia">{Chisono}</p>
		<p class="Sofia">{Contatti}</p>
	</div>

	<div class="Sofia_Centro">
		<img class="Sofia_Image" src={image} alt="copertina" />
		<div>
			<p class="Sofia">{Ciao}</p>
			<p class="Sofia_Title">{WorkExperienceTitle}</p>
			<p class="Sofia">{Ciao}</p>
		</div>
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
		font-weight: bold;
		flex-direction: row;
		justify-content: space-between;
	}

	.Sofia_Image {
		border-radius: 1000px;
		max-height: 600px;
	}

	.Sofia_Centro {
		display: grid;
		grid-template-columns: 1fr 1fr;
	}

	.Sofia_Title {
		font-weight: bold;
	}
</style>
