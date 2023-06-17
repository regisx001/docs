<script>
	import Navbar from '$lib/Components/Navbar.svelte';

	import '../app.postcss';
</script>

<header>
	<Navbar />
</header>

<main class="relative flex justify-center mx-auto max-w-8xl sm:px-2 lg:px-8 xl:px-12">
	<slot />
</main>
