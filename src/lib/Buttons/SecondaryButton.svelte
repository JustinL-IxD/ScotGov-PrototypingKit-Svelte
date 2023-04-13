<script lang="ts">
    export let name:String;
    export let destination:String;
</script>

<button 
    class=" text-DarkGrey text-center pr-3 pl-3 pt-2 pb-2 mr-1  outline outline-offset-[-2px] outline-2 outline-DarkGrey mr-1
        hover:bg-[#ebebeb]
        active:bg-SecondaryYellow 
        active:text-DarkGrey 
        active:shadow-button
        active:outline-none
        "
        
    >
    <a href="./{destination}">{name ? name : "Cancel"}</a>
</button>



<!--

outline-2 outline-offset-[2px] outline-DarkGrey
-->