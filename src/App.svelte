<script>
	let num = 123;
	function double(){
		num *= 2;
	}
</script>

<main>
	<h1>Hello {num}!</h1>
	<button on:click={double}>double</button>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>