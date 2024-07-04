<script>
    export let title;

    let classButton;
    $: classButton = ' p-4 w-8 '
</script>

<button class={classButton} on:click={() => (console.log('boton'))}>
    {title}
</button>

