<div class="window">
	<div class="window-inner">
		<div class="window-header">
			<span>Hello window</span>
		</div>
		<div class="window-content">
			<span>hello iam a window content</span>
		</div>
	</div>
</div>

<style>
	.window {
		width: 300px;
		height: 300px;
		background-color: var(--primary);
		border: 2px solid var(--outline);
		border-radius: 3px;
	}

	.window-inner {
		border: 2px solid var(--innerline);
		height: 100%;
		display: flex;
		flex-direction: column;
	}

	.window-header {
		background-color: var(--secondary);
		font-weight: bold;
		padding: 3px 5px;
		cursor: pointer;
	}

	.window-content {
		border: 2px solid rgba(0, 0, 0, 0.3);
		padding: 3px 5px;
		flex: 1;
	}
</style>