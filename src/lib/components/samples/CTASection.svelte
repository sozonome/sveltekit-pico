<script lang="ts">
	import Link from '$lib/components/Link.svelte';
</script>

<section>
	<code>{'npx degit sozonome/sveltekit-pico <YOUR_APP_NAME>'}</code>

	<Link href="https://github.com/sozonome/sveltekit-pico/generate" isExternal>
		<button>Use This Template</button>
	</Link>
</section>

<style>
	code {
		margin: 0 auto;
	}
</style>
