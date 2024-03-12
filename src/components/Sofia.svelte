<script>
	export let Chisono;
	export let Progetti;
	export let Contatti;
	export let Ciao;
	export let WorkExperienceTitle;
	export let Lavorouno;
	export let Luogo;
	export let Anno;
	export let Lavorodue;
	export let Annodue;
	export let Luogodue;
	export let Lavorotre;
	export let Annotre;
	export let Luogotre;
	export let Lavoroquattro;
	export let Annoquattro;
	export let Luogoquattro;
	export let EducationTitle;
	export let Educationuno;
	export let Educationdue;
	export let Educationtre;
	export let Uniuno;
	export let Unidue;
	export let Unitre;
	export let Voto;

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
			<p class="Sofia_Title">{EducationTitle}</p>
			<p class="Sofia_Titoletto">{Educationuno}</p>
			<p class="Sofia_Luogo">{Uniuno}</p>
			<p class="Sofia_Info">{Voto}</p>
			<p class="Sofia_Titoletto">{Educationdue}</p>
			<p class="Sofia_Luogo">{Unidue}</p>
			<p class="Sofia_Titoletto">{Educationtre}</p>
			<p class="Sofia_Luogo">{Unitre}</p>
			<p class="Sofia_Title">{WorkExperienceTitle}</p>
			<p class="Sofia_Titoletto">{Lavorouno}</p>
			<p class="Sofia_Luogo">{Luogo}</p>
			<p class="Sofia_Info">{Anno}</p>
			<p class="Sofia_Titoletto">{Lavorodue}</p>
			<p class="Sofia_Luogo">{Luogodue}</p>
			<p class="Sofia_Info">{Annodue}</p>
			<p class="Sofia_Titoletto">{Lavorotre}</p>
			<p class="Sofia_Luogo">{Luogotre}</p>
			<p class="Sofia_Info">{Annotre}</p>
			<p class="Sofia_Titoletto">{Lavoroquattro}</p>
			<p class="Sofia_Luogo">{Luogoquattro}</p>
			<p class="Sofia_Info">{Annoquattro}</p>
		</div>
	</div>
</div>

<style>
	.Sofia {
		background-color: rgb(253, 247, 235);
		border-radius: 20px;
		padding-top: 20px;
		padding-bottom: 20px;
		font-family: sans-serif;
	}

	.Sofia_Topbar {
		font-size: 25 px;
		display: flex;
		font-weight: bold;
		flex-direction: row;
		justify-content: space-between;
		padding-left: 30px;
		padding-right: 30px;
	}

	.Sofia_Image {
		border-radius: 1000px;
		max-height: 600px;
	}

	.Sofia_Centro {
		display: grid;
		grid-template-columns: 1fr 1fr;
		padding-left: 40px;
		padding-right: 40px;
	}

	.Sofia_Title {
		font-weight: bolder;
		font-size: larger;
		line-height: 20px;
		color: darkslateblue;
		padding-top: 30px;
	}

	.Sofia_Titoletto {
		font-weight: bold;
		line-height: 40px;
		padding-top: 20px;
	}

	.Sofia_Luogo {
		line-height: 20px;
		font-weight: normal;
	}

	.Sofia_Info {
		line-height: 20px;
		font-style: italic;
	}
</style>
