<script>
  import SkillCard from './SkillCard.svelte';
</script>

<div class="bg-purple-300 pb-2">
  <h3 id="skills" class="mx-auto pt-4 pb-5 text-center text-5xl font-black">
    Skills
  </h3>
  <div
    class="mx-auto grid w-3/4 min-w-[300px] grid-cols-2 grid-rows-2 content-center items-center justify-center gap-10 font-semibold lg:grid-cols-4 lg:text-2xl"
  >
    <SkillCard name="HTML" icon="skill-icons:html" />
    <SkillCard name="CSS" icon="skill-icons:css" />
    <SkillCard name="Javascript" icon="skill-icons:javascript" />
    <SkillCard name="Svelte" icon="skill-icons:svelte" />
    <SkillCard name="Tailwind" icon="skill-icons:tailwindcss-dark" />
    <SkillCard name="Vite" icon="skill-icons:vite-dark" />
    <SkillCard name="pnpm" icon="skill-icons:pnpm-dark" />
    <SkillCard name="Python" icon="skill-icons:python-dark" />
    <SkillCard name="Java" icon="skill-icons:java-dark" />
    <SkillCard name="Git" icon="skill-icons:git" />
    <SkillCard name="Vim" icon="skill-icons:vim-dark" />
    <SkillCard name="Stack Overflow" icon="skill-icons:stackoverflow-dark" />
  </div>
</div>
