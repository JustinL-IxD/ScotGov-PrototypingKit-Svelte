<script>
    export let radioAnswer = "";
    $: console.log(radioAnswer)
</script>

<label class="block">
    <input type="radio" name="exercise" value="yes" bind:group={radioAnswer}>
    Yes, all the time
</label>
<label class="block">
    <input type="radio" name="exercise" value="no" bind:group={radioAnswer}>
    No, I never exercise
</label>
<label class="block">
    <input type="radio" name="exercise" value="sometimes" bind:group={radioAnswer}>
    Sometime I exercise
</label>


