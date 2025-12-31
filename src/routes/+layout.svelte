<script lang="ts">
	import './layout.css';

	const { children } = $props();
</script>

<div>
	{@render children()}
</div>
