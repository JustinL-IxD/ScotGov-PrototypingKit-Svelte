<script>
    import H1 from '$lib/Typography/H1.svelte';
    import Body from '$lib/Typography/Body.svelte';
    import Small from '$lib/Typography/Small.svelte';
    import PrimaryButton from '$lib/Buttons/PrimaryButton.svelte';
	import SecondaryButton from '$lib/Buttons/SecondaryButton.svelte';
	import TextInput from '$lib/Forms/TextInput.svelte';
</script>

<H1>Test page</H1>

<div>
    <Body>This is ADP</Body>
    <TextInput type="text" heading="Test heading" />
    <SecondaryButton name="Back" />
    <PrimaryButton name="Next" destination="/" />
</div>