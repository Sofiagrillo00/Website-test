<script>
	export let nome;
	export let indirizzo;
	export let mail;
	export let numero;

	export let image;
</script>

<div class="Biglietto">
	<img class="Biglietto_immagine" src={image} alt="copertina" />

	<div class="BigliettoDaVisita_Top">
		<p class="BigliettoDaVisita">{nome}</p>
	</div>
	<div class="BigliettoDaVisita_Centro">
		<p class="BigliettoDaVisita">{indirizzo}</p>
		<p class="BigliettoDaVisita">{mail}</p>
		<p class="BigliettoDaVisita">{numero}</p>
	</div>
</div>

<style>
	.Biglietto {
		background-color: rgb(253, 247, 235);
		width: 600px;
		border-radius: 20px;
		padding: 20px;
		font-family: sans-serif;
	}

	.BigliettoDaVisita {
		font-size: 25px;
		font-family: serif;
	}

	.BigliettoDaVisita_Top {
		margin-top: 30px;
		margin-bottom: 40px;
	}

	.BigliettoDaVisita_Centro {
		margin-top: 15px;
		margin-bottom: 15px;
	}

	.Biglietto_immagine {
	}
</style>
