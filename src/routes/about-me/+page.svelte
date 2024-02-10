<script lang="ts">
    // import type { PageData } from './$types';
    
    // export let data: PageData;
</script>

<header class="grid grid-cols-3 items-center">
    <a href="/" class="ml-4">back to home</a>
    <h1 class="text-center text-6xl text-primary font-heading font-bold mt-4">About Me</h1>
</header>

<article class="px-8">
    <h2>I am...</h2>
    <p class="whitespace-pre-line text-lg">
        ...a human (<em>he/him</em>) born on 1999 in Surabaya, Indonesia 
        ...the first of three siblings to a brilliant family.
        ...in a loving relationship to a beautiful and passionate woman, Maya.
        ...practicing the Islamic religion casually and peacefully.
        ...stubbornly refusing to pursue a career inline with my Mechanical Engineering Bachelor's Degree from <a href="https://its.ac.id/tmesin" target="_blank" rel="noopener noreferrer">ITS</a>.
        ...currently an <strong><em>IT System Officer</em></strong> for <a href="https://pertamc.com" target="_blank" rel="noopener noreferrer">PT. Pertamina Maintenance and Construction</a>.
        ...a enthusiastic <strong><em>freelance web developer</em></strong>. if you have a project or a question in mind, <a href="mailto:andira.a2n@gmail.com">come say hi!</a>
    </p>
</article>

<article class="px-8 text-right">
    <h2>My Journey So Far</h2>
    <p class="whitespace-pre-line text-lg">
        Started teaching myself to code during the pandemic, around late 2021.
        Stopped my web development studies to finish my final thesis. 
        Resumed web development studies on 2022, went straight to taking freelance client.
        Created an awesome custom form for the project and learned to do it <i>on-the-fly</i>.
        Completed the project (<i>surprisingly</i>) and finished college (<i>thankfully</i>).
        Took another more relaxing freelance gig refactoring a project's UI elements. <i>it went okay</i>.
        Got a <b>Job Offer</b> from a subsidiary of a big company. <b><i>And I took it</i></b>.
        Currently freelancing as a side-gig until the current day job contract expires. 
        Got a project in mind? <a href="mailto:andira.a2n@gmail.com">let's talk about it!</a>
    </p>
</article>

<style lang="postcss">
    h2 {
        @apply text-2xl font-semibold;
    }
    a {
        @apply italic font-light 
            hover:underline;
    }
</style>