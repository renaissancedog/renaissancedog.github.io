<script>
	export let title, body;
</script>

<div class="mt-4 flex flex-col rounded-xl bg-green-900 p-4">
	<h3 class="pb-2 text-3xl text-gray-100">{title}</h3>
	<p class="text-xl text-gray-100">{@html body}</p>
</div>
