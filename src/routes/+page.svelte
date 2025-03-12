<script>
  import Row from '../lib/components/Row.svelte';
</script>

<main class="m-auto w-full space-y-4 text-xl lg:w-1/2">
  <h1 class="mb-4 text-center text-5xl font-bold">About Me!</h1>
  <Row
    title="My Education"
    body="I am currently a sophomore at Ronald Reagan High School in San Antonio, Texas (expected graduation May 2027) with a 99.1 unweighted and 105.8 weighted GPA."
  />
  <Row
    title="My Academic Interests"
    body="I am interested in most STEM-related fields, but I especially enjoy mathematics (algebra and probability in particular) and computer science (check out
		 <a class=underline target=_blank href=https://github.com/renaissancedog>my GitHub!</a>)"
  />
  <p>And some stuff I do for fun:</p>
  <Row
    title="Violin"
    body="I'm an orchestra kid. Currently learning the Butterfly Lovers' Concerto!"
  />
  <Row
    title="Swimming"
    body="I was on the school swim team for a year (we don't talk about my times though). I've also done summer league swimming for 6 years."
  />
  <Row
    title="Exercise in general"
    body="Personal bests: 22 minute 5K, ~6:30 minute mile, 11 pull-ups, 36 push-ups"
  />
  <Row title="Playing The Game" body="You just lost" />
</main>
