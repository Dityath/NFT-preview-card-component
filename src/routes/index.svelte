<script context="module">
	export const prerender = true;
</script>

<script>
</script>

<svelte:head>
	<title>Equilibrium</title>
	<meta name="description" content="Try using Svelte" />
</svelte:head>

<img class="img-1" src="images/image-equilibrium.jpg" alt="Equilibrium #3429 Collectible" />

<section class="main">
	<h1>Equilibrium #3429</h1>
	<p>Our Equilibrium collection promotes balance and calm.</p>

	<div class="under-main">
		<h2 class="left">
			<img src="images/icon-ethereum.svg" alt="ether icon" />
			0.041ETH
		</h2>
		<h2 class="right">
			<img src="images/icon-clock.svg" alt="clock icon" />
			3 days left
		</h2>
	</div>
	<hr class="divider" />
	<div class="footer">
		<img class="avatar" src="images/image-avatar.png" alt="avatar" />
		<p>Creation of <span>Jules Wyvern</span></p>
	</div>
</section>

<style>
	.img-1 {
		width: 100%;
		border-radius: 1rem;
	}

	.main p {
		font-weight: 300;
		font-size: 18px;
		color: var(--primary-blue);
	}

	.under-main {
		margin-top: 1rem;
		display: flex;
		justify-content: space-between;
	}

	.under-main h2 {
		font-weight: 400;
		font-size: 18px;
		display: flex;
		align-items: center;
		gap: 0.5rem;
	}

	.under-main .left {
		color: var(--primary-cyan);
	}

	.under-main .right {
		color: var(--primary-blue);
	}

	.divider {
		border: solid 1px var(--neutral-line);
	}

	.footer {
		display: flex;
		gap: 1rem;
		align-items: center;
	}

	.footer p {
		font-weight: 400;
	}

	.footer p span {
		color: white;
	}

	.avatar {
		width: 2rem;
		height: 2rem;
		border-radius: 100%;
		border: solid 1px white;
	}
</style>
