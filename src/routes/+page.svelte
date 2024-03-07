<script>
	import BigliettoDaVisita from '$components/BigliettoDaVisita.svelte';

	let Biglietto = {
		nome: 'Sofia Grillo',
		indirizzo: 'Piazza della trivulziana 2',
		mail: 'sofiagrillo0@gmail.com',
		numero: '3313447376',
		image:
			'https://images.pexels.com/photos/18031818/pexels-photo-18031818/free-photo-of-mano-estate-fiore-tenendo.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2'
	};

	let Biglietti = [
		{
			nome: 'Sara',
			indirizzo: 'Ciao',
			mail: '10:20',
			numero: '1230',
			image:
				'https://images.pexels.com/photos/20264866/pexels-photo-20264866/free-photo-of-relax-letto-biondo-sorridente.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2'
		}
	];
</script>

<svelte:head>
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@3.4.1/src/css/preflight.css" />
</svelte:head>

<BigliettoDaVisita
	nome="Sofia Grillo"
	indirizzo="Piazza della trivulziana 2"
	mail="sofiagrillo0@gmail.com"
	numero="3313447376"
	image="https://images.pexels.com/photos/18031818/pexels-photo-18031818/free-photo-of-mano-estate-fiore-tenendo.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2"
></BigliettoDaVisita>
