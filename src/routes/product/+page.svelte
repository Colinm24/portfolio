<script>
	import SubscribeImage from '$lib/assets/960x0.jpg';
	import HeroImageButton from '$lib/components/hero/HeroImageButton.svelte';
	import TestimonialGrid
		from '$lib/components/testimonial/TestimonialGrid.svelte';
</script>
<HeroImageButton
	title="Storage Prices"
	subtitle="For your business"
	buttonText="View Plans"
/>


<style>
    body {
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
        background-color: #333333;
        font-family: Arial, sans-serif;
        color: #333;
    }

    .description {
        text-align: center;
        width: 80%;
        max-width: 600px;
        margin: auto;
        padding: 20px;
        box-sizing: border-box;
        background-color: #fff;
        border-radius: 8px;
        box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    }

    h2 {
        font-size: 24px;
        margin-bottom: 15px;
        color: #333;
    }

    h3 {
        font-size: 18px;
        margin-bottom: 8px;
        color: #333;
    }

    p {
        font-size: 16px;
        line-height: 1.5;
        margin-bottom: 15px;
        color: #555;
    }
</style>

<div class="description">
	<h2>Efficient Data Storage Solutions</h2>
	<p>At [Your Company Name], we understand the importance of efficient data storage for modern computer users. With the rapid advancement of technology and the ever-increasing size of files, having ample storage capacity has become essential. We offer cutting-edge storage solutions tailored to meet the diverse needs of individuals and businesses alike.</p>

	<h3>Benefits of Our Storage Solutions</h3>
	<p>Investing in our storage solutions brings a host of benefits. First and foremost, our high-capacity storage options allow you to store vast amounts of data, including documents, photos, videos, and applications, ensuring you never run out of space. Our products provide lightning-fast access and transfer speeds, enabling seamless multitasking, smooth media streaming, and quick file sharing.</p>

	<h3>Prioritizing Data Security</h3>
	<p>In addition to capacity and speed, our storage solutions prioritize data security. We employ advanced encryption and backup features to protect your valuable information from unauthorized access, hardware failures, or unforeseen events. With our reliable storage devices, you can confidently safeguard your sensitive files and important documents.</p>

	<h3>Catering to Your Needs</h3>
	<p>Whether you are a professional who relies on extensive data processing, a creative individual working with large multimedia files, or a casual user looking for a hassle-free storage experience, our products cater to your specific requirements. We offer a range of options, including solid-state drives (SSDs), hard disk drives (HDDs), and network-attached storage (NAS), to suit various budgets and usage scenarios.</p>

	<h3>Exceptional Support and Peace of Mind</h3>
	<p>By choosing [Your Company Name], you gain access to top-quality storage solutions backed by exceptional customer support. Our team of experts is ready to assist you in finding the ideal storage solution for your computer, ensuring optimal performance and peace of mind.</p>

	<h3>Unlock the Full Potential of Your Computer</h3>
	<p>Don't let limited storage capacity hold you back. Invest in our reliable and high-performance storage solutions to enhance your computing experience, streamline your workflow, and unlock the full potential of your computer.</p>
</div>

<head>
	<style>
      .hero {
          position: relative;
          width: 100%;
          height: 950px;
          background-color: #ffffff;
          overflow: hidden;
      }

      .hero-image {
          width: 100%;
          height: 100%;
          object-fit: cover;
      }

      .hero-content {
          position: absolute;
          top: 50%;
          left: 50%;
          transform: translate(-50%, -50%);
          text-align: center;
          color: #000000;
      }

      .hero-title {
          font-size: 36px;
          margin-bottom: 20px;
					font-weight: bold;
      }

      .hero-description {
          font-size: 18px;
          margin-bottom: 40px;
      }

      .hero-button {
          padding: 12px 24px;
          font-size: 18px;
          background-color: #A020F0;
          color: #ffffff;
          border: none;
          border-radius: 4px;
          cursor: pointer;
      }
	</style>
</head>
<body>
<div class="hero">
	<img src="https://i.pcmag.com/imagery/roundups/03yy022DDsenwhBBYdxvwDi-3..v1593631883.jpg" alt="Cloud Storage" class="hero-image">
	<div class="hero-content">
		<h1 class="hero-title">Store Your Files in the Cloud</h1>
		<p class="hero-description">Secure and reliable cloud storage solutions for all your important files.</p>
		<button class="hero-button">Get Started</button>
	</div>
</div>
</body>


<div class="flex items-center justify-center min-h-screen
bg-slate-800">
	<!-- Inner Container -->
	<div
		class="flex flex-col my-6 space-y-6 md:space-y-0
md:space-x-6 md:flex-row md:my-0"
	>
		<!-- Col 1 -->
		<div class="bg-slate-700 rounded-xl text-white">
			<!-- Upper Container -->
			<div class="p-8 mx-3 mt-3 rounded-t-xl bg-slate-800">
				<div class="text-center uppercase">Basic</div>
				<h1 class="mt-10 font-serif text-5xl

text-center">100GB</h1>

				<h1 class="mt-2 text-center">$1.99/Month</h1>
				<div class="flex justify-center">
					<a
						href="#"
						class="inline-block px-10 py-3 my-6 text-center

border border-violet-600 rounded-lg duration-200
hover:bg-violet-800 hover:border-violet-800"

					>Purchase</a
					>
				</div>
			</div>

			<!-- Border -->
			<div class="border-t border-slate-700"></div>

			<!-- Lower Container -->
			<div class="p-8 mx-3 mb-3 rounded-b-xl bg-slate-800">
				<!-- List Container -->
				<div class="flex flex-col space-y-2">
					<!-- List Item 1 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">100 GB of storage</span>
					</div>

					<!-- List Item 2 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"

							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">Option to add

members</span>
					</div>

					<!-- List Item 3 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>

						<span class="text-sm ml-1">Extra member

benefits</span>
					</div>
				</div>
			</div>
		</div>

		<!-- Col 2 -->
		<div class="bg-white rounded-xl text-white">
			<!-- Upper Container -->
			<div class="p-8 mx-3 mt-3 rounded-t-xl bg-slate-800">
				<div class="text-center uppercase">Standard</div>
				<h1 class="mt-10 font-serif text-5xl

text-center">200GB</h1>

				<h1 class="mt-2 text-center">$3.99/Month</h1>
				<div class="flex justify-center">
					<a
						href="#"
						class="inline-block px-10 py-3 my-6 text-center
border border-violet-600 rounded-lg duration-200 bg-violet-600
hover:bg-violet-800 hover:border-violet-800"

					>Purchase</a
					>
				</div>
			</div>

			<!-- Border -->
			<div class="border-t border-slate-700"></div>

			<!-- Lower Container -->

			<div class="p-8 mx-3 mb-3 rounded-b-xl bg-slate-800">
				<!-- List Container -->
				<div class="flex flex-col space-y-2">
					<!-- List Item 1 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">200 GB of storage</span>
					</div>

					<!-- List Item 2 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"

							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">Option to add

members</span>
					</div>

					<!-- List Item 3 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">Extra member

benefits</span>

					</div>
				</div>
			</div>
		</div>

		<!-- Col 3 -->
		<div class="bg-slate-700 rounded-xl text-white">
			<!-- Upper Container -->
			<div class="p-8 mx-3 mt-3 rounded-t-xl bg-slate-800">
				<div class="text-center uppercase">Premium</div>
				<h1 class="mt-10 font-serif text-5xl text-center">2

																													TB</h1>

				<h1 class="mt-2 text-center">$8.99/Month</h1>
				<div class="flex justify-center">
					<a
						href="#"
						class="inline-block px-10 py-3 my-6 text-center

border border-violet-600 rounded-lg duration-200
hover:bg-violet-800 hover:border-violet-800"

					>Purchase</a
					>
				</div>
			</div>

			<!-- Border -->
			<div class="border-t border-slate-700"></div>

			<!-- Lower Container -->
			<div class="p-8 mx-3 mb-3 rounded-b-xl bg-slate-800">
				<!-- List Container -->

				<div class="flex flex-col space-y-2">
					<!-- List Item 1 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">2 TB of storage</span>
					</div>

					<!-- List Item 2 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"

							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">Option to add

members</span>
					</div>

					<!-- List Item 3 -->
					<div class="flex justify-center">
						<svg
							xmlns="http://www.w3.org/2000/svg"
							class="w-5 h-5"
							viewBox="0 0 24 24"
							stroke-width="2"
							stroke="currentColor"
							fill="none"
							stroke-linecap="round"
							stroke-linejoin="round"
						>
							<path stroke="none" d="M0 0h24v24H0z" fill="none"

							/>

							<path d="M5 12l5 5l10 -10" />
						</svg>
						<span class="text-sm ml-1">Exclusive Benefits for You</span>
					</div>
				</div>

			</div>
		</div>
	</div>
</div>

<TestimonialGrid/>

<section class="flex items-center justify-center h-full p-10 bg-zinc-700">
	<div class="bg-zinc-800 p-2 mx-6 rounded-2xl">
		<div class="flex flex-col md:flex-row rounded-l-xl">
			<img src={SubscribeImage} alt="electronics" class="object-fit rounded-xl h-80 md:h-64 md:rounded-l-xl md:rounded-r-none transform hover:scale-105 hover:rounded-xl duration-200" />
			<div class="p-6 md:p-12">
				<h2 class="font-serif text-xl font-medium text-center text-white md:text-left">Get the latest tech updates in your inbox.</h2>
				<p class="max-w-xs text-xs leading-5 tracking-wide text-center text-white md:text-left">Stay up-to-date with the latest electronics news, deals, and trends. Sign up for the Electronics newsletter.</p>
				<div class="flex flex-col mt-5 space-y-4 md:space-x-3 md:flex-row md:space-y-0">
					<input type="text" placeholder="Enter your email address" class="p-2 px-4 text-center text-white bg-zinc-800 border border-zinc-600 placeholder:text-xs placeholder:text-center md:text-left placeholder:md:text-left focus:outline-none"/>
					<button class="px-5 py-3 text-xs rounded-md text-zinc-800 bg-white border border-zinc-600 hover:bg-zinc-600 hover:text-zinc-800 duration-500">Subscribe</button>
				</div>
			</div>
		</div>
	</div>
</section>

