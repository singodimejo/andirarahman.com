<script lang="ts">
    // import type { PageData } from './$types';

    import { AspectRatio } from '$lib/components/ui/aspect-ratio'
    import * as Carousel from '$lib/components/ui/carousel';
    
    // export let data: PageData;
</script>

<div class="grid grid-cols-4 mt-4 items-center">
    <a href="/projects" class="ml-4 hover:underline italic font-light">back to projects</a>
    <header class="col-start-2 col-end-4">
        <h1 class="text-3xl text-center text-accent font-bold font-heading">
            Online Safety Report Portal
        </h1>
        <h2 class="mt-4 text-2xl text-center text-primary font-bold font-heading">
            PT. Pertamina Patra Niaga
        </h2>
    </header>
</div>


<div class="px-32 py-4">
    <Carousel.Root class='w-full'>
        <Carousel.Content>
            <Carousel.Item>
                <AspectRatio ratio={16 / 9}>
                    <img src="/hsse_rjbb_login_page.jpg" class="rounded-xl" alt="">
                </AspectRatio>
            </Carousel.Item>
            <Carousel.Item>
                <AspectRatio ratio={16 / 9}>
                    <img src="/hsse_rjbb_forms_1.jpg" class="rounded-xl" alt="">
                </AspectRatio>
            </Carousel.Item>
            <Carousel.Item>
                <AspectRatio ratio={16 / 9}>
                    <img src="/hsse_rjbb_forms_2.jpg" class="rounded-xl" alt="">
                </AspectRatio>
            </Carousel.Item>
        </Carousel.Content>
        <Carousel.Previous />
        <Carousel.Next />
    </Carousel.Root>
</div>

<article class="px-32 pb-8 space-y-4">
    <h3 class="text-2xl font-heading font-semibold">Overview</h3>
    <p>
        PT. Pertamina Patra Niaga is an oil and gas distribution company which needs to operates under tight safety regulations and thus need an accessible way to create and manage safety reports from the field. Thus we collaborated to create an online portal for creating, reviewing, and managing said safety report documents. It's complete with authentication logic to make the app more private and secure, automated email notifications, PDF generation, and OneDrive backup to ensure smooth operations, custom form input to match the document's format, and database CRUD functionalities for both the user accounts and the reports.
    </p>
    <ul class="list-disc list-inside">
        <h3 class="text-2xl font-heading font-semibold">Tech Stack</h3>
        <li>
            Sveltekit w/ Typescript
        </li>
        <li>
            Tailwind CSS 
        </li>
        <li>
            Daisy UI component library
        </li>
        <li>
            MongoDB 
        </li>
        <li>
            GCP Cloud Storage
        </li>
        <li>
            Microsoft Graph
        </li>
        <li>
            GCP App Engine
        </li>
    </ul>
</article>