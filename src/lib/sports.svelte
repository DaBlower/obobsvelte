<script>
    import sports from '../sports.json';
</script>
<div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6 justify-items-center mx-auto">
    {#each sports as sport}
        <a href="{sport.link}">
            <div class="bg-white rounded-lg shadow-md p-4 hover:scale-105 transition-transform text-black">
                <div class="h-1/2 w-full">
                    <img src="{sport.image}" alt="A image of the sport {sport.name}">
                </div>
                <div class="h-1/2 w-full flex items-center justify-center">
                    <p class="text-lg text-center">{sport.name}</p>
                </div>
            </div>
        </a>
    {/each}
</div>