
<script>
	import Testimonial from '$lib/components/testimonial/Testimonial.svelte';
</script>


<section class='bg-neutral-100 w-full flex place-content-center py-10'>
	<div class='grid grid-cols-3 md:grid-cols-3 gap-4 w-3/4'>
		<Testimonial
			company='Tesla'
			logo='https://upload.wikimedia.org/wikipedia/commons/thumb/3/34/Elon_Musk_Royal_Society_%28crop2%29.jpg/1200px-Elon_Musk_Royal_Society_%28crop2%29.jpg'
			name='Elon Musk'
			quote='"Buy Tesla Stocks Buy Tesla Stocks Buy Tesla Stocks Buy Tesla Stocks Buy Tesla Stocks Buy Tesla Stocks Buy Tesla Stocks Buy Tesla Stocks"'
			role='CEO'
		/>
		<Testimonial
			company='Fast and Furious'
			logo='https://encrypted-tbn1.gstatic.com/licensed-image?q=tbn:ANd9GcR8JsW5BpMjYavaYInWmsjmxg9wL-iO6TL3ZqXwwrDkdWNC-MG3XKk_LmBVlTN-e73v83-Lod4iUC-BjTY'
			name='Vin Diesel'
			quote='It doesn’t matter whether you win by an inch or a mile, winning is winning'
			role='CEO'
		/>
		<Testimonial
			company='Company'
			logo='https://static01.nyt.com/images/2021/05/25/multimedia/25xp-johncena/25xp-johncena-mediumSquareAt3X.jpg'
			name='John Cena'
			quote='Good morning, China…Now I have ice cream… I like ice cream very much…But “Fast and Furious 9″ is better than ice cream'
			role='CEO'
		/>
		<Testimonial
			company='Presidents and Co'
			logo='https://upload.wikimedia.org/wikipedia/commons/thumb/6/68/Joe_Biden_presidential_portrait.jpg/1200px-Joe_Biden_presidential_portrait.jpg'
			name='Joe Biden'
			quote='VOTE BIDEN 2024'
			role='CEO'
		/>
		<Testimonial
			company='Furtado Inc'
			logo='https://sippican.theweektoday.com/sites/beaverdam/files/2015/06/field/image/RMS%20vocab_2.jpg'
			name='Ethan Furtado'
			quote='This product changed my life for the better. I was struggling and in poverty and now Im a Multi-Trillionaire'
			role='CEO'
		/>

		<Testimonial
			company='Rock'
			logo='https://people.com/thmb/mYK-lIK22BHl71BJVb_9Lz9xRVY=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc():focal(309x0:311x2)/rock-insta-778d9e7296924ee1829c8293b7e942f6.jpg'
			name='Dwayne "The Rock" Johnson'
			quote='Its about drive, its about power  We stay hungry, we devour Put in the work, put in the hours and take whats ours (ahoo) Black and Samoan in my veins My culture bangin with Strange I change the game, so whats my motherfreakin (Rock)'
			role='Literal Rock'
		/>

	</div>
</section>
