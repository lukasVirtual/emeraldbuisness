<script lang="ts">
	function scroll({ target }: { target: any }) {
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
	<div class="flex justify-evenly py-60 mb-80">
		<div class="flex items-center justify-center">
			<a href="#websites" on:click|preventDefault={scroll}>
				<img class="h-60 w-80 blur-md" src="/images/website.jpg" alt="" />
			</a>
			<span class=" absolute text-center text-white text-2xl font-bold">Websites</span>
		</div>

		<div class="flex items-center justify-center">
			<a href="#desktop" on:click|preventDefault={scroll}>
				<img class="h-60 w-80 blur-md" src="/images/desktop.jpg" alt="" />
			</a>
			<span class="absolute text-center text-white text-2xl font-bold">Desktop Applications</span>
		</div>

		<div class="flex items-center justify-center">
			<a href="#automation" on:click|preventDefault={scroll}>
				<img class="h-60 w-80 blur-md" src="/images/automation.jpg" alt="" />
			</a>
			<span class="absolute text-center text-white text-2xl font-bold">Automation</span>
		</div>
	</div>
	<div class="bg-black text-white">
		<div class="hero h-[45rem]" id="websites">
			<div class="hero-content flex-col lg:flex-row-reverse">
				<img src="/images/website.jpg" class="h-64 max-w-sm rounded-lg shadow-2xl" />
				<div>
					<h1 class="text-5xl font-bold">Websites</h1>
					<p class="py-6">
						L odio bibendum euismod tempor a quam. Molestie in scelerisque rhoncus ultrices eget
						massa faucibus. Amet integer pulvinar aliquet tristique et morbi tempus commodo.
						Sollicitudin massa porttitor blandit tortor pellentesque. Lectus ullamcorper ultrices
						duis turpis euismod mauris tincidunt. Nulla fringilla eget est dapibus. Elementum eget
						nunc urna semper neque. Egestas lobortis turpis senectus suspendisse nisl lorem. Commodo
						commodo libero sem in sed. L odio bibendum euismod tempor a quam. Molestie in
						scelerisque rhoncus ultrices eget massa faucibus. Amet integer pulvinar aliquet
						tristique et morbi tempus commodo. Sollicitudin massa porttitor blandit tortor
						pellentesque. Lectus ullamcorper ultrices duis turpis euismod mauris tincidunt. Nulla
						fringilla eget est dapibus. Elementum eget nunc urna semper neque. Egestas lobortis
						turpis senectus suspendisse nisl lorem. Commodo commodo libero sem in sed.
					</p>
				</div>
			</div>
		</div>

		<div class="hero h-[45rem]" id="desktop">
			<div class="hero-content flex-col lg:flex-row">
				<img src="/images/desktop.jpg" class="max-w-sm rounded-lg shadow-2xl" />
				<div>
					<h1 class="text-5xl font-bold text-right">Desktop Applications</h1>
					<p class="py-6 text-right">
						L odio bibendum euismod tempor a quam. Molestie in scelerisque rhoncus ultrices eget
						massa faucibus. Amet integer pulvinar aliquet tristique et morbi tempus commodo.
						Sollicitudin massa porttitor blandit tortor pellentesque. Lectus ullamcorper ultrices
						duis turpis euismod mauris tincidunt. Nulla fringilla eget est dapibus. Elementum eget
						nunc urna semper neque. Egestas lobortis turpis senectus suspendisse nisl lorem. Commodo
						commodo libero sem in sed. L odio bibendum euismod tempor a quam. Molestie in
						scelerisque rhoncus ultrices eget massa faucibus. Amet integer pulvinar aliquet
						tristique et morbi tempus commodo. Sollicitudin massa porttitor blandit tortor
						pellentesque. Lectus ullamcorper ultrices duis turpis euismod mauris tincidunt. Nulla
						fringilla eget est dapibus. Elementum eget nunc urna semper neque. Egestas lobortis
						turpis senectus suspendisse nisl lorem. Commodo commodo libero sem in sed.
					</p>
				</div>
			</div>
		</div>
		<div class="hero h-[45rem]" id="automation">
			<div class="hero-content flex-col lg:flex-row-reverse">
				<img src="/images/automation.jpg" class="h-64 max-w-sm rounded-lg shadow-2xl" />
				<div>
					<h1 class="text-5xl font-bold">Automation</h1>
					<p class="py-6">
						L odio bibendum euismod tempor a quam. Molestie in scelerisque rhoncus ultrices eget
						massa faucibus. Amet integer pulvinar aliquet tristique et morbi tempus commodo.
						Sollicitudin massa porttitor blandit tortor pellentesque. Lectus ullamcorper ultrices
						duis turpis euismod mauris tincidunt. Nulla fringilla eget est dapibus. Elementum eget
						nunc urna semper neque. Egestas lobortis turpis senectus suspendisse nisl lorem. Commodo
						commodo libero sem in sed. L odio bibendum euismod tempor a quam. Molestie in
						scelerisque rhoncus ultrices eget massa faucibus. Amet integer pulvinar aliquet
						tristique et morbi tempus commodo. Sollicitudin massa porttitor blandit tortor
						pellentesque. Lectus ullamcorper ultrices duis turpis euismod mauris tincidunt. Nulla
						fringilla eget est dapibus. Elementum eget nunc urna semper neque. Egestas lobortis
						turpis senectus suspendisse nisl lorem. Commodo commodo libero sem in sed.
					</p>
				</div>
			</div>
		</div>
		<div class="h-60" />
	</div>
</div>
