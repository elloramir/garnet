<button class="button">
	<div class="button-inner">Hello iam a button</div>
</button>

<style>
	.button {
		color: var(--text-primary);
		background-color: var(--secondary);
		border: 2px solid var(--outline);
		border-radius: 3px;
		cursor: pointer;
	}

	.button:hover {
		background-color: var(--primary);
	}

	.button-inner {
		border: 2px solid var(--innerline);
		padding: 5px 5px;
	}
</style>