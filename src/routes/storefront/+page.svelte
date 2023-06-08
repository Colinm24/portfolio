<script>
	import ProductGrid from '$lib/components/ProductGrid.svelte';
	import HeroImageButton from '$lib/components/hero/HeroImageButton.svelte';
</script>

<!--Storefront hero-->
<HeroImageButton
	title="Welcome to the Store"
	subtitle="Purchase the best of the best"
	buttonText="Shop Now"
	bgImage="https://www.ceotodaymagazine.com/CEO-Today/wp-content/uploads/2018/04/Nitin-Kumar-The-CEO-Consultant-from-Silicon-Valley.jpg"
/>
<!--Product List-->
<ProductGrid />
