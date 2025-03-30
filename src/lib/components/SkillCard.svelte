<script>
  import 'iconify-icon';
  let { name, id } = $props();
</script>

<div
  class="flex flex-col gap-2 rounded-md border-4 border-black bg-yellow-400 p-6 text-black drop-shadow-2xl"
>
  <iconify-icon icon="skill-icons:{id}" width="64" height="64"></iconify-icon>
  <p class="pt-12">{name}</p>
</div>
