<script>
	export let title, body, link;
</script>

<div class="mt-4 flex flex-col rounded-xl bg-green-900 p-4">
	<h3 class="pb-2 text-3xl text-gray-100">{title}</h3>
	<p class="text-xl text-gray-100">{body}</p>
	<a
		class="break-words text-lg text-cyan-400 underline"
		target="_blank"
		href={link}>{link}</a
	>
</div>
