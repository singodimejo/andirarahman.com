<script lang="ts">
    import { TextChangingLink } from '$lib/components/custom/text-changing-link'
</script>

<header class="flex flex-col h-[95vh] items-start text-xl md:text-2xl lg:text-3xl text-left font-heading justify-center py-8 px-16 gap-4">
    <TextChangingLink href='/about-me' values={{default: 'Andira Rahman Imani', hover: 'About me'}}>
        Hello there! My name is
    </TextChangingLink>
    <TextChangingLink href='/socials' values={{default: 'Aan', hover: 'My Socials'}}>
        but you can call me
    </TextChangingLink>
    <TextChangingLink href='/projects' values={{default: 'Fullstack JS Web Developer', hover: 'See My Projects'}}>
        I am a
    </TextChangingLink>
    <p>currently based in South Jakarta, Indonesia.</p>
    <TextChangingLink href='mailtp:andira.a2n@gmail.com' values={{default: 'Talk to me!', hover: 'Email me!'}}>
        Want to collaborate on a project? 
    </TextChangingLink>
</header>