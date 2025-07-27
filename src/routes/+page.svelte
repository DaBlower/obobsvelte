<script>
    import Sports from '$lib/sports.svelte';
</script>

<div class="bg-blue-600 text-white text-center">
    <h1 class="text-3xl">Hi, I'm Oliver!</h1>
    <p class="text-xl">Welcome to my personal website!</p>
    <p>Here you can find stuff about me, what I like and my projects</p>

    <div class="flex justify-center p-8">
        <button class="bg-white  text-blue-600 font-bold p-4 rounded hover:scale-105">
            <a href="https://github.com/DaBlower">Check Out my Github</a>
        </button>
    </div>

    <div class="flex flex-col items-center px-4">
        <h1 class="text-xl mb-6">My favourite sports</h1>
        <div class="max-w-6xl w-full">
            <Sports />
        </div>
    </div>
</div>

<footer class="text-center p-10 flex justify-center bg-blue-600 text-white">
    Made with <span class="hover:animate-bounce">❤️</span> by obob :D
</footer>