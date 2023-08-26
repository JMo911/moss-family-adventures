<script lang="ts">
	import { goto } from '$app/navigation';

	const handleClick = () => {
		goto('/');
	};
</script>

<h1>hello about</h1>
<button on:click={handleClick}>click to go home</button>
