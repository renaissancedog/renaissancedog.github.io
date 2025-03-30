<script>
  import About from '../lib/components/About.svelte';
  import Header from '../lib/components/Header.svelte';
  import Navbar from '../lib/components/Navbar.svelte';
  import Projects from '../lib/components/Projects.svelte';
  import Skills from '../lib/components/Skills.svelte';
  import { base } from '$app/paths';
</script>

<div class="min-h-full bg-yellow-100 text-black">
  <Navbar {base} />
  <Header />
  <About />
  <Skills />
  <Projects />
</div>
