<script>
    $: props = {
        class: [
            "vbb-btn"
        ]
    }
</script>

<button
    on:click
    on:focus
    on:blur
    on:mouseover
    on:mouseenter
    on:mouseleave
    {...props}
>
    <slot/>
</button>