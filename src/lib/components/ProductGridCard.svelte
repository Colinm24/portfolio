<script>
	export let Image = 'https://m.media-amazon.com/images/I/71KeDAkw+0L._AC_UF894,1000_QL80_.jpg';
	export let Title = 'title';
	export let Color = 'color';
	export let Price = '$';
</script>

<div class="group relative">
	<div
		class="aspect-h-1 aspect-w-1 w-full overflow-hidden rounded-md bg-gray-200 lg:aspect-none group-hover:opacity-75 lg:h-80"
	>
		<img
			src={Image}
			alt="The"
			class="h-full w-full object-cover object-center lg:h-full lg:w-full"
		/>
	</div>
	<div class="mt-4 flex justify-between">
		<div>
			<h3 class="text-sm text-gray-700">
				<a href="#">
					<span aria-hidden="true" class="absolute inset-0" />
					{Title}
				</a>
			</h3>
			<p class="mt-1 text-sm text-gray-500">{Color}</p>
		</div>
		<p class="text-sm font-medium text-gray-900">{Price}</p>
	</div>
</div>
