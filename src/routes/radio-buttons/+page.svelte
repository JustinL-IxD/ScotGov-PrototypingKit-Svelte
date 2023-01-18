<script>
    import H1 from "$lib/Typography/H1.svelte";
	import RadioButton from "$lib/Forms/RadioButton.svelte";
	import TextInput from "$lib/Forms/TextInput.svelte";
    import radioAnswer from "$lib/Forms/RadioButton.svelte";
    $: console.log(radioAnswer);
</script>


<H1>Do you exercise regularly?</H1>
<RadioButton />
<TextInput />



