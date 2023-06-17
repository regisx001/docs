<script lang="ts">
	import Hero from '$lib/Components/Hero.svelte';
	import BottomNavigation from '$lib/Components/BottomNavigation.svelte';
	import SideNavigation from '$lib/Components/SideNavigation.svelte';
</script>

<SideNavigation />

<div class="flex-auto max-w-2xl min-w-0 px-4 py-10 lg:max-w-none lg:pr-0 lg:pl-8 xl:px-16">
	<Hero />

	<BottomNavigation />
</div>
