<script lang="ts">
	export let href: string;
	export let isExternal = false;
</script>

<a {href} rel="noopener noreferrer" target={isExternal ? '_blank' : ''}>
	<slot />
</a>
