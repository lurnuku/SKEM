<script lang="ts">
	let x = $state<any>('')
</script>

<form>
	<div
		class="flex w-215 gap-4 rounded-2xl border-none bg-primary p-4 text-base text-dark
			shadow-[0_0.3rem_var(--color-secondary)]"
	>
		<div
			class="-my-4 -ml-4 flex w-[12%] cursor-default items-center rounded-l-2xl bg-light px-6
				shadow-[0_0.3rem_var(--color-light-shadow)]"
		>
			https://
		</div>
		<input type="text" placeholder="Insert the full URL" class="shadow-none outline-none" />
	</div>
</form>
