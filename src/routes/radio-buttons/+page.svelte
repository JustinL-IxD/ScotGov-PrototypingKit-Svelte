<script>
    import H1 from "$lib/Typography/H1.svelte";
	import TextInput from "$lib/Forms/TextInput.svelte";
	import Radiobuttons from "$lib/Forms/RadioButtons.svelte";
	import Body from "$lib/Typography/Body.svelte";
	import PrimaryButton from "$lib/Buttons/PrimaryButton.svelte";
	import SecondaryButton from "$lib/Buttons/SecondaryButton.svelte";
    
</script>


<H1>Do you exercise regularly?</H1>
<Body>We can use this page to create something that takes users to other places, changing the content to reflect what we want</Body>
<Radiobuttons option1="This is a test" option2="Go elsewhere"/>
<TextInput heading="Asking user for something" type="text" />
<SecondaryButton name="Back" />
<PrimaryButton name="Continue" destination="test" />



