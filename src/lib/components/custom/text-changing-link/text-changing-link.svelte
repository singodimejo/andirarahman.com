<script lang="ts">
    import { fade } from 'svelte/transition';

    export let href: string
    export let values: Values
    type Values = { default: string, hover: string }

    let isHovered: boolean = false
    $: value = isHovered ? values.hover : values.default
</script>

<p 
    class="w-full"
    on:mouseenter={() => isHovered = true}
    on:mouseleave={() => isHovered = false}
>
    <slot />
    {#key value}
        <a
            {href}
            class="text-primary"
            out:fade={{duration: 150}}
            in:fade={{delay: 150, duration:150}}
        >
            {value}
        </a>
    {/key}
</p>


<!-- <div 
    class="block text-left"
    >
    <div class="w-full flex items-baseline justify-center gap-2">
        <p><slot /></p>
        <div 
            on:pointerenter={() => isHovered = true}
            on:pointerleave={() => isHovered = false}  
            class="w-96 block"
            >
            {#key value}
            <a
                {href}
                class={cn("text-3xl text-primary text-nowrap")}
                out:fade={{duration: 150}}
                in:fade={{delay: 150, duration:150}}
            >
                {value}
            </a>
            {/key}
        </div>
    </div>
</div> -->