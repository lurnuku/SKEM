<!-- Official documentation at https://svelte.dev/docs/kit/creating-a-project says this: "You create
pages by adding files to the src/routes directory of your project. These will be server-rendered so
that a user's first visit to your app is as fast as possible, then a client-side app takes over."
But I am not sure how to set it up properly yet, gonna have to figure it out */ -->

<script lang="ts">
	import Insert from '../components/Insert.svelte'
	import Logo from '../components/Logo.svelte'
</script>

<section class="flex flex-col items-center justify-center gap-20">
	<Logo />
	<Insert />
</section>
