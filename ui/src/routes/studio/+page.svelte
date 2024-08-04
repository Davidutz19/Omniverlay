<script lang="ts">
    import Sidebar from "$lib/components/studio/Sidebar.svelte";
    import { invoke } from "@tauri-apps/api";
    import { onMount } from "svelte";

    
</script>

<main class="container">
    <Sidebar />

    
</main>

<style>
    .container {
        display: flex;
        flex-direction: row;
    }
</style>
