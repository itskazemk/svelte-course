<script>
	let { children, ...other } = $props();
</script>

<button {...other}>{@render children()}</button>

<style>
	button {
		color: white;
		background-color: black;
		padding: 20px 24px;
		font-weight: normal;
		font-size: 22px;
		border: 2px solid white;
		text-transform: uppercase;
		transition: all 0.3s;

		&:hover {
			background-color: white;
			color: black;
		}
	}
</style>
