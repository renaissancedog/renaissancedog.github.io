<script>
  import Project from '../../lib/components/Project.svelte';
</script>

<main class="m-auto w-full space-y-4 text-xl lg:w-1/2">
  <h1 class="mb-2 text-center text-5xl font-bold">Projects</h1>
  <p class="mb-2 ml-2 text-xl">Stuff that I've built.</p>
  <Project
    link="https://renaissancedog.github.io/reagan-schedule"
    title="Reagan Bell Schedule"
    body="An app to keep track of the bell schedule!"
  />
  <Project
    link="https://renaissancedog.github.io/qrcode/"
    title="QR Code Generator"
    body="Tired of annoying Internet QR code generators? Use mine! It's free, ad-free, intuitive, and definitely doesn't look like it's from 2005!"
  />
  <Project
    link="https://github.com/renaissancedog/cp-solutions"
    title="Competitive Programming Solutions"
    body="Solutions I wrote in Java - primarily USACO, also some DSA and UIL"
  />
  <Project
    link="https://reagan-uil.github.io"
    title="Reagan HS UIL Website"
    body="Our school UIL team's webpage"
  />
  <Project
    link="https://samathcircle.github.io"
    title="San Antonio Math Circle Website"
    body="The official website of the San Antonio Math Circle"
  />
  <Project
    link="https://renaissancedog.github.io/rrcsclub/"
    title="Reagan Computer Science Club Website"
    body="School Club website rebuilt with Svelte"
  />
</main>
