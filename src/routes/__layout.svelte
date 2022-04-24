<script>
	import '../style/app.css';
</script>

<svelte:head>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossOrigin="true" />
	<link
		href="https://fonts.googleapis.com/css2?family=Outfit:wght@300;400;600&display=swap"
		rel="stylesheet"
	/>
</svelte:head>

<main>
	<div class="main">
		<div class="container">
			<slot />
		</div>
	</div>
</main>

<style>
	.main {
		font-family: var(--main-font);
		width: 100%;
		height: 97vh;
		display: flex;
		justify-content: center;
		align-items: center;
	}

	.container {
		color: white;
		background-color: var(--neutral-card);
		width: 18rem;
		height: 34rem;
		padding: 1.25rem;
		border-radius: 1rem;
		filter: drop-shadow(0 20px 13px rgb(0 0 0 / 0.03)) drop-shadow(0 8px 5px rgb(0 0 0 / 0.08));
	}
</style>
