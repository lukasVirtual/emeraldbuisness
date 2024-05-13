<script lang="ts">
	import { base } from '$app/paths';
	import Icon from '@iconify/svelte';
</script>

<div class=" flex items-center justify-center h-screen w-screen bg-base-200">
	<div class="w-1/2 text-center">
		<h1 class="text-3xl font-bold">Kontaktieren sie uns jetzt!</h1>
		<p class="mt-2 font-semibold">Und Sichern sie sich ein kostenloses Beratungsgespräch</p>
		<div class="card mt-24 mb-32 w-96 bg-base-100 shadow-xl mx-auto">
			<div class="card-body text-center">
				<img class=" object-cover h-32" src="{base}/images/logo_transparent.png" alt="" />
				<div class="divider" />
				<p class="font-semibold">Email:</p>
				<div class="flex flex-row items-end content-start">
					<p>gerlinskilukas@gmail.com</p>
					<!-- <button class="btn btn-xs">copy!</button> -->
				</div>
				<div class="divider" />
				<p class="font-semibold">Nummer:</p>
				<div class="flex flex-row items-end content-start">
					<p>+49 170 3760484</p>
					<!-- <button class="btn btn-xs">copy!</button> -->
				</div>
			</div>
		</div>
	</div>
	<div class="w-1/2 p-4">
		<img src="{base}/images/meeting.jpg" alt="Contact Us" class="w-3/4 h-auto mb-64" />
	</div>
</div>
