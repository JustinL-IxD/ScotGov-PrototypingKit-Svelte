<script lang="ts">
    export let name:String;
    export let destination:String;
</script>


<button 
    class="bg-PrimaryBlue text-white text-center p-2 m-1
        hover:bg-SecondaryBlue 
        active:bg-SecondaryYellow 
        active:text-DarkGrey 
        active:shadow-button"
    >
    <a href="/{destination}">{name ? name : "Start"}</a>
</button>