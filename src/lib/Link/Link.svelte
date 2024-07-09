<script>
    export let href;

    $: props = {
        class: [
            "vbb-link"
        ]
    }
</script>

<a {...props} href="{href}"><slot/></a>