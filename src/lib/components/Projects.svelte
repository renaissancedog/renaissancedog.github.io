<script>
  import ProjectCard from './ProjectCard.svelte';
</script>

<div class="mt-8 border-y-8 bg-purple-300">
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
      name="Currency Converter"
      body="A simple converter made for a comp sci class project."
      lang="Java"
      link="https://github.com/renaissancedog/currency-converter"
    />
    <ProjectCard
      name="Reagan Academic UIL Website"
      body="The official website of our team - built from scratch."
      lang="Typescript, Svelte, Tailwind"
      link="https://reagan-uil.github.io/"
    />
    <ProjectCard
      name="Budget Cookie Clicker"
      body="A relic of the past - it's the first programming project I ever made! Very buggy."
      lang="HTML, CSS, Javascript"
      link="https://renaissancedog.github.io/projects/cookie.html"
    />
    <ProjectCard
      name="My personal website"
      body="You're looking at it!"
      lang="Svelte, Tailwind"
      link="https://github.com/renaissancedog/renaissancedog.github.io"
    />
  </div>
</div>
