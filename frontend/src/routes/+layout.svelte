<script lang="ts">
	import './layout.css'
	import favicon from '$lib/assets/favicon.svg'

	let { children } = $props()
</script>

<!-- SVG for the noise filter; do not move or remove -->
<svg class="absolute h-0 w-0">
	<filter id="noiseFilter">
		<feTurbulence type="fractalNoise" baseFrequency="1.2" numOctaves="6" stitchTiles="stitch" />
	</filter>
</svg>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

{@render children()}
