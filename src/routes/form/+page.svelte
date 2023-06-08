<section>
	<div class="p-48">
		<h1>Registration Form</h1>
		<p>Please fill out this form with the required information</p>
	</div>

	<form method="post" action="https://register-demo.freecodecamp.org">
		<fieldset>
			<label for="first-name"
				>Enter Your First Name: <input
					id="first-name"
					name="first-name"
					type="text"
					required
				/></label
			>
			<label for="last-name"
				>Enter Your Last Name: <input id="last-name" name="last-name" type="text" required /></label
			>
			<label for="email"
				>Enter Your Email: <input id="email" name="email" type="email" required /></label
			>
			<label for="new-password"
				>Create a New Password: <input
					id="new-password"
					name="new-password"
					type="password"
					pattern="[a-z0-5]"
					required
				/></label
			>
		</fieldset>
		<fieldset>
			<label for="personal-account"
				><input id="personal-account" type="radio" name="account-type" class="inline" /> Personal Account</label
			>
			<label for="business-account"
				><input id="business-account" type="radio" name="account-type" class="inline" /> Business Account</label
			>
			<label for="terms-and-conditions">
				<input
					id="terms-and-conditions"
					type="checkbox"
					required
					name="terms-and-conditions"
					class="inline"
				/>
				I accept the
				<a href="https://www.freecodecamp.org/news/terms-of-service/">terms and conditions</a>
			</label>
		</fieldset>
		<fieldset>
			<label for="profile-picture"
				>Upload a profile picture: <input id="profile-picture" type="file" name="file" /></label
			>
			<label for="age"
				>Input your age (years): <input
					id="age"
					type="number"
					name="age"
					min="13"
					max="120"
				/></label
			>
			<label for="referrer"
				>How did you hear about us?
				<select id="referrer" name="referrer">
					<option value="">(select one)</option>
					<option value="1">freeCodeCamp News</option>
					<option value="2">freeCodeCamp YouTube Channel</option>
					<option value="3">freeCodeCamp Forum</option>
					<option value="4">Other</option>
				</select>
			</label>
			<label for="bio"
				>Provide a bio:
				<textarea
					id="bio"
					name="bio"
					rows="3"
					cols="30"
					placeholder="I like coding on the beach..."
				/>
			</label>
		</fieldset>
		<input type="submit" value="Submit" />
	</form>
</section>

<style>
	section {
		width: 100%;
		height: 100%;
		margin: 0;
		background-color: #3d4b5f;
		color: #f5f6f7;
		font-family: Tahoma, serif;
		font-size: 16px;
	}

	h1,
	p {
		text-align: center;
		font-family: Ramaraja, serif;
		color: #8ec1d6;
	}

	form {
		width: 60vw;
		max-width: 500px;
		min-width: 300px;
		margin: 0 auto;
		padding-bottom: 2em;
	}

	fieldset {
		border: none;
		padding: 1rem 0;
		border-bottom: 3px solid #3b3b4f;
	}

	fieldset:last-of-type {
		border-bottom: none;
	}

	label {
		display: block;
		margin: 1.5rem 0;
	}

	input,
	textarea,
	select {
		margin: 10px 0 0 0;
		width: 100%;
		min-height: 2em;
	}

	input[type='text'],
	input[type='number'],
	input[type='email'],
	input[type='password'],
	textarea {
		background-color: #ffffff;
		border: 1px solid #0a0a23;
		box-shadow: 10px 10px 5px 0px rgba(0, 0, 0, 0.75);
		-webkit-box-shadow: 10px 10px 5px 0px rgba(0, 0, 0, 0.75);
		-moz-box-shadow: 10px 10px 5px 0px rgba(0, 0, 0, 0.75);
	}

	.inline {
		width: unset;
		margin: 0 0.5em 0 0;
		vertical-align: middle;
	}

	input[type='submit'] {
		display: block;
		width: 60%;
		margin: 1em auto;
		height: 2em;
		font-size: 1.1rem;
		background-color: #3b3b4f;
		border-color: white;
		min-width: 300px;
		color: #cbd5e1;
	}

	input[type='file'] {
		padding: 1px 2px;
	}

	a {
		color: #ffffff;
	}
</style>
