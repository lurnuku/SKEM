<!-- Official documentation at https://svelte.dev/docs/kit/creating-a-project says this: "You create
pages by adding files to the src/routes directory of your project. These will be server-rendered so
that a user's first visit to your app is as fast as possible, then a client-side app takes over."
But I am not sure how to set it up properly yet, gonna have to figure it out */ -->

<!-- Testing bits-ui -->
<script lang="ts">
	import { Button } from 'bits-ui'
</script>

<Button.Root
	class="rounded-input bg-dark text-background shadow-mini hover:bg-dark/95 inline-flex
	h-12 items-center justify-center px-[21px] text-[15px]
	font-semibold active:scale-[0.98] active:transition-all"
>
	Unlimited
</Button.Root>
