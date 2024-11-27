<script>
	export let title, body, link;
</script>

<div class="mt-4 flex flex-col rounded-xl bg-gray-700 p-4">
	<h3 class="pb-2 text-3xl text-gray-300">{title}</h3>
	<p class="text-xl text-gray-300">{body}</p>
	<a
		class="break-words text-lg text-gray-400 underline"
		target="_blank"
		href={link}>{link}</a
	>
</div>
