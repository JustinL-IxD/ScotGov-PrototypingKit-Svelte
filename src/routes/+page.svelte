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
	import RadioButton from '$lib/Forms/RadioButton.svelte';
</script>




<div>
    <H1>This is a heading one</H1>
    <H2>This is a heading two</H2>
    <H3>This is a heading three</H3>
    <H4>This is a heading four</H4>
    <H5>This is a heading five</H5>
    <Leader>This is a leader</Leader>
    <Body>This is a body paragraph</Body>
    <Small>This is a small paragraph</Small>
</div>



<div class="mt-8">
    <TextInput />
    <RadioButton />
</div>

<div class="mt-8">
    <SecondaryButton />
    <PrimaryButton />
</div>

<div class="mt-8">
    <H1>Adult Disability Payment</H1>
    <H3>Something else</H3>
    <Body>This is ADP</Body>
    <TextInput />
    <SecondaryButton />
    <PrimaryButton />
</div>



