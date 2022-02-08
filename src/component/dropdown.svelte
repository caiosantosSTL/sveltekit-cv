
<script>
    import Card from '../component/mycard.svelte'
    export let title = 'title'
</script>

<main>
    <div class="dropdown dropdown-top dropdown-hover">
        <div tabindex="0" class="m-1 btn">{title}</div> 
        
        <div class="p-2 shadow dropdown-content bg-base-100 rounded-box w-54">
            <slot></slot>
            
        </div>
        
      </div>
</main>