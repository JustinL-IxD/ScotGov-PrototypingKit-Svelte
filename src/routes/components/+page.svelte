<script>
    import H1 from '$lib/Typography/H1.svelte';
    import H2 from '$lib/Typography/H2.svelte';
    import H3 from '$lib/Typography/H3.svelte';
    import H4 from '$lib/Typography/H4.svelte';
    import H5 from '$lib/Typography/H5.svelte';
    import Leader from '$lib/Typography/Leader.svelte';
    import Body from '$lib/Typography/Body.svelte';
    import Small from '$lib/Typography/Small.svelte';
    import PrimaryButton from '$lib/Buttons/PrimaryButton.svelte';
	import SecondaryButton from '$lib/Buttons/SecondaryButton.svelte';
	import TextInput from '$lib/Forms/TextInput.svelte';
    import RadioButtons from '$lib/Forms/RadioButtons.svelte';
	import Textarea from '$lib/Forms/Textarea.svelte';
</script>

<div>
    <H1>This is a heading one</H1>
</div>

<div class="mt-[-40px]">
    <H2>This is a heading two</H2>
</div>

<div class="mt-4">
    <H3>This is a heading three</H3>
</div>

<div class="mt-4">
    <H4>This is a heading four</H4>
</div>

<div class="mt-4">
    <H5>This is a heading five</H5>
</div>

<div class="mt-4">
    <Leader>This is a leader</Leader>
</div>

<div class="mt-4">
    <Body>This is a body paragraph</Body>
</div>

<div class="mt-[-20px]">
    <Small>This is a small paragraph</Small>
</div>

<div class="mt-4">
    <SecondaryButton name="Back" />
    <PrimaryButton name="Next" />
</div>

<div class="mt-6">
    <RadioButtons />
</div>

<div class="mt-2">
    <TextInput />
</div>

<div class="mt-2">
    <Textarea />
</div>