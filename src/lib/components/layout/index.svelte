<script lang="ts">
	import DefaultMetaTags from './DefaultMetaTags.svelte';
	import Footer from './Footer.svelte';
	import Header from './Header.svelte';
</script>

<DefaultMetaTags />
<Header />
<main class="container">
	<slot />
</main>
<Footer />
