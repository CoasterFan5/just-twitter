<script lang="ts">
    import '@fontsource-variable/raleway';
</script>

<div>
    <slot/>
</div>

<style lang="scss">
    :global(body) {
        --bg: #1c1c1c;
        --text: #f1f1f1;

        font-family: 'Raleway Variable', sans-serif;
        background: var(--bg);
        color: var(--text);

        margin: 0px;
    }
</style>

