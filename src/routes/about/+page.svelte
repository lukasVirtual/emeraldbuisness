<script lang="ts">
	import { base } from "$app/paths";

</script>


<div class="relative min-h-[45vh] flex items-center justify-center bg-black">
	<img class="object-cover blur-md w-full h-[45vh]" src="{base}/images/partner.png" alt="" />

	<figure class="absolute mx-auto">

	<h1
		class=" font-extrabold text-white  text-center text-6xl "
	>
		Ihr neuer Partner!
	</h1>
	<p
		class="font-bold text-gray-200 text-center"
	>
		Moderne Software welche ihr Unternehmen repräsentiert
	</p>

	<a href="{base}/contact" class="relative left-[28%] mt-10  btn bg-green-400">Kontaktieren sie uns!</a>

	</figure>
</div>
<div class="flex text-white flex-col-reverse items-center pt-10 bg-black">
	<div
		class="
		flex-col
		w-[40%] md:h-[35rem]"
	>
		<h1 class="text-5xl pt-20 text-center">Wer sind wir?</h1>
		<p class="break-word md:break-all mt-8">
			Wir sind ein junges Unternehmen, welches sich ein Ziel gesetzt hat Software auf einen neuen
			Standard zu bringen! Deutschland war und ist für Qualität bekannt in der Industrie, jedoch
			nicht in der Digitalen Welt. Das Ändern wir! Pünktlich, Perfekt und Wunderschön. Das sind wir
			und unsere Software.
		</p>
	</div>
</div>

<div class="flex  text-white flex-col-reverse items-center pt-10 bg-black">
	<div
		class="
		w-[40%] md:h-[35rem]"
	>
		<h1 class="text-5xl text-center">Warum sie uns für ihr nächstes Projekt wählen sollten!</h1>
		<p class="break-word md:break-all mt-8">
			Durch Mehrjährige Erfahrung in der IT-Branche wissen wir die Schwächen und Umsatzkiller vieler
			Unternehmen, welche wir erfolgreich für Unternehmen lösen. Unternehmen brauchen
			Geschwindigkeit, Erreichbarkeit und Qualität all dies verstehen wir und setzen es erfolgreich
			in der Praxis um. Überzeugen sie sich selbst!
		</p>
	</div>
</div>
<!-- <div class="flex flex-col md:flex-row items-center justify-center bg-black ">
    <img class="object-cover blur-md w-full h-[45vh]" src="{base}/images/partner.png" alt="" />
    <h1 class="absolute font-extrabold text-white  left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center text-6xl">
        Ihr neuer Partner!
    </h1>
    <p class="absolute font-bold text-gray-200 mt-16 left-1/2 transform -translate-x-1/2 -translate-y-1/2 text-center">
        Moderne Software welche ihr Unternehmen repräsentiert
    </p>
    <a href="{base}/contact" class="absolute mt-36 btn bg-green-400 text-white px-4 py-2 rounded-lg">Kontaktieren sie uns!</a>
</div>
<div class="flex flex-col-reverse items-center pt-10 bg-black min-h-screen">
    <div class="hero-content text-white flex flex-col w-[40%] h-[35rem] mx-auto">
        <h1 class="text-5xl text-center">Wer sind wir?</h1>
        <p class="break-word md:break-all mt-8">
            Wir sind ein junges Unternehmen, welches sich ein Ziel gesetzt hat Software auf einen neuen Standard zu bringen Deutschland war und ist für Qualität bekannt in der Industrie, jedoch nicht in der Digitalen Welt. Das Ändern wir Pünktlich, Perfekt und Wunderschön. Das sind wir und unsere Software.
        </p>
    </div>
</div> -->
<!-- <div class="flex text-white bg-black">
	<div
		class="
	bg-black
	text-white
	mt-11
	w-full
	stats shadow"
	>
		<div class="stat">
			<div class="stat-figure text-secondary text-center">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					class="inline-block w-8 h-8 stroke-current"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"
					/></svg
				>
			</div>
			<div class="text-center">
				<div class="stat-title text-white">Downloads</div>
				<div class="stat-value text-white">31K</div>
				<div class="stat-desc text-white">Jan 1st - Feb 1st</div>
			</div>
		</div>

		<div class="stat">
			<div class="stat-figure text-secondary">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					class="inline-block w-8 h-8 stroke-current"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4"
					/></svg
				>
			</div>
			<div class="text-center">
				<div class="stat-title text-white">New Users</div>
				<div class="stat-value text-white">4,200</div>
				<div class="stat-desc text-white">↗︎ 400 (22%)</div>
			</div>
		</div>

		<div class="stat">
			<div class="stat-figure text-secondary">
				<svg
					xmlns="http://www.w3.org/2000/svg"
					fill="none"
					viewBox="0 0 24 24"
					class="inline-block w-8 h-8 stroke-current"
					><path
						stroke-linecap="round"
						stroke-linejoin="round"
						stroke-width="2"
						d="M5 8h14M5 8a2 2 0 110-4h14a2 2 0 110 4M5 8v10a2 2 0 002 2h10a2 2 0 002-2V8m-9 4h4"
					/></svg
				>
			</div>
			<div class="text-center">
				<div class="stat-title text-white">New Registers</div>
				<div class="stat-value text-white">1,200</div>
				<div class="stat-desc text-white">↘︎ 90 (14%)</div>
			</div>
		</div>
	</div>
</div> -->

<!-- <div -->
<!-- 	class=" -->
<!-- 	bg-black -->
<!-- 	text-white -->
<!-- 	mt-11 -->
<!-- 	w-[40%] -->
<!-- 	stats shadow" -->
<!-- > -->
<!-- 	<div class="stat"> -->
<!-- 		<div class="stat-figure text-secondary"> -->
<!-- 			<svg -->
<!-- 				xmlns="http://www.w3.org/2000/svg" -->
<!-- 				fill="none" -->
<!-- 				viewBox="0 0 24 24" -->
<!-- 				class="inline-block w-8 h-8 stroke-current" -->
<!-- 				><path -->
<!-- 					stroke-linecap="round" -->
<!-- 					stroke-linejoin="round" -->
<!-- 					stroke-width="2" -->
<!-- 					d="M13 16h-1v-4h-1m1-4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z" -->
<!-- 				/></svg -->
<!-- 			> -->
<!-- 		</div> -->
<!-- 		<div class="stat-title">Downloads</div> -->
<!-- 		<div class="stat-value">31K</div> -->
<!-- 		<div class="stat-desc">Jan 1st - Feb 1st</div> -->
<!-- 	</div> -->
<!---->
<!-- 	<div class="stat"> -->
<!-- 		<div class="stat-figure text-secondary"> -->
<!-- 			<svg -->
<!-- 				xmlns="http://www.w3.org/2000/svg" -->
<!-- 				fill="none" -->
<!-- 				viewBox="0 0 24 24" -->
<!-- 				class="inline-block w-8 h-8 stroke-current" -->
<!-- 				><path -->
<!-- 					stroke-linecap="round" -->
<!-- 					stroke-linejoin="round" -->
<!-- 					stroke-width="2" -->
<!-- 					d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" -->
<!-- 				/></svg -->
<!-- 			> -->
<!-- 		</div> -->
<!-- 		<div class="stat-title text-white">New Users</div> -->
<!-- 		<div class="stat-value text-white">4,200</div> -->
<!-- 		<div class="stat-desc text-white">↗︎ 400 (22%)</div> -->
<!-- 	</div> -->
<!---->
<!-- 	<div class="stat"> -->
<!-- 		<div class="stat-figure text-secondary"> -->
<!-- 			<svg -->
<!-- 				xmlns="http://www.w3.org/2000/svg" -->
<!-- 				fill="none" -->
<!-- 				viewBox="0 0 24 24" -->
<!-- 				class="inline-block w-8 h-8 stroke-current" -->
<!-- 				><path -->
<!-- 					stroke-linecap="round" -->
<!-- 					stroke-linejoin="round" -->
<!-- 					stroke-width="2" -->
<!-- 					d="M5 8h14M5 8a2 2 0 110-4h14a2 2 0 110 4M5 8v10a2 2 0 002 2h10a2 2 0 002-2V8m-9 4h4" -->
<!-- 				/></svg -->
<!-- 			> -->
<!-- 		</div> -->
<!-- 		<div class="stat-title">New Registers</div> -->
<!-- 		<div class="stat-value">1,200</div> -->
<!-- 		<div class="stat-desc">↘︎ 90 (14%)</div> -->
<!-- 	</div> -->
<!-- </div> -->
