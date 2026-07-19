<script>
  import 'iconify-icon';
  let { name, icon } = $props();
</script>

<div
  class="flex flex-col gap-2 rounded-md border-4 border-black bg-white p-6 drop-shadow-2xl"
>
  <iconify-icon {icon} width="64" height="64"></iconify-icon>
  <p class="pt-12">{name}</p>
</div>
