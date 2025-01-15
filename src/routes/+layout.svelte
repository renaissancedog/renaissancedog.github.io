<script>
  import '../app.css';
  import Navbar from '../lib/components/Navbar.svelte';
  import { base } from '$app/paths';
</script>

<svelte:head>
  <title>William Liu</title>
</svelte:head>
<div class="min-h-full bg-sky-50 text-black">
  <Navbar {base} />
  <slot></slot>
</div>
