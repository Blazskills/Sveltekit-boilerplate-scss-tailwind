<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>


Tailwind style <br/>
<span class="text-[20px] font-bold underline text-[white]">Hello world!, tailwind css style</span>


<p>
    To activate the Tailwind css, uncomment tailwind style in <strong>src/routes/+layout.svelte</strong>
</p>


<br/>
<br/>
<br/>
<br/>
<br/>
<input />

<select name="" id="">
	<option value="Option">Option</option>
</select>
<button>Button</button>

<!-- cspell:ignore unsass -->
<style lang="scss">
	h1 {
		color: rgb(255, 0, 251);
		font-size: functions.toRem(36);
		@include breakpoint.up('md') {
			color: green;
		}

		@include breakpoint.up('lg') {
			color: blue;
		}
		@include breakpoint.down('sm') {
			color: indigo;
		}
		&:hover {
			text-decoration: underline;
			cursor: pointer;
			color: rgb(174, 218, 0);
		}
	}
</style>
