<script lang='ts'>
    import * as Card from '$lib/components/ui/card'
</script>

<header class="grid grid-cols-3 items-center">
    <a href="/" class="ml-4 hover:underline italic font-light">back to home</a>
    <h1 class="text-6xl text-primary font-bold font-heading mt-8 text-center">My Projects</h1>
</header>

<div class="grid grid-cols-4 p-16 gap-2 w-full" data-sveltekit-preload-data='hover'>
    <a href="/projects/hsse-rjbb-online" class="col-start-1 col-end-2">
        <Card.Root class="hover:scale-105 transition-transform duration-150 p-4">
            <Card.Header class="text-center">
                <Card.Title>
                    Online Safety Report Portal
                </Card.Title>
                <Card.Description>
                    HSSE division of PT. Pertamina Patra Niaga' West Java Region Branch
                </Card.Description>
            </Card.Header>
        </Card.Root>
    </a>

</div>
