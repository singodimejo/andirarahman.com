<script lang="ts">
    import "../app.pcss";
    import { ModeWatcher } from "mode-watcher";
</script>
<svelte:head>
    <link rel="preload" as="font" href="https://fonts.googleapis.com/css2?family=Josefin+Sans:ital,wght@0,100..700;1,100..700&family=Montserrat:ital,wght@0,100..900;1,100..900&display=swap">
</svelte:head>
<ModeWatcher />
<slot />