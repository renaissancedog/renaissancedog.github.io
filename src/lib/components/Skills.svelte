<script>
  import SkillCard from './SkillCard.svelte';
</script>

<h3 id="skills" class="mx-auto mt-4 mb-20 text-center text-5xl font-black">
  Skills
</h3>
<div
  class="mx-auto grid w-3/4 min-w-[300px] grid-cols-2 grid-rows-2 content-center items-center justify-center gap-10 font-semibold lg:grid-cols-4 lg:text-2xl"
>
  <SkillCard name="HTML" id="html" />
  <SkillCard name="CSS" id="css" />
  <SkillCard name="Javascript" id="javascript" />
  <SkillCard name="Svelte" id="svelte" />
  <SkillCard name="Tailwind" id="tailwindcss-dark" />
  <SkillCard name="Vite" id="vite-dark" />
  <SkillCard name="pnpm" id="pnpm-dark" />
  <SkillCard name="Python" id="python-dark" />
  <SkillCard name="Java" id="java-dark" />
  <SkillCard name="Git" id="git" />
  <SkillCard name="Vim" id="vim-dark" />
  <SkillCard name="Stack Overflow" id="stackoverflow-dark" />
</div>
