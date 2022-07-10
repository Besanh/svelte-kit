<script>
	let title = 'Gaming';
	const updateTitle = () => {
		title = 'Hello Anh Gaming';
	};
</script>

<div class="index">
	<h2>{title}</h2>
	<p>
		Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ex, reiciendis! Fugiat maxime iusto
		reprehenderit omnis at facere nemo, laborum minima magni doloremque. Tempora qui praesentium
		reiciendis dolorum sunt provident maxime?
	</p>
	<button on:click={updateTitle}>Change</button>
	<input type="text" bind:value={title} />
	<a href="/guides">View guides</a>
	<a href="/about">About</a>
</div>

<style>
	.index {
		text-align: center;
		display: block;
	}
</style>
