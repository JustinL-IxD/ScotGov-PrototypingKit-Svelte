<script lang="ts">
    export let name:String;
</script>

<button 
    class=" text-DarkGrey text-center p-2 outline outline-offset-[-2px] outline-2 outline-DarkGrey mr-1
        hover:bg-[#ebebeb]
        active:bg-SecondaryYellow 
        active:text-DarkGrey 
        active:shadow-button
        active:outline-none
        "
        
    >
    {name ? name : "Cancel"}
</button>



<!--

outline-2 outline-offset-[2px] outline-DarkGrey
-->