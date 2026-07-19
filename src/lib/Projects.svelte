<script>
  import ProjectCard from './ProjectCard.svelte';
</script>

<div class="border-b-8 bg-white pb-4">
  <h3
    id="projects"
    class="mx-auto p-8 pt-15 pb-10 text-center text-5xl font-black"
  >
    Projects
  </h3>
  <div
    class="mx-auto flex w-3/4 flex-col content-center items-center justify-center gap-10 font-semibold md:grid-cols-5 md:text-2xl"
  >
    <ProjectCard
      name="Reagan Bell Schedule App"
      body="An app to keep track of my school's bell schedule."
      link="https://renaissancedog.github.io/reagan-schedule/"
      lang="Javascript, Svelte"
    />
    <ProjectCard
      name="Fourier Epicycle Drawer"
      body="A simulation of a Fourier transform. It takes a path you trace with your mouse and draws it as a chain of a lot of rotating circles (epicycles). Inspired by 3Blue1Brown."
      link="https://renaissancedog.github.io/fourier/"
      lang="Javascript"
    />
    <ProjectCard
      name="Valentine's Day Applet"
      body="Your crush (literally) can't say no to this one! It's a cute little applet to send your special someone a Valentine's Day message. 
      It even has fun animations!"
      link="https://renaissancedog.github.io/valentine/"
      lang="Javascript, Svelte"
    />
    <ProjectCard
      name="Reagan GPA Calculator"
      body="A GPA calculator for those like myself too lazy to do the math by hand."
      link="https://renaissancedog.github.io/gpa-calculator/"
      lang="Javascript, Svelte"
    />
    <ProjectCard
      name="Alarm Clock"
      body="Source code for my custom alarm clock. I designed and prototyped it with an Ardino and breadboard circuits, and wrote C++ code to run it. 
      Featuring a brand-new, mesmerizing 16x2 LCD display!"
      lang="C++"
      link="https://github.com/renaissancedog/alarmclock"
    />
    <ProjectCard
      name="QR Code Generator"
      body="Tired of annoying Internet QR code generators? Use mine! It's free, ad-free, intuitive, and definitely doesn't look like it's from 2005!"
      lang="Javascript"
      link="https://renaissancedog.github.io/qrcode/"
    />
    <ProjectCard
      name="My website"
      body="You're looking at it."
      lang="Svelte"
      link="https://github.com/renaissancedog/renaissancedog.github.io"
    />
  </div>
</div>
