<script>
    import "../app.css"; 
    import Header from '$lib/Header/Header.svelte';
	import PartOf from "$lib/Header/PartOf.svelte";
</script>

<Header />
<PartOf name="Pension Age Disability Payment" />
<slot />