<div class="panel">
	<div class="panel-inner">
		<div class="panel-header">
			<span>Hello panel</span>
		</div>
		<div class="panel-content">
			<span>hello iam a panel content</span>
		</div>
	</div>
</div>

<style>
	.panel {
		width: 300px;
		height: 300px;
		background-color: var(--primary);
		border: 2px solid var(--outline);
		border-radius: 3px;
	}

	.panel-inner {
		border: 2px solid var(--innerline);
		height: 100%;
		display: flex;
		flex-direction: column;
	}

	.panel-header {
		background-color: var(--secondary);
		font-weight: bold;
		padding: 3px 5px;
		cursor: pointer;
	}

	.panel-content {
		border: 2px solid rgba(0, 0, 0, 0.3);
		padding: 3px 5px;
		flex: 1;
	}
</style>