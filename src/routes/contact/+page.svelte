<script lang="ts">
	import Icon from '@iconify/svelte';
</script>

<div class="min-h-screen bg-base-200">
	<div class="flex flex-col items-center text-center">
		<div class="mt-56 max-w-md">
			<h1 class="text-5xl font-bold">Contact Us!</h1>
			<p class="py-6">and talk to our sales team</p>
		</div>
	</div>
	<div class="flex items-center justify-evenly">
		<div class="card sm:mt-36 lg:mt-96 w-96 bg-base-100 shadow-xl">
			<figure><Icon icon="gg:phone" height="8rem" /></figure>
			<div class="card-body text-center">
				<h2 class="text-3xl font-bold">Call Us!</h2>
				<div class="divider" />
				<p class="font-semibold">Our Sales Team:</p>
				<div class="flex flex-row items-end content-start">
					<p>+49 180 12837283</p>
					<button class="btn btn-xs">copy!</button>
				</div>
				<div class="divider" />
				<p class="font-semibold">Our IT-Support:</p>
				<div class="flex flex-row items-end content-start">
					<p>+49 180 83718277</p>
					<button class="btn btn-xs">copy!</button>
				</div>

				<!-- <div class="card-actions justify-end"> -->
				<!-- 	<button class="btn btn-primary">Buy Now</button> -->
				<!-- </div> -->
			</div>
		</div>

		<div class="card sm:mt-36 lg:mt-96 w-96 bg-base-100 shadow-xl">
			<figure><Icon icon="ic:baseline-email" height="8rem" /></figure>
			<div class="card-body text-center">
				<h2 class="text-3xl font-bold">Email Us!</h2>
				<div class="divider" />
				<p class="font-semibold">Our Sales Team:</p>
				<div class="flex flex-row items-end content-start">
					<p>sales@emeraldsolutons.de</p>
					<button class="btn btn-xs">copy!</button>
				</div>
				<div class="divider" />
				<p class="font-semibold">Our IT-Support:</p>
				<div class="flex flex-row items-end content-start">
					<p>it@emeraldsolutons.de</p>
					<button class="btn btn-xs">copy!</button>
				</div>

				<!-- <div class="card-actions justify-end"> -->
				<!-- 	<button class="btn btn-primary">Buy Now</button> -->
				<!-- </div> -->
			</div>
		</div>

		<div class="card sm:mt-36 lg:mt-96 w-96 bg-base-100 shadow-xl">
			<figure><Icon icon="ic:baseline-discord" height="8rem" /></figure>
			<div class="card-body text-center">
				<h2 class="text-3xl font-bold">Join our Discord Server!</h2>
				<div class="divider" />
				<p class="font-semibold">Our IT-Support:</p>
				<div class="flex flex-row items-end content-start">
					<p>+49 180 83718277</p>
					<button class="btn btn-xs">copy!</button>
				</div>

				<div class="card-actions justify-center mt-6">
					<button class="btn btn-primary">Join Now</button>
				</div>
			</div>
		</div>
	</div>
</div>
