<script>
	import Row from '../lib/components/Row.svelte';
</script>

<main class="m-auto w-full text-xl lg:w-1/2">
	<h1 class="mb-4 text-center text-5xl font-bold">About Me!</h1>
	<Row
		title="My Education"
		body="I am currently a sophomore at Ronald Reagan High School in San Antonio, Texas (expected graduation May 2027) with a 105.1 weighted GPA."
	/>
	<Row
		title="My Academic Interests"
		body="I am interested in most STEM-related fields, but I especially enjoy mathematics (algebra and probability in particular) and computer science (check out
		 <a class=underline target=_blank href=https://github.com/renaissancedog>my GitHub!</a>)"
	/>
	<Row
		title="My Hobbies"
		body="In my free time, I like to read, play violin, run, swim, play video games, and sleep."
	/>
</main>
