<script lang="ts">
	import SearchSvg from './SearchSvg.svelte';
</script>

<nav
	class="h-[50px] bg-gradient-to-b from-[#0C071E]  to-[#312562] absolute w-full bottom-0 text-white"
>
	<ul class="flex gap-[50px] text-center items-center justify-center font-semibold">
		<li class="w-[52.9px]"><a href="#">Free games</a></li>

		<li class="w-[52.9px]">
			<a href="#">Game Prices</a>
		</li>

		<li class="w-[52.9px]">
			<a href="#">Tips & Tricks</a>
		</li>

		<li class="w-max">
			<SearchSvg />
		</li>
	</ul>
</nav>
