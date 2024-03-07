<script>
	export let Titolo;
	export let Descrizione;
	export let Bottone;
</script>

<div class="card_festival">
	<p class="titolo">{Titolo}</p>
	<p class="descrizione">{Descrizione}</p>
	<div class="card_bottone">
		<p class="bottone">{Bottone}</p>
	</div>
</div>

<style>
	.card_festival {
		background-color: #000;
		width: fit-content;
		border-radius: 20px;
		padding: 10px;
		color: #14ff00;
		font-family: sans-serif;
	}

	.titolo {
		text-align: center;
		font-size: 32px;
	}

	.descrizione {
		text-align: center;
		font-size: 9px;
	}

	.card_bottone {
		background-color: #14ff00;
		padding: 10px;
		border-radius: 20px;
	}

	.bottone {
		text-align: center;
		color: white;
		font-size: 12px;
	}
</style>
