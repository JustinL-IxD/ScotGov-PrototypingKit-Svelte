<script lang="ts">
	import H4 from "$lib/Typography/H4.svelte";
    export let heading:string;
    export let type:string;
</script>

<label class="text-body font-bold">{heading ? heading : "Enter name for field"}</label>
<input type={type ? type : "text"} class="block border-2 border-DarkGrey h-6 w-[350px] mb-6 p-1
    focus:outline 
    focus:outline-2 
    focus:outline-SecondaryYellow
    focus:shadow-textInput
"/>