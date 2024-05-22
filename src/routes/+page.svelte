<script>
    import { Button } from "$lib/components/ui/button";
</script>

<h1>Welcome to SvelteKit</h1>
<p>Visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to read the documentation</p>

<p>Click <a href="test">here</a> for other route</p>

<Button>Random button</Button>

<style lang="scss">
    a {
        text-decoration: underline;
    }

    :global(Button) {
        background-color: orange;
    }
</style>
