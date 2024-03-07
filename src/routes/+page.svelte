<script lang="ts">
	import Card_festival from '$components/Card_festival.svelte';

	let Cards = [
		{
			Titolo: 'TICKET',
			Descrizione: 'Choose the best ticket based on your needs',
			Bottone: 'Get them',
			link: 'https://www.youtube.com/watch?v=BbeeuzU5Qc8'
		},
		{
			Titolo: 'HOTEL',
			Descrizione: 'Choose the best hotel',
			Bottone: 'Book now',
			link: 'https://www.youtube.com/watch?v=BbeeuzU5Qc8'
		},

		{
			Titolo: 'TRANSPORT',
			Descrizione: 'Discover all the possibilities to reach us',
			Bottone: 'Come now',
			link: 'https://www.youtube.com/watch?v=BbeeuzU5Qc8'
		},
		{
			Titolo: 'ACTIVITIES',
			Descrizione: 'Make your experience even more enjoyable',
			Bottone: 'Enjoy',
			Link: 'https://www.youtube.com/watch?v=BbeeuzU5Qc8'
		}
	];
</script>

<svelte:head>
	<link rel="stylesheet" href="https://unpkg.com/tailwindcss@3.4.1/src/css/preflight.css" />
</svelte:head>

{#each Cards as Card}
	<Card_festival Titolo={Card.Titolo} Descrizione={Card.Descrizione} Bottone={Card.Bottone} />
{/each}
