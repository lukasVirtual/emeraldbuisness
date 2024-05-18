<script lang="ts">
	import Icon from '@iconify/svelte';
	import Typewriter from 'svelte-typewriter';
	import { page } from '$app/stores';
	import { base } from '$app/paths';
	export const prerender = true
</script>

<div
	class="flex flex-col justify-evenly
	min-h-screen bg-base-200"
>
	<div class="flex flex-row justify-center">
		<div class="text-center">
			<div class="max-w-md">
				<Typewriter>
					<h1 class="text-5xl font-bold">Tailored Software</h1>
				</Typewriter>
				<p class="text-2xl font-medium pb-5">for all your needs</p>
				<a href="{base}/services">
					<button class="btn bg-green-400">Get Started</button>
				</a>
			</div>
		</div>
	</div>
	<div class="md:flex max-sm:pt-10 justify-center justify-evenly">
		<div class="flex justify-center">
			<h1 class="absolute font-extrabold text-center text-2xl font-serif">UI/UX Design</h1>
			<Icon class="mt-11" height="8rem" icon="mdi:design" />
		</div>

		<div class="flex justify-center">
			<h1 class="absolute font-extrabold text-center text-2xl font-serif">Development</h1>
			<Icon class="mt-14" height="8rem" icon="mingcute:code-fill" />
		</div>

		<div class="flex justify-center">
			<h1 class="absolute font-extrabold text-center text-2xl font-serif">IT-Support</h1>
			<Icon class="mt-12" height="8rem" icon="healthicons:medical-advice" />
		</div>
	</div>
</div>
