<script context="module">
	export const prerender = true;
</script>

<script>
</script>

<svelte:head>
	<title>Equilibrium</title>
	<meta name="description" content="Try using Svelte" />
</svelte:head>

<div class="img-div">
	<img class="img-2" src="images/icon-view.svg" alt="" />
	<img class="img-1" src="images/image-equilibrium.jpg" alt="Equilibrium #3429 Collectible" />
</div>

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
		transition: 0.3s;
	}

	.img-div:hover .img-1 {
		z-index: 20;
		cursor: pointer;
		opacity: 70%;
	}

	.img-2:hover {
		cursor: pointer;
	}

	.img-div:hover .img-2 {
		opacity: 100%;
	}

	.img-2 {
		transition: 0.3s;
		opacity: 0%;
		z-index: 30;
		position: absolute;
		left: 50%;
		margin-left: -22px;
		top: 50%;
		margin-top: -22px;
	}

	.img-div {
		position: relative;
		background-color: var(--primary-cyan);
		border-radius: 1.1rem;
		width: 100%;
		height: 288px;
	}

	.main h1 {
		transition: 0.3s;
	}

	.main h1:hover {
		cursor: pointer;
		color: var(--primary-cyan);
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
		font-size: 18px;
		display: flex;
		align-items: center;
		gap: 0.5rem;
		font-weight: 400;
	}

	.under-main .left {
		color: var(--primary-cyan);
		font-weight: 600;
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
		transition: 0.3s;
	}

	.footer p span:hover {
		cursor: pointer;
		color: var(--primary-cyan);
	}

	.avatar {
		width: 2rem;
		height: 2rem;
		border-radius: 100%;
		border: solid 1px white;
	}
</style>
