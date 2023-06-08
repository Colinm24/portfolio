<script>
	import ProductGridCard from '$lib/components/ProductGridCard.svelte';
</script>

<div class="bg-white">
	<div class="mx-auto max-w-2xl px-4 py-16 sm:px-6 sm:py-24 lg:max-w-7xl lg:px-8">
		<h2 class="text-2xl font-bold tracking-tight text-gray-900">Customers also purchased</h2>

		<div class="mt-6 grid grid-cols-1 gap-x-6 gap-y-10 sm:grid-cols-2 lg:grid-cols-4 xl:gap-x-8">
			<ProductGridCard
				Image="https://m.media-amazon.com/images/I/71KeDAkw+0L._AC_UF894,1000_QL80_.jpg"
				Title="2TB SSD"
				Color="SAUMSUNG"
				Price="$129.99"
			/>
			<ProductGridCard
				Image="https://c1.neweggimages.com/ProductImage/20-250-088-V03.jpg"
				Title="1TB INTERNAL SSD"
				Color="Western Digital"
				Price="$75.49"
			/>

			<ProductGridCard
				Image="https://image-us.samsung.com/SamsungUS/home/computing/memory-and-storage/solid-state-drives/pdp/mz-n6e500bw/MZ-N6E500BW_120180108.jpg"
				Title="SSD 860 500GB SSD"
				Color="SAMSUNG"
				Price="$40.99"
			/>
			<ProductGridCard
				Image="https://m.media-amazon.com/images/I/81LzB6vrDpL.jpg"
				Title="Intel 2.5 Inch"
				Color="Intel"
				Price="$99.99"
			/>
		</div>
	</div>
</div>
