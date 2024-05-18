<script lang="ts">
	import { base } from "$app/paths";

	function scroll({ target}: {target:any}) {
		// const el = document.querySelector(target.getAttribute('href') as string);

		const t = target.parentElement.getAttribute('href');
		const el = document.querySelector(t);
		if (!el) return;
		el.scrollIntoView({
			behavior: 'smooth'
		});
	}
</script>

<div class="min-h-screen bg-base-200">
	<div class="md:flex justify-evenly py-60 mb-80">
		<div class="flex items-center justify-center ">
			<a href="#websites" on:click|preventDefault={scroll}>
				<img class="h-60 w-80 blur-md hover:scale-105" src="{base}/images/website.png" alt="" />

			</a>
			<span class="absolute text-center  text-2xl font-bold">Websites</span>
		</div>

		<div class="flex items-center justify-center">
			<a href="#desktop" on:click|preventDefault={scroll}>
				<img class="h-60 w-80 blur-md hover:scale-105" src="{base}/images/desktop.png" alt="" />
			</a>
			<span class="absolute text-center text-2xl font-bold">Desktop Applications</span>
		</div>

		<div class="flex items-center justify-center">
			<a href="#automation" on:click|preventDefault={scroll}>
				<img class="h-60 w-80 blur-md hover:scale-105" src="{base}/images/automation.png" alt="" />
			</a>
			<span class="absolute text-center text-2xl font-bold">Automation</span>
		</div>
	</div>
	<div class="bg-black text-white">
		<div class="hero h-[45rem]" id="websites">
			<div class="hero-content flex-col lg:flex-row-reverse">
				<img src="{base}/images/website.png" class="h-64 max-w-sm rounded-lg shadow-2xl" />
				<div>
					<h1 class="text-5xl font-bold">Websites</h1>
					<p class="py-6">
						Unser Ziel ist es, Ihnen dabei zu helfen, Ihre Online-Präsenz zu stärken und zu
						optimieren. Egal, ob Sie eine neue Website von Grund auf erstellen möchten, Ihre
						bestehende Website überarbeiten oder einzigartige Weblösungen für Ihr Unternehmen
						entwickeln wollen, wir haben die richtigen Tools und Experten, um Ihre Vision in die
						Realität umzusetzen.
					</p>
				</div>
			</div>
		</div>

		<div class="hero h-[45rem]" id="desktop">
			<div class="hero-content flex-col lg:flex-row">
				<img src="{base}/images/desktop.png" class="h-64 max-sm:w-[90%] max-w-sm rounded-lg shadow-2xl" />
				<div>
					<h1 class="text-5xl font-bold ">Desktop Applications</h1>
					<p class="py-6 ">
						Selbstverständlich bieten wir Ihnen eine umfassende Palette von Dienstleistungen im
						Bereich der Desktop-Anwendungsentwicklung an. Unser Ziel ist es, Ihnen dabei zu helfen,
						maßgeschneiderte Softwarelösungen zu entwickeln, die Ihre Geschäftsprozesse optimieren
						und Ihre Ziele erreichen. Egal, ob Sie eine spezielle Hardware-Anwendung, eine
						Systemebene-Software oder eine komplexe 3D-Modellierungssoftware benötigen, wir haben
						die Expertise und die Tools, um Ihre Vision in die Realität umzusetzen.
					</p>
				</div>
			</div>
		</div>
		<div class="hero h-[45rem]" id="automation">
			<div class="hero-content flex-col lg:flex-row-reverse">
				<img src="{base}/images/automation.png" class="h-64 max-w-sm rounded-lg shadow-2xl" />
				<div>
					<h1 class="text-5xl font-bold">Automation</h1>
					<p class="py-6">
						Wie schaffen sie es lästige Aufgaben, die nur Zeit und Geld kosten loszuwerden? Wir
						optimieren ihr Alltagsgeschäft und gestalten es effizienter. Egal, ob Sie sich auf die
						Automatisierung einzelner Aufgaben, den gesamten Arbeitsablauf oder unternehmensweite
						Prozesse konzentrieren möchten, wir haben die Expertise und die Tools, um Ihre Vision in
						die Realität umzusetzen.
					</p>
				</div>
			</div>
		</div>
		<div class="h-60" />
	</div>
</div>
