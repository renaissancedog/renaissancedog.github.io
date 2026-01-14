<script>
  import ProjectCard from './ProjectCard.svelte';
</script>

<div class="border-b-8 bg-yellow-100 pb-4">
  <h3
    id="projects"
    class="mx-auto mt-4 mb-20 p-8 text-center text-5xl font-black"
  >
    Projects
  </h3>
  <div
    class="mx-auto flex w-3/4 flex-col content-center items-center justify-center gap-10 font-semibold md:grid-cols-5 md:text-2xl"
  >
    <ProjectCard
      name="Reagan Bell Schedule App"
      body="An app to keep track of the bell schedule! Extremly functional."
      link="https://renaissancedog.github.io/reagan-schedule/"
      lang="Javascript, Tailwind, Svelte"
    />
    <ProjectCard
      name="Reagan GPA Calculator"
      body="Self-explanatory - a GPA calculator for those like myself too lazy to do it by hand."
      link="https://renaissancedog.github.io/gpa-calculator/"
      lang="Javascript, Tailwind, Svelte"
    />
    <ProjectCard
      name="QR Code Generator"
      body="Tired of annoying Internet QR code generators? Use mine! It's free, ad-free, intuitive, and definitely doesn't look like it's from 2005!"
      lang="Javascript, Tailwind"
      link="https://renaissancedog.github.io/qrcode/"
    />
    <ProjectCard
      name="TMEA Webscraper"
      body="A tool to get audition results from the TMEA website."
      lang="Python"
      link="https://github.com/renaissancedog/tmea"
    />
    <ProjectCard
      name="Competitive Programming Solutions"
      body="A collection of my solutions to competitive programming problems."
      lang="Java"
      link="https://github.com/renaissancedog/cp-solutions"
    />
    <ProjectCard
      name="My personal website"
      body="You're looking at it!"
      lang="Svelte, Tailwind"
      link="https://github.com/renaissancedog/renaissancedog.github.io"
    />
  </div>
</div>
