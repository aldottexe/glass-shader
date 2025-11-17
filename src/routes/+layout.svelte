<script lang="ts">
	import '../app.css';

	let { children } = $props();
</script>

{@render children()}

<style lang="postcss">
	@reference "tailwindcss";
	:global(body) {
		@apply text-slate-200;
		background-image: url(https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2Fb%2Fbc%2FBiogradska_suma.jpg&f=1&nofb=1&ipt=9c5182c15145ea55944a21375e60771bee386da7f6e300456f4c07c1f35520ad);
	}
</style>
