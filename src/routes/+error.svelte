<script lang="ts">
    import { page } from '$app/stores';
</script>

<div class="w-full min-h-screen grid items-center text-center">
    <div>
        <h1 class="text-6xl text-accent font-heading font-bold">{$page.status}: {$page.error?.message}</h1>
        <a href="/" class="italic hover:underline">back to home</a>
    </div>
</div>