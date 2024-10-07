<script>
    import Header from '$lib/components/Header.svelte';
    import Body from '$lib/components/Body.svelte';
</script>
    
<Header />

<slot />

<h1>Layout</h1>

<style>
    h1 {
        color: purple;
    }
</style>
    
    