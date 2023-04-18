<script>
	import PrimaryButton from "$lib/Buttons/PrimaryButton.svelte";
import SecondaryButton from "$lib/Buttons/SecondaryButton.svelte";
import RadioButtons from "$lib/Forms/RadioButtons.svelte";
import TextInput from "$lib/Forms/TextInput.svelte";
    import H1 from "$lib/Typography/H1.svelte";
</script>

<H1>About User</H1>
<TextInput heading="first name"/>
<RadioButtons option1="Option 1 text" option2="Option 2 text" />
<SecondaryButton name="Back" destination="about-the-benefit" /> 
<PrimaryButton name="Continue" destination="about-scotgov" />