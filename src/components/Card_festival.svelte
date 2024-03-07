<script>
	export let Titolo;
	export let Descrizione;
	export let Bottone;
	export let link;
</script>

<div class="card_festival">
	<p class="titolo">{Titolo}</p>
	<p class="descrizione">{Descrizione}</p>
	<a class="card_bottone" href={link} target="_blank">
		<p class="bottone">{Bottone}</p>
	</a>
</div>

<style>
	.card_festival {
		background-color: #000;
		width: 300px;
		border-radius: 20px;
		padding: 10px;
		color: #14ff00;
		font-family: sans-serif;
		margin-bottom: 10px;
		margin-top: 10px;

		display: flex;
		flex-direction: column;
		justify-content: center;
		align-items: center;
	}

	.titolo {
		text-align: center;
		font-size: 32px;
	}

	.descrizione {
		text-align: center;
		font-size: 9px;
		padding-bottom: 10px;
	}

	.card_bottone {
		text-align: center;
		background-color: #14ff00;
		padding: 10px;
		border-radius: 20px;
		width: 200px;
	}

	.bottone {
		text-align: center;
		color: white;
		font-size: 12px;
	}
</style>
