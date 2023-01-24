<script>
	import { imgs } from './../stores.js';
</script>

{#each imgs as img}
	<img src={img.img} alt="" />
{/each}
