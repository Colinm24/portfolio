<script>
</script>
<div class="container">
	<div class="boxes">
		<div class="box box-start">
			<h2 class="title">Basic</h2>
			<div class="price">
				<span class="price-value">$9</span><span class="price-billed">/month</span>
			</div>
			<ul class="features">
				<li>Shared hosting</li>
				<li>512mb RAM</li>
				<li>20gb storage</li>
				<li>200gb bandwidth</li>
				<li><s>Choice of OS</s></li>
				<li><s>Host multiple sites</s></li>
			</ul>
			<a href="#" class="button">Get Started</a>
		</div>
		<div class="box box-center">
			<h2 class="title">Professional</h2>
			<div class="price">
				<span class="price-value">$18</span><span class="price-billed">/month</span>
			</div>
			<ul class="features">
				<li>VPS hosting</li>
				<li>4gb RAM</li>
				<li>40gb SSD storage</li>
				<li>1tb bandwidth</li>
				<li>Choice of OS</li>
				<li>Host multiple sites</li>
			</ul>
			<a href="#" class="button">Upgrade Now</a>
		</div>
		<div class="box box-end">
			<h2 class="title">Enterprise</h2>
			<div class="price">
				<span class="price-value">$36</span><span class="price-billed">/month</span>
			</div>
			<ul class="features">
				<li>Dedicated hosting</li>
				<li>12gb RAM</li>
				<li>120gb SSD storage</li>
				<li>1tb bandwidth</li>
				<li>Choice of OS</li>
				<li>Host multiple sites</li>
			</ul>
			<a href="#" class="button">Upgrade Now</a>
		</div>
	</div>
</div>

<style>
    .container {
        padding: 10% 0;
        background-color: #276b93;
    }
    .boxes {
        display: flex;
        align-items: center;
        max-width: 798px;
        margin: auto;
    }

    /* Box */
    .box {
        position: relative;
        flex: 1;
        font-family: Work Sans, sans-serif;
        border-radius: 4px;
        background-color: #ffffff;
        color: #000000;
        text-align: center;
        box-shadow: 0 2px 2px rgba(54, 141, 115, 0.4),
        0 2px 12px rgba(77, 184, 152, 0.4);
    }
    .box-outer {
        padding: 60px 0;
    }
    .box-inner {
        padding: 72px 0;
        margin: 0 -12px;
        z-index: 1;
    }

    /* Title */
    .title {
        color: #000000;
        font-size: 36px;
        font-weight: 300;
        letter-spacing: -0.05em;
        margin: 0 0 18px;
    }

    /* Price */
    .price {
        padding: 12px;
        background-color: #fff6e5;
        color: #29d040;
        font-weight: 600;
        font-size: 18px;
    }
    .price-value {
        font-size: 24px;
    }
    .price-billed {
        font-variant: small-caps;
    }

    /* Features */
    .features {
        margin: 0;
        padding: 24px;
    }
    .features s {
        color: #434948;
    }
    .features li {
        line-height: 2;
        list-style: none;
    }
    .features li:first-child {
        font-weight: 600;
    }

    /* Button */
    .button {
        display: inline-block;
        background-color: #3ab641;
        color: #ffffff;
        padding: 12px 24px;
        border-radius: 4px;
        text-decoration: none;
        font-weight: 600;
        transition: 0.3s;
    }
    .button:hover,
    .button:focus {
        color: #94debf;
        box-shadow: inset 0 -44px #de1010;
    }
    .button:active {
        transform: scale(0.95455);
    }
</style>
