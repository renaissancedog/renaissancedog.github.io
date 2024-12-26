<script>
	export let title, body, link;
</script>

<div class="mt-4 flex flex-col rounded-xl bg-sky-200 p-4">
	<h3 class="pb-2 text-3xl">{title}</h3>
	<p class="text-xl">{body}</p>
	<a
		class="break-words text-lg underline"
		target="_blank"
		href={link}>{link}</a
	>
</div>
