<script lang="ts">

</script>

<header class="flex flex-col h-[95vh] items-center justify-center p-8">
    <h1 class="whitespace-pre-line text-2xl text-center font-heading">
        Hello there! I'm <a href="/about-me" data-before="About Me">Andira Rahman Imani</a> 
        but you can <a href="/socials" data-before="My Socials">call me Aan</a>
        I am a <a href="/projects" data-before="My Projects">Javascript Web Developer</a> 
        currently based in South Jakarta, Indonesia.
        Want to collaborate on a project? <a href="mailto:andira.a2n@gmail.com" data-before="Email me!">Talk to me!</a>
    </h1>
</header>

<style lang='postcss'>
    h1 a {
        @apply 
            text-3xl text-primary relative
            hover:invisible
            before:content-[attr(data-before)] before:absolute before:invisible before:w-full
            before:hover:visible before:hover:text-primary
            ;
            /* active:text-primary/50 hover:text-primary/75 
            transition-colors duration-150;    */
    }
</style>