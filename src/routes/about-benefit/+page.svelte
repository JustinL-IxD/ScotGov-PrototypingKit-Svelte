<script>
	import PrimaryButton from "$lib/Buttons/PrimaryButton.svelte";
	import SecondaryButton from "$lib/Buttons/SecondaryButton.svelte";
	import TextInput from "$lib/Forms/TextInput.svelte";
	import Body from "$lib/Typography/Body.svelte";
	import H1 from "$lib/Typography/H1.svelte";
</script>

<H1>About Benefit</H1>
<Body>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</Body>
<TextInput heading="First name(s)" type="text" />
<TextInput heading="Last name" type="text" />
<SecondaryButton name="Back" destination="about-user" /> 
<PrimaryButton name="Continue"  />