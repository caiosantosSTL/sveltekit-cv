
<script>
    export let picsrc = '../img/blender.png'
    export let text = 'Lorem ipsum dolor sit amet.'
    export let link = '#'
    export let title = 'my title'
</script>

<main>
    <div class="flex flex-col p-2  w-52 card border-black border-2">
        <div class="flex justify-center">
            <img src={picsrc} class="w-40 rounded-2xl" alt="">
        </div>
        <div class="flex justify-center">{title}</div>
        <div>
            <p class="text-center flex flex-wrap p-2">{text} 
                
            </p>
            {#if link === "#"}
                <p class="hover:text-red-500">Examples soon</p>
            {:else}
                <a href="{link}" class="hover:text-blue-500">Examples here</a>
            {/if}
        </div>

    </div>

</main>