<script>
  import 'iconify-icon';
  let { name, body, link, lang } = $props();
</script>

<div
  class="mb-2 flex w-full flex-col gap-2 rounded-md border-4 border-black bg-yellow-400 p-6 drop-shadow-2xl"
>
  <div>
    <h1 class=" text-3xl font-black">{name}</h1>
  </div>
  <p>{body}</p>
  <p>Languages/frameworks used: {lang}</p>
  <a
    aria-label="Open link"
    class="break-words underline"
    target="_blank"
    href={link}
  >
    <svg
      xmlns="http://www.w3.org/2000/svg"
      width="32"
      height="32"
      viewBox="0 0 16 16"
      ><path
        fill="currentColor"
        d="M14.21 1.5H10v1.25h3.08L7.9 7.21l.82 1l5.53-4.77V7h1.25V2.79a1.29 1.29 0 0 0-1.29-1.29"
      /><path
        fill="currentColor"
        d="M12.25 13.25H1.75v-8.5H7.5V3.5h-6a1 1 0 0 0-1 1v9a1 1 0 0 0 1 1h11a1 1 0 0 0 1-1v-4h-1.25z"
      /></svg
    >
  </a>
</div>
