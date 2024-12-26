<script>
	export let title, body;
</script>

<div class="mt-4 flex flex-col rounded-xl bg-sky-200 p-4">
	<h3 class="pb-2 text-3xl">{title}</h3>
	<p class="text-xl">{@html body}</p>
</div>
